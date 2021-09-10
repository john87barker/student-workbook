# Wednesday

## What is SQL injection?
It is an attack where someone can inject sql data into database query.
## What are 3 methods SQL injection can be done by?
Through user input, modifying cookies (thus poisoning the databases query), and second order sql attacks.
## How can we detect and sanitize SQL injection attacks?
Have an IDS. Sanatize your DB tables, whitelist input validation, to use prepared statements with parameterized queries, to escape all user-supplied input, to limit account privilges, and assume there will be a breach because humans do mess up sometimes. 