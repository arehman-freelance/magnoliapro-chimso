### For DB Server - Compose file
sudo docker-compose -f db-docker-compose.yml --project-name erp up -d

### For APP Server - Compose file
sudo docker-compose -f app-docker-compose.yml --project-name erp up -d

### For Creating a new site
1. update SITE_NAME variable in .env file
2. add site name in SITES variable with tilde(`) sign comma separated.
3. sudo docker-compose -f app-docker-compose.yml --project-name erp up site-creator