# Minimal boostrap

This is a minimal jekyll project in which bootstrap is in place so you can start playing with it.

## Steps

Create a blank jekyll project 

    jekyll new jekyll-bootstrap-minimal --blank

Make sure the `assets/css` and `assets/js` folders are present

Create folder `_sass`

Download [bootstrap](https://getbootstrap.com)

Copy bootstrap scss into the _sass folder:

    $ cp -r ~/Downloads/bootstrap-4.2.1/scss/* _sass/bootstrap/

Create a `main.scss` file in assets/css which refers to the `_sass` folder

    ---
    ---
    /* modify Bootstrap variables here */

    @import 'bootstrap/bootstrap';

    /* add additional CSS rules below */

Copy the jquery and bootstrap js into the `assets/js` folder

    wget https://code.jquery.com/jquery-3.3.1.min.js -P js
    cp ~/Downloads/bootstrap-4.2.1/dist/js/* js/