This is the root folder. Folder structure as follows:

\BulletinBoard_Django			:	root folder
	__init__.py
	settings.py					: 	system-wide settings
	urls.py						:	system-wide url routing
	wsgi.py						:	Web Server Gateway Interface
	README.txt
\bulletin 						:	folder for application/package: bulletin
	__init__.py
	admin.py					:	admin panel
	views.py					:	views (controllers in Rails language)
	models.py					:	DB model
	urls.py						:	url routing for bulletin
	tests.py					:	website testers
	utils.py					:	helper functions (view this as some customized liraries)
	\static						:	folder for static resources
		\bulletin
			\css				:	stylesheets all stay here
			\images				:	image assets stay here
			\js					:	javascripts stay here
	\templates
		\bulletin 				:	all templates (views in Rails language) stay here
			listing.html		:	bulletin listing page
			preferences.html	:	user preferences page
			profile.html		:	user profile page
			login.html			:	user login page
	\migrations					:	DB migration files
"manage.py"						:	main Django script engine
"README.txt"					:	dude you are reading it now