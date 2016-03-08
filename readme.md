# Project in progress


# PlaceMapper

![PlaceMapper demo gif]()

Placemapper is a demo file that uses Vue.js to build an interface on top of Google Maps using the Google Places library. PlaceMapper will display the google map and allow the user to search for locations by name (e.g. "Target", "Saint Louis Arch", etc), view general info on the location, save the location in a side menu, and persist those saves to a storage location (either sessionStorage or server, I haven't decided how far I want to take this demo yet).

## Mockup

The mockup I put together before building out PlaceMapper can be found [here ondraw.io](https://drive.google.com/file/d/0Bxhfk2Nciu7jZF9pTG1xTklzWVU/view?usp=sharing).

You will need a google account to view the mockup because the source file is stored in google drive.

## Prerequisites


To launch this project you'll need [Node.js](https://nodejs.org/en/download/) installed. This will install both Node and npm.

<!--
You will also need to generate your own google maps API key. Please refer to the [google maps javascript instructions for generating an API key](https://developers.google.com/maps/documentation/javascript/get-api-key). Once you have your key, open the file:

    src/app/PlaceMapper/map.vue

In this line of code replace the 'YOURGOOGLEAPIKEYHERE' with your API Key:

    GoogleMapsLoader.KEY = 'YOURGOOGLEAPIKEYHERE';

-->

## Install and Launch

To get this project up and running:

- Clone the repo to your computer, open a terminal, and `cd` into the root:

	    cd ~/Desktop
	    git clone https://github.com/chris-schmitz/PlaceMapper.git Mapper
	    cd VueToDos

- Install the project dependencies using `npm` (installed when you install node):

	    npm install

- Start the default task in `gulp` (installed when you run npm install):

    	./node_modules/.bin/gulp

- In your terminal you should see the url for the server that this project starts:

	<!-- ![mapper launched](readmeAttachments/MapperLaunched.png) -->
