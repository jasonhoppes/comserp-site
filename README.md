(currently work in progress)

comserp-site 
============

COMSERP External Web Site Repository

COMSERP external web site is not specifically DDD based because it is a bit small but it borrows DDD concepts.  
There are nine projects in all:

* comserp-core
* comserp-app
* comserp-jpa
* comserp-profile-api
* comserp-profile-adapter
* comserp-site
* comserp-ui-adapter
* comserp-ui-api
* comserp-web
 
comserp-site
------------
Parent maven POM project.

comserp-core
------------
Core business objects.

comserp-jpa
-----------
The JPA implementation of the Infrastructure Layer.  Used by comserp-profile-adapter.

comserp-app
-----------
The Application Layer.  Handles logging, AOP, services that fall outside of core business services.

comserp-web
-----------
Web implementation of UI layer.

comserp-ui-api
--------------
UI API to be implemented by adapter.

comserp-ui-adapter
------------------
Implementation of comserp-ui-api.

comserp-profile-api
-------------------
API for profile infrastructure adapter.  

comserp-profile-adapter
-----------------------
Implements comsper-profile-api.
