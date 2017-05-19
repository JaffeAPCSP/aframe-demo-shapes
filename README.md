# APCSP: A-Frame Demo 1

A-Frame demonstration program with [A-Frame](https://aframe.io).

## Getting Started

Log in to your Cloud 9 account and create a new HTML 5 workspace.  Clone the [repo](git@github.com:JaffeAPCSP/aframe-demo-1.git) to initialize your workspace.

<hr>

## Start the web server

In the Cloud 9 terminal enter the comment <code>sudo service start apache2</code>

## Publishing your scene

If you don't already know, GitHub offers free and awesome publishing of static sites through __[https://pages.github.com/](GitHub Pages)__.

To publish your scene to your personal GitHub Pages:

    npm run deploy

And, it'll now be live at __http://`your_username`.github.io/__ :)

<hr>

To know which GitHub repo to deploy to, the `deploy` script first looks at the optional [`repository` key](https://docs.npmjs.com/files/package.json#repository) in the [`package.json` file](package.json) (see [npm docs](https://docs.npmjs.com/files/package.json#repository) for sample usage). If the `repository` key is missing, the script falls back to using the local git repo's remote origin URL (you can run the local command `git remote -v` to see all your remotes; also, you may refer to the [GitHub docs](https://help.github.com/articles/about-remote-repositories/) for more information).

<hr>

## Still need Help?

### Installation

First make sure you have Node installed.

On Mac OS X, it's recommended to use [Homebrew](http://brew.sh/) to install Node + [npm](https://www.npmjs.com):

    brew install node

To install the Node dependencies:

    npm install


### Local Development

To serve the site from a simple Node development server:

    npm start

Then launch the site from your favourite browser:

[__http://localhost:3000/__](http://localhost:3000/)

If you wish to serve the site from a different port:

    PORT=8000 npm start


## License

This program is free software and is distributed under an [MIT License](LICENSE).
