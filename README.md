# node-github-hook-deploy

A demo to use github hook by NodeJS

## Install dependency package

	$ npm i
	

## Progress

1. Replace your repository url in **app.js**
* Select "Settings" on your repository page
* Select "Service Hooks"
* Add hook url **http://yourserver.com:3131/hook** to your WebHook URLs
* Modify **hook.sh** to execute anything you want to do after new commit comming.
* Run app on your server

	```
	$ node app.js &
	```
