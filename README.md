cache-swagger
-------------
This is a small RESTful service to automatically generate the Swagger-UI JSON required to show your Cache/Ensemble RESTful services in the Swagger-UI interface (see [http://swagger.io](http://swagger.io))

You will need to do the following steps;

-  Install the Cache class, or add the code to your existing Cache RESTful service class (i.e. extends %CSP.REST)
-  Set-up (if its a new RESTful service) the Application information in the Cache System Management Portal.
-  Install the swagger-ui onto your web server.
-  Browse to the swagger-ui and enter the URL for your swagger-ui json service.

See the example screenshots of setups in the project images directory.
