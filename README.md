# split-lecture

**split-lecture** is a simple tool to show YouTube videos alongside Jupyter Notebooks and keep them synchronised. It has been built to support blended learning for a Python programming course delivered at the University of Manchester. 

[**View an example lecture**](https://personalpages.manchester.ac.uk/staff/stefan.guettel/split-lecture/)

![Screenshot](screenshot.png)

# Setup

**split-lecture** is written in JavaScript and very easy to set up. Simply follow the below steps:

1. On your webserver, create a new folder.
2. In this folder, place your Jupyter Notebook file as an HTML export. (In Jupter, view the notebook and go to File -> Download as -> html to produce this HTML file.)
3. In that same folder, place the files `index.html` and `custom.css` from the repository.
4. Open `index.html` and edit the highlighted variables.

That's it. I hope you find **split-lecture** useful for your teaching. Feel free to modify it to your needs. 

Any comments and feedback are appreciated, either by raising them as *issues* or dropping me an email: stefan.guettel@manchester.ac.uk
