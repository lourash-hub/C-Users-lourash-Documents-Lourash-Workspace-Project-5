# C-Users-lourash-Documents-Lourash-Workspace-Project-5

### TASK – Implement a Client Server Architecture using MySQL Database Management System (DBMS).

1.  Create and configure two Linux-based virtual servers (EC2 instances in AWS).

  ```markdown
   Server A name - `mysql server`
   Server B name - `mysql client`
```

 run sudo apt update on both servers
```markdown
  sudo apt update
```
2.  On mysql server Linux Server install MySQL Server software.
```markdown
    sudo apt install mysql-server
```
log in to the MySQL console by typing:
```markdown
$ sudo mysql
```
This will connect to the MySQL server as the administrative database user root, which is inferred by the use of sudo when running this command. You should see output like this:

```markdown
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 11
Server version: 8.0.22-0ubuntu0.20.04.3 (Ubuntu)

Copyright (c) 2000, 2020, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql>
```

3.  On mysql client Linux Server install MySQL Client software.

```markdown
    sudo apt install mysql-client
```

