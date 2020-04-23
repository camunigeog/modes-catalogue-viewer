MODES catalogue viewer
======================

This is a PHP application to show a MODES catalogue online.

This consumes data from an API: https://github.com/camunigeog/modes-catalogue-api


Screenshot
----------

![Screenshot](screenshot.png)


Usage
-----

1. Clone the repository.
2. Download the library dependencies and ensure they are in your PHP include_path.
3. Download and install the famfamfam icon set in /images/icons/
4. Add the Apache directives in httpd.conf (and restart the webserver) as per the example given in .httpd.conf.extract.txt; the example assumes mod_macro but this can be easily removed.
5. Create a copy of the index.html.template file as index.html, and fill in the parameters.
6. Access the page in a browser at a URL which is served by the webserver.


Dependencies
------------

* [application.php application support library](https://download.geog.cam.ac.uk/projects/application/)
* [database.php database wrapper library](https://download.geog.cam.ac.uk/projects/database/)
* [frontControllerApplication.php front controller application implementation library](https://download.geog.cam.ac.uk/projects/frontcontrollerapplication/)
* [multisearch.php Multisearch library](https://download.geog.cam.ac.uk/projects/multisearch/)
* [pagination.php Pagination library](https://download.geog.cam.ac.uk/projects/pagination/)
* [pureContent.php general environment library](https://download.geog.cam.ac.uk/projects/purecontent/)
* [ultimateForm.php form library](https://download.geog.cam.ac.uk/projects/ultimateform/)
* [xml.php XML support library](https://download.geog.cam.ac.uk/projects/xml/)
* [FamFamFam Silk Icons set](http://www.famfamfam.com/lab/icons/silk/)


Author
------

Martin Lucas-Smith, Scott Polar Research Institute, Department of Geography, University of Cambridge, 2012-20.


License
-------

GPL2.

