






php

1. codignator installation steps
->download file
->extract file
->rename file name

/// purpose for remove in index.php in url
->replace for htdocs file for application folder remove to replace for application out side 
->code remove replace in .htdocs code
  -->code for 
 RewriteEngine on
RewriteCond $1 !^(index\.php|resources|robots\.txt)
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ index.php/$1 [L,QSA] 

/////

->config folder and config file replace in $config['index_page'] ="index.php"; replace for empty string $config['index_page'] ="";
->connect databse in database file 
->autoload file libirs file add database array

