How to Upload and Restore a WordPress Backup

1.Upload Backup Files

Upload your WordPress backup ZIP file to your hosting server.

Extract the contents into the public_html (or root) directory.

2.Create a Database

Open your hosting control panel (cPanel or similar).

Create a new MySQL database and user, then assign the user to the database with full permissions.

3.Configure wp-config.php

Open the wp-config.php file from your WordPress folder.

Enter your new database name, username, and password.

4.Import the Database

Go to phpMyAdmin in your hosting panel.

Select your new database and use the Import option.

Upload and import the Database.sql file from your backup.

5.Set Up .htaccess

If not already included, create or update the .htaccess file in the root directory.

Make sure it contains the standard WordPress rewrite rules.

6.Finish Up

Visit your site URL and check if everything is working.

Update permalinks from WordPress Dashboard > Settings > Permalinks to refresh the .htaccess rules.