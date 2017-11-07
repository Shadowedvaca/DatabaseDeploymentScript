# DatabaseDeploymentScript
Powershell script to deploy a database with a dev and prod instance

Requires .sql files in the directory with the script or in sub-folders ( scan is recursive ).

If need to specify actions between DBs in stored procedures ( etc ), put [ProdDB]. or [DevDB]. to indicate a reference to the other database.  References for the database will be removed and references to the other DB will be inserted using the variables in the script.
