# 2FA using Laravel and Twilio

# Prepared by dreamsoft4u's developer. Website - https://www.dreamsoft4u.com

Description:

	Adding Two-Factor Authentication (2FA) to your web application increases the security of your user's. This is a 2fa package via sms for Laravel at login. We use Twilio api for this.
	
Requirements: Laravel(5.3),php (> 5.6.4),Twilio account settings
	
Installation Instructions : We are assuming that composer is already installed
	
	1) From your projects root folder in terminal run:
	
		git clone https://github.com/ds4you/laravel-2fa laravel-2fa	
		
	2) cd laravel-2fa
	
	3) Run composer update command: composer update
	
	Optionally Update your .env file and associated settings (see Environment File section)

	4) Run the migration to add the table: 
	
		php artisan migrate
	
	5) finally run command: php artisan serve
	
Note: Make sure you have provide your Twilio settings in .env file like TWILIO_NUMBER,TWILIO_ACCOUNT_SID,TWILIO_AUTH_TOKEN.

Make sure your apps email is configured in the .env file.