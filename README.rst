=======
SSC
=======
SSC is a specific client/server application.
Purpose - remote execution of specific commands.


Quick start
-----------

1. Add "ssc" to your INSTALLED_APPS setting like this::

       INSTALLED_APPS = (
          ...
          'ssc',
       )

2. Include the polls URLconf in your project urls.py like this::

    url(r'^ssc', include('ssc.urls')),

3. Create or change conf.ini file in root of your django project to add next::

    [server]
    server_ip = 
    server_port = 

    [ssc]
    url = 
    login = 
    pass = 




