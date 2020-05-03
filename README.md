# Pqtato's Guides
This project is the source code of [guides.pqtato.pw](https://guides.pqtato.pw) which has some guides made by me. The website is built using [mkdocs](https://www.mkdocs.org) with the [material theme](https://squidfunk.github.io/mkdocs-material/). If you would like to contribute please create a pull request.

## Running locally
These are the instructions for contributing. Please don't touch .travis.yml. That file allows the project to be built with Travis CI. The theme and stylesheets folder are for dark theme. The docs folder contains the Markdown files which are built into HTML with mkdocs. The .idea folder is for [PhpStorm](https://www.jetbrains.com/phpstorm/).

1. Install Python 3 from [python.org](https://www.python.org) (this project is built with 3.8.2)
2. Clone this repository on your computer
3. In terminal or command prompt please run the following command which will install mkdocs with the material theme.
```
pip3 install mkdocs-material
```

4. Check if it installed correctly by typing
```
mkdocs --version
```

5. You can run mkdocs locally by typing
```
mkdocs serve
```
