# mysqldump

> Backups MySQL databases.

- Create a backup, user will be prompted for a password:

`mysqldump -u {{user}} --password --default-character-set=utf8mb4 {{database_name}} {{table_names}} > {{filename.sql}}`

- Restore a backup, user will be prompted for a password:

`mysql -u {{user}} --password {{database_name}} < {{filename.sql}}`
