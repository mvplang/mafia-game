Server-Side Components :

	views – jade templates that compile to HTML
		login.jade
		home.jade
		signup.jade
	modules – helper classes that interact with the database and dispatch emails
		account-manager.js
		email-dispatcher.js


Client-Side Components :

	views – these setup our form controllers & modal windows
		login.js
		home.js
		signup.js
	controllers – handle user interactions
		loginController.js
		homeController.js
		signupController.js
	form-validators – validate forms and display errors
		loginValidator.js
		accountValidator.js
		resetValidator.js
		emailValidator.js