# Data Science Lambda notes
### [Github](https://github.com/Bayaniblues/DSLambda-notes)
### [Netlify](https://ds16lambda.netlify.app/)

Here are the notes so far for DS-16. Which includes blank Assignments, Lecture notes
and my own personal answers to the assignments. Please fork or git clone to modify, and include your
own styling, and lecture notes.

Mkdocs is a common Documentation library used for building static websites fastidiously, 
and is often found in the wild. Learning how to
build Documentation is a valuable skill set that will not only help you as a data scientist, but as a 
 competent python developer as well.

## deploy

 content in requirements.txt
 
    mkdocs==1.0.4
    
    3.6
    
Create a new site and link git repository to netlify.

Specify the build command: mkdocs build.

Specify the site folder: site.

Build and site commands are in the netlify.toml file

## Requirements

    pip install wheel
    pip install mkdocs
    pip install mkdocs-jupyter
    pip install mkdocs-windmill

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.




For full documentation visit [mkdocs.org](https://www.mkdocs.org).
