## Package structure
### Downloading the Package
The package that is downloaded consist of the following files & folders. 

1. config

2. public

3. databases

4. resouces

5. srs

6. test

7. .gitignnore

8. .travis.yml

9. composer.json

10. licence.md

11. phpnit.xml

12. readme.md

### Package Structure
The structure allows the user to understand the package against small and large applications. The user can assemble the package as he/she would desire. 

##src Directory

The ***src*** directory consist of a variety of files & directories. It contains the core code of the applications, the directory will be explored in depth later. 

The ***config*** directory, consist of all of the application's configuration files.

The ***database*** directory contains your database migration and seeds that has been implemented. You may also use this directory to hold an SQLite database.

The ***public*** directory contains the front controller and your assets (images, JavaScript, CSS, etc.).

The ***resources*** directory contains your views, raw assets (LESS, SASS, CoffeeScript), and localization files.

The ***tests*** directory contains your automated tests. An example PHPUnit is provided out of the box.
### SRC Directory
The "meat" of your application lives in the ***src*** directory. By default, this directory is namespaced under ***Src*** and is autoloaded by Composer using the PSR-4 autoloading standard.

The ***Policies*** directory contains the authorization policy classes for your application. Policies are used to determine if a user can perform a given action against a resource. For more information, check out the authorization documentation.
