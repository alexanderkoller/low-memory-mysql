# Low memory MySQL

MySQL is great, but with its default settings, it uses a lot of memory. This can be a problem when deploying it in a low-memory environment, such as a virtual server or a Docker container server.

This project defines a Dockerfile which replaces the config file of the default MySQL Docker image with one which uses less memory. These modifications come from the following sources:

 * http://www.tocker.ca/2014/03/10/configuring-mysql-to-use-minimal-memory.html
 * https://mariadb.com/de/node/579
 
