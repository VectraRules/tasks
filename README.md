README

My Tasks

My Tasks is a low resource app providing secure login for users which includes and admin role to view other user registered on the system.
At this atage admin account must be set manually in the database. Instructions on request

Instructions for use

	Windows:
		Setup a WAMP or XAMP server installation. Browse to https://sourceforge.net/projects/wampserver/ for WAMP installation.
		Alternatively browse for XAMP or AMPPS server implementations
		

	Paste all file in the public_html folder of the respective host or linux host. Refer to host or software vendor for troubleshooting to get host setup correctly.
	The source code does not require a SSL certificate but will run securely under it.
	
	MYSQL DB
	
	Setup MYSQL and configure a Database and access permissions/users to the database, alternatively you can use local DB with root access.
	Create a Data an run the provided sql with the database namespace to create the required tables and init data
	
	Browse the site via your choice of Browser. Design using Chrome. If Firefox browser gives permision errors or fails to display some components disabled advanced secure page loads under the shield icon next to the secure website indicator at the top URL display
	
	Edit the db.php file to match your database access criteria.
	If auto detection fails you can manually specify the host server address variable on pages ( CNJS variable with PHP code ), this will ensure requestes are directed to the correct network location.
	
	Note: If image uploads fail check if PHP Image plugins are enabled in php.ini, upload size limits might also need to be adjusted and memory allocations as uploads of images that need reencoding due to oriantation
	
Dev T