# Tuesday

## What is the difference between a primary key and a foreign key
Primary key is the 'most important' key on a table, typically the id. The foreign key is typically the 'primary key' on a different table that you want attached to it.
## What is an Alias?
An alias is an alternate name or nickname for an object. For example for the table teachers you could alias it out as 't'.
## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

string sql = @"
      SELECT 
        d.*,
        p.*
      FROM doctors d
      JOIN patients p ON p.Id = d.patientId
      WHERE d.id = @id
      ";
      return _db.Query<Doctor, Patient, Doctor>(sql, (dr, pt) =>
      {
        dr.patientId =pt.id;
        return dr;
      }, new { id }, splitOn: "id").ToList()

