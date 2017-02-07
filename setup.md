## Installation & Getting Set Up

### 1. INSTALLATION

If you do not have PostgreSQL installed:

1. Download it: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
2. Install the most recent version for your OS (I did 9.6.1 and Mac OS X). You do not need Stackbuilder 3.1.1.
3. Create a password for the superuser (has all permissions) = `postgres`. Note that Port = 5432 (default)

If you already have PostgreSQL installed, get PgAdminIII:

1. Download it: http://www.pgadmin.org/download/
2. On the left hand side under `pgAdmin 4`, select your OS & install the most recent stable version by clicking on the appropriate link
3. Under `Files`, select the middle option, then "Agree"


#### 2. INITIALIZATION (in class)

1. Open pgAdmin 4
2. Add a server:
  * Object >> Create >> Server...
  * Fill in the following info & click Save
  General Tab

   **Name:** `<your-name>-ga`  

   **Server group:** Servers  
  Connection Tab

   **Host:** given in class  
   
   **Port:** 5432  

   **Maintenance DB:** given in class  
   
   **Username:** given in class  
   
   **Password:** given in class  
3. Click on the databases with X’s to connect to them.
4. Click on a database under <your-name>-ga, then select Tools >> Query Tool.