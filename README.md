# Bash One-Liners
A collection of useful bash one-liners (yet another one of these repos).

## Contents 
- [MySQL] (#mysql)

## MySQL

[[back to top](#contents)]

Check size of mysql db: 

    mysql> SELECT table_schema "crowdrise", sum( data_length + index_length ) / 1024 / 1024 "Data Base Size in GB" FROM information_schema.TABLES GROUP BY table_schema ;
