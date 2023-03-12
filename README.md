# Typer NEXRAD


A Python CLI Application for NEXRAD

Created five user functionalities in Typer 

1. createuser - Creates user with their username, password, and their tiers and uploads them to database
  `typer_t7 createuser <username> <passwod>`

2. download - Download files from users public s3 bucket by specifying the file name
   `typer_t7 download <username> <password> <bucketname> <filename>`

3. fetch - Lists all files in the public S3 bucket 
   `typer_t7 fetch <username> <password> <bucketname>`

4. fetchnexrad - Generates NOAA public S3 link and Users S3 link based on the parameters year, day, hour, station, and filename
   `typer_app fetchnexrad <username> <password>`

5. fetchnexrad_filename - Generates link based on NOAA Nexrad S3 bucket based on the filename given by the user
   `typer_app  fetchnexrad_filename <username> <password>`

