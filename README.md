# chalktalk_docs

###Getting Started with using sphinx

For the Chalktalk documentation, we are using the python documentation generator [sphinx](http://www.sphinx-doc.org/en/stable/) which the best option (at least that I've seen) for rapidly creating documentation that allows for easy and quick maintainence with the least amount of work involved. Also, the documentation that is generated comes with an elegant interface. 

The Sphinx project uses python, pip (a python package
manager), and encapsulates all of the packages inside of a virtual environment.

After you install [pip](https://pip.pypa.io/en/stable/installing/) and the [virtual environment software](http://docs.python-guide.org/en/latest/dev/virtualenvs/) on your
computer, you should be able to activate the virtual environment that is included in the github repository after you clone it. Virtual environments are essentially isolated storage containers for your package installations. So they allow you to install packages for a specific project that you don't actually need to use elsewhere on your computer. 

The virtual environment in this repository comes with Sphinx installed. So whenever you want to work on the documentation, simply navigated into the ```chalktalk_docs``` directory and use the command:

```source ctdocs_env/bin/activate```

which will activate the virtual environment. After this, you will be able to use sphinx. 

###Additional Info

There are many good tutorial videos on how to use the syntax of Restructured Text which is the formatting language that sphinx uses. Its similar to markdown, but its more powerful and its easy to get the gist of. Here are a few links for reference:

[Sphinx and restructured text](https://www.youtube.com/watch?v=ouHVkMo3gwE)

[Sphinx and read the docs](https://www.youtube.com/watch?v=oJsUvBQyHBs)

[restructured text reference](http://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html)


For this project, I generally wanted to follow the open-source model for documentation, a general outline of which can be found [here]( http://docs.writethedocs.org/writing/beginners-guide-to-docs/)

In case you're curious on why Sphinx is a good tool to use, you can check out [this](https://www.youtube.com/watch?v=eWNiwMwMcr4) presentation. Sphinx has already been set up for the project, but in case you want to know how it should be set up, watch [this](https://www.youtube.com/watch?v=oJsUvBQyHBs)


Once you have cloned the repository, inside of the
chalktalk_docs/build/html/ directory, you will see an index.html file which has an example of the home page for the documentation so you can see how it looks.

[Here](http://docs.python-requests.org/en/master/) is an example of a comprehensive documentation for an open source software

