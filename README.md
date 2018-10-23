# PHP Admin Template  


Admin template structured with PHP

- PHP
- html
- css
- jquery
- htaccess rewrite rules 

#### For use


changes in /global.php
```sh
define( 'SYSTEM_NAME', 'base_project' ); // change to your project key
define( 'DISPLAY_NAME', 'Base Project' ); // change to your project name
define( 'SYSTEM_ROOT', '/base_project' ); // change to your project folder name

```
same as changes in /.htaccess
```sh

'base_project' change to your project folder name

ErrorDocument 400 /base_project/public/error.php?key=400 
ErrorDocument 401 /base_project/public/error.php?key=401
ErrorDocument 403 /base_project/public/error.php?key=403 
ErrorDocument 404 /base_project/public/error.php?key=404
ErrorDocument 500 /base_project/public/error.php?key=500
ErrorDocument 502 /base_project/public/error.php?key=502
ErrorDocument 504 /base_project/public/error.php?key=504
```

