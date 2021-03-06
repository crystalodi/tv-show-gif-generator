# TV Show GIF Generator

Tv Show GIF generator is an app that uses the giphy api to display gifs captured from tv dramas and animated cartoons.

## Live Version

Go [here](https://crystalodi.github.io/tv-show-gif-generator/) to view the app. 

## About the Application

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

Install the following programs if they aren't on your local machine.

GIT - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

### Installing

Open your terminal and clone [this](https://github.com/crystalodi/tv-show-gif-generator.git) repository to your computer. 

```
git clone https://github.com/crystalodi/tv-show-gif-generator.git

```

Navigate to the `/tv-show-gif-generator` directory with your terminal

```
cd tv-show-gif-generator
```

Open file explorer from the `/tv-show-gif-generator` directory

```
explorer .
```

Open the `index.html` file by double clicking on it. The app will open in a web browser and should look like this:

<img src="https://raw.githubusercontent.com/crystalodi/tv-show-gif-generator/master/assets/images/home.png">

### Folder Structure

After following the instructions in the installation section, the contents of the `/tv-show-gif-generator`will look like this

```
│   index.html
│   README.md
│
└───assets
    ├───css
    │       reset.css
    │       style.css
    │
    ├───images
    │       add_gif_search_term_1.png
    │       add_gif_search_term_2.png
    │       ezgif-4-e75bd4e6bd.gif
    │       home.png
    │       retrieve_gifs.jpg
    │
    └───javascript
            app.js
```

* `index.html` contains the ui for the application. This includes the form used to add buttons used to search for gifs.
* `assets/css/reset.css` removes any default styling applied by web browsers
* `assets/css/style.css` Contains styling for add tv show form, tv show search buttons, and gif search results.
* `assets/javascript/app.js` Each time a tv show search button is clicked, an ajax GET request is sent using the url `https://api.giphy.com/v1/gifs/search` to retrieve 10 gifs that match the tv show text on the button. The code also allows users to add more search terms and display them as buttons.

## How to Use

### Adding a gif search term

In the form below the page header, fill out the tv show field

<img src="https://raw.githubusercontent.com/crystalodi/tv-show-gif-generator/master/assets/images/add_gif_search_term_1.png">

Press the Add TV Show Button

<img src="https://raw.githubusercontent.com/crystalodi/tv-show-gif-generator/master/assets/images/add_gif_search_term_2.png">

The tv show you entered will appear as a button underneath the add tv show form.


### Retrieving gifs

Press any button located underneath the add tv show form. If there are any gifs associated with the tv show you entered they will appear like this:

<img src="https://raw.githubusercontent.com/crystalodi/tv-show-gif-generator/master/assets/images/retrieve_gifs.jpg">


### Stopping and Starting a gif

All gifs retrieved will be loaded as still images. To make the gif move, click on the gif. To make it stop moving, click on the gif again.

<img src="https://raw.githubusercontent.com/crystalodi/tv-show-gif-generator/master/assets/images/ezgif-4-e75bd4e6bd.gif">


## Built With

* HTML
* jQuery
* JavaScript
* CSS
* Giphy Developer's API

## Authors

* **Crystal Odi** - *Initial work* - [crystalodi](https://github.com/crystalodi)


## Acknowledgments

* jQuery Documentation
* Mozilla Developer's Network
* Giphy Developer's API Documentation

