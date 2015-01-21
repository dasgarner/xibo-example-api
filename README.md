# API example for Xibo
This is a very basic example of interfacing to the Xibo API.

## Configuration
An oAuth database will need to be installed prior to this functioning correctly.

1. Create a database called "oauth_consumer"
2. Run the contents of `oauth-php/library/store/mysql/mysql.sql`
3. Adjust your connection parameters in `index.php`
4. Add the Application to the CMS and copy the key/secret to `index.php`