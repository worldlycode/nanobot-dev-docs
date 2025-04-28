# Configuring pgAdmin for PostgreSQL

**Date:** April 27, 2025  
**Author:** sam-i-am

<pre style="color: #3f51b5; font-size: 1.1rem;"><code>"Hello World! 🌐"</code></pre>

pgAdmin is an Open Source administration and development platform for PostgreSQL -- Which claims to be the most advanced Open Source database in the world.  

I don't know about that claim, but PostgreSQL is pretty great, it does have plugins for embedding vectors and vector indexing.  So I am currently a fan :)

This is how I installed pgAdmin on Windows

1. Downloaded and installed pgAdmin from their [website](https://www.pgadmin.org/)
2. run pgadmin4
3. right click on "servers" and click "register" -> "server"
4. enter the following information:
    - General:
        - Name: {name of the instance of the database}
    - Connection:
        - Host: {host of the database} -- if local it will be 127.0.0.1
        - Port: {port of the database} -- default is 5432, but this is often already used, so could create a new port number
        - Maintenance database: {name of the database} -- if local it will be postgres
        - Username: {username of the database} -- if local it will be postgres
        - Password: {password of the database} -- if local it will be postgres
    - Save

At this point the connect will either be made or if there is an error you should follow the errors to fix the issue.  


