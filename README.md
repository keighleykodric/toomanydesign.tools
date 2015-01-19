# Too May Design Tools

http://toomanydesigntools.divshot.io

Nowadays its a big task just doing the research to see what tools are available for web designers. This project is a collaborative collection of tools available for designers.


## Contributing
 
Anyone can add a tool using GitHub's web interface.


## How to add resources the easy way

The site uses a templating system called Jekyll that generates static HTML files, and makes it easy (hopefully) to add files that share the same template. GitHub plays nicely with Jekyll, and lets you add and edit files using the web interface. So no need to download anything, you can do it straight in repository on GitHub.

First, you'll need to decide whether your tool is bootsrap, code, graphic, in browser, interactive, mobile, mockup or wireframe based.

The only folders you'll need to worry about are:

* _toolbootstrap
* _toolcode
* _toolgraphic
* _toolinbrowser
* _toolinteractive
* _toolmobile
* _toolmockup
* _toolwireframe

If it's a interavtive tool, open up the _toolinteractive folder. In there, you'll find a README that'll explain exactly what to do to.


## How to add resources the hard way

If you want to get this repo running locally on your machine, you'll need to get set up with Jekyll.

To install Jekyll, open up your command line and type…

```
gem install jekyll
```

…then…

```
jekyll serve
```

…to get the server address where the static files are built. You only need to worry about the files in the folders prefixed by _resource, and you can follow the instructions in the README in each folder if you're not sure what to do.


## Credits
 
This project was inspired by styleguides.io
