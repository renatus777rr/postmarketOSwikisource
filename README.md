** Postmarketos wiki source code remake **
Important notice: This is a remade version of the PostmarketOS wiki source code. It is not the official repository. You must set up the environment properly yourself. Some components are missing, such as images, so you will need to provide your own. This guide explains how to prepare the environment, install dependencies, and run the wiki locally.

Warnings:

    This source is incomplete; you must configure and install required components manually.

    Do not host this on a public server. Run it only on localhost for testing.

    Some pages and images are placeholders. You may remove or replace them.

    The iPhone 4s appearing on the main page is not factual content.

Step 1. Install prerequisites Install the following dependencies on your system:

    PHP (version 8.1 or newer recommended)

    MySQL or MariaDB

    Composer (PHP dependency manager)

    ImageMagick (for image processing in MediaWiki)

    Git (for cloning and managing the source repository) Note: WSL (Windows Subsystem for Linux) is not supported.

Step 2. Download MediaWiki and source Download the latest MediaWiki release (for example 1.41.1). Extract it and move it to your webserver root, for example /var/www/mediawiki. Clone or fork the PostmarketOS wiki source repository with Git and copy the provided extensions folder and images folder into the MediaWiki root. Copy 
