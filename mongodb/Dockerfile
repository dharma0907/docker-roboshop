FROM mongo:7.0
COPY master-data.js /docker-entrypoint-initdb.d/
#above copy command will load all the master data into monngo after mongo got installed and started. This is a feature provided by mongo image.
# It will look for any scripts in /docker-entrypoint-initdb.d/ and execute them after mongo is up and running.