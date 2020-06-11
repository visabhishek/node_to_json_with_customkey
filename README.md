CONTENTS OF THIS FILE
---------------------

* Introduction
* Requirements
* Installation
* Configuration
* References
* Total time

Introduction
------------

* The Site API Key module adds a new textfield called "Site API Key"
in "Site Information" form which can be found at the path
"/admin/config/system/site-information".
* This module also provides a URL that responds with a JSON value of a
given node of "page" content type, If provided the correct "Site API Key" is
entered in the URL.

Example URL : http://example.com/page_json/site_api_key/node_id

Requirements
------------

This module requires the following module:
* System (Provided by Drupal core)

Installation
------------

* Login as an Administrator.
* Go to /admin/modules.
* Find the module called "Node To JSON with customkey" and install this.


Configuration
-------------

* Configure your "Site API Key" in the Site Information form located at
"/admin/config/system/site-information".

References
----------

* https://drupal.stackexchange.com/questions/245990/add-config-forms-to-existing-admin-page
* https://www.drupal.org/docs/8/api/routing-system/using-parameters-in-routes
* https://www.codimth.com/blog/web/drupal/custom-controller-json-response-drupal-8
* 

Total time
----------

I have spent around 6 hours for this.
