# Project Overview

In this project contains a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! 

## The tests include:

  - A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
  - A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
  - A test that ensures the menu element is hidden by default. 
  - A test that ensures the menu changes visibility when the menu icon is clicked.
  - A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
  - A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.


### Getting started

To run this app, please download this repository and open index.html

To run a local server:

	1. 
	  ```bash
	  $> cd /path/to/your-project-folder
	  $> python -m SimpleHTTPServer 8080
	  ```

	2. Open a browser and visit localhost:8080
	3. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

	  ``` bash
	  $> cd /path/to/your-project-folder
	  $> ./ngrok http 8080
	  ```

	4. Copy the public URL ngrok gives you and try running it through PageSpeed Insights!