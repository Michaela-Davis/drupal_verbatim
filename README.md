# _Verbatim Bookstore_
<!-- #### [Click for live site](.com/) <br> -->
#### By _**Michaela Davis**_   &nbsp; 4.21.17


## Description

This website allows visitors to "Verbatim Bookstore" to view "Locations" and "About" pages. Authenticated "Reviewers" can add, edit, and delete book reviews; the 3 most recent reviews appear in the sidebar for all users. It also utilizes the Strongarm module to create a feature called "Site Configuration" that tracks the site name, slogan, theme, and front page.


## Prerequisites

You will need the following things properly installed on your computer:

* [Git](https://git-scm.com/) v2
* [MAMP](https://www.mamp.info/en/downloads/) v4 (for Mac Users)
<br>  OR <br>
* [WAMP](http://www.wampserver.com/en/#download-wrapper) v3 (for Windows Users)


## Installation

```bash
git clone https://github.com/Michaela-Davis/drupal_verbatim.git
cd drupal_verbatim
```

* MAMP users: Click on Preferences in your MAMP window and set your document root to the top level of your repository.

* WAMP users: Make sure to clone your repository into your websites directory as we set up during the server installation lesson. Then make sure the server is connected and load your site on http://localhost:8888/.


## Import the Database

* Open phpMyAdmin and click on the "Import" tab.
  * Leave all the default settings and make sure the character set is "utf-8".
  * Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file included in the sites/db-backup folder. It's okay to leave it zipped.
  * Click the "Go" button on the bottom left.

* Create the Database User
  * After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".
  * Use the username `bookstore` and password `bookstore`

* After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.


## Running / Development

* Visit Verbatim Bookstore at [http://localhost:8888](http://localhost:8888).
* Use the username `bookstore` and password `bookstore` to login to the Verbatim Bookstore site


### License

*MIT license*


Copyright (c) 2017 Michaela Davis All Rights Reserved.
