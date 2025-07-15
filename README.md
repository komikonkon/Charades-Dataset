# Charades-Dataset

## 1. How to use
1. Download and install MariaDB (latest version).
2. Execute sql file "CreateDBwithData_Charades.sql".
3. (Install database GUI client tool such as HeidiSQL at your convinience.)
4. Execute update statement below.<br>
    `UPDATE {your db name} SET used_count=0;`
5. Download repositorie "Charades".
6. Modify "settings.json" and apply your information; such as database name.
7. Launch Charades locally.
8. Access `http://127.0.0.1:8080/` .
9. Done.