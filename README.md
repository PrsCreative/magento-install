# magento
Magento Community Edition 1.9.2.4 Install

# Build required install
1. Apache
2. PHP 
3. MySQL (root, P@ssw0rd)

# Step of install magento & database
1. Clone repository to root apache [ubuntu : var/www/html/]
2. Create database name "magento" on MySQL Server
4. Open phpmyadmin on browser and import sql script "magento.sql" (you see root directory)
3. Open browser run and copy url here : http://127.0.0.1/magento  
4. Working it.


# Connection setting (Change)
1. Please change config.xml file to new connection : app/etc/local.xml
2. Default connection
	- Username : root
	- Password : P@ssw0rd
	- Database name : magento


# User of admin panel
- Username : admin
- Password : password1

# Default config of admin panel
1. Disable cach mamagement
2. Allow symlinks
3. Enable log system
3. Use Web Server Rewrites
4. Reindexs
5. Remove inbox

# Modman clone install default repository from github
1. modman init
2. EcomDev_PHPUnit (phpunit custom for magento)
3. SMTP Pro

# EcomDev config for use phpunit test
1. app/etc/local.xml.phpunit (dbname,base_url, allow_same_db)
2. phpunit.xml.dist  (Uncomment to enable coverage-html )

# Thank you very much..
