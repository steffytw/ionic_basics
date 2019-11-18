### ionic_basics

## Installing Ionic

CONTENTS
Install the Ionic CLI
Start an App
Run the App
Ionic apps are created and developed primarily through the Ionic command-line utility. The Ionic CLI is the preferred method of installation, as it offers a wide range of dev tools and help options along the way. It is also the main tool through which to run the app and connect it to other services, such as Ionic Appflow.

## install-the-ionic-cli

Before proceeding, make sure the latest version of Node.js and npm are installed. See Environment Setup for details. Install the Ionic CLI globally with npm:

* for linux:
$ sudo npm install -g ionic
* for windows:
$ npm install -g ionic

## Start an App
Create an Ionic app using one of the pre-made app templates, or a blank one to start fresh. The three most common starters are the blank starter, tabs starter, and sidemenu starter. Get started with the ionic start command:
* $ ionic start myApp tabs

## Run the App
The majority of Ionic app development can be spent right in the browser using the ionic serve command:

* $ cd myApp
* $ ionic serve


There are a number of other ways to run an app, it's recommended to start with this workflow. To develop and test apps on devices and emulators, see the Running an App Guide.

