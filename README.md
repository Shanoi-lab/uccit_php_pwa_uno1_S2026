# uccit_php_pwa_uno1_S2026
PROJECT ASSESSMENT INTERNET AUTHORING II [ITT307]_WILSON_SHANOI_20233095

# 			UNIVERSITY OF THE COMMONWEALTH CARIBBEAN
		A Member of the Commonwealth & OAS Consortia of Universities
			School of Mathematics, Science & Technology
			  Department of Information Technology
				Bachelor of Science Degree
				in Information Technology


MODULE : INTERNET AUTHORING II [ITT307]
STUDENT NAME : SHANOI WILSON
STUDENT ID NUMBER : 20233095



Main Project files:
1. layouts/app.blade.php : This file contains the code for the layout of the web app, code such as FAB email button, app bar, PWA meta tags, headers and overall styling.
2. DatabaseSeeder.php : This is the source of all the data on the website such as faculty details, courses etc.
   Below are all the other files
3. home.blade.php : Main menu with 4 feature cards
4. directory/index.blade.php: Main menu with 4 feature cards
5. courses/index.blade.phh: Expandable course cards from the database
6  directory/index.blade.php: Staff directory with click to call and email
7. courses/index.blade.php: Expandable course cards from the database
8. admissions/index.blade.php: Requirements page with apply link
9. social/index.blade.php: Tabbed Facebook/Twitter/Instagram viewer
10. public/css/app.css: Full stylesheet 
11. All Controllers: DirectoryController, AdmissionsController, SocialController CourseController
12. Models: Course and StaffMember
13. Migrations: Tables for courses and staff
14. Migrations



Instructions to successfully launch the app:

1. Clone the repo: git clone https://github.com/yourusername/uccit_php_pwa_duo1_S2026.git
2. Run composer install (Install composer from :https://getcomposer.org/download/)
3. Copy .env to .env and configure database with name ucc_resources_pwa as this is the name given to the database that was create in phpmyadmin
4. Run php artisan key:generate
5. Run php artisan migrate --seed (This updates the database)
6. Run php artisan serve



Other important information for this project

Install and run Xamp Server which provides PHP8.1
Install composer from :https://getcomposer.org/download/
Location of Php files and composer - C:\xampp\php
Run the Laravel install command (Ran from termnial/cmd in the project folder)
Command: composer create-project laravel/laravel uccit_php_pwa_uno1_S2026
Install the PWA package
composer require erag/laravel-pwa
php artisan vendor:publish --provider="Erag\LaravelPwa\LaravelPwaServiceProvider"
Configure database in phpmyadmin and .env file (database name ucc_resources_pwa)
Once installed run the php artisan serve from the uccit_php_pwa_uno1_S2026 folder this launches Laravel (runs/launches the actual webpage)
http://127.0.0.1:8000/directory
How to update database after file changes, stop phpMyAdmin then run the update command after making changes to the site to save them:
php artisan db:seed

Files to edit or update

DatabaseSeeder.php  (site info)
app.blade.php (site layout)

