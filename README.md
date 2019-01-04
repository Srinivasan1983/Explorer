# `Blockchain-Explorer` — the seed for AngularJS apps

This project is an application skeleton for a typical [AngularJS][angularjs] web app. You can use it
to quickly bootstrap your angular webapp projects and dev environment for these projects.

The seed contains a sample AngularJS application and is preconfigured to install the Angular
framework and a bunch of development and testing tools for instant web development gratification.

The Blockchain-Explorer app doesn't do much, just shows how to wire two controllers and views together.

## Getting Started

To get you started you can simply clone the `Blockchain-Explorer` repository and install the dependencies:

### Prerequisites

You need git to clone the `Blockchain-Explorer` repository. You can get git from [here][git].

We also use a number of Node.js tools to initialize and test `Blockchain-Explorer`. You must have Node.jsand its package manager (npm) installed. You can get them from [here][node].

### Clone `Blockchain-Explorer`

Clone the `Blockchain-Explorer` repository using git:

```
git clone https://github.com/Srinivasan1983/Blockchain-Explorer.git
cd angular-seed
```

If you just want to start a new project without the `Blockchain-Explorer` commit history then you can do:

```
git clone --depth=1 git clone https://github.com/Srinivasan1983/Blockchain-Explorer.git <your-project-name>
```

The `depth=1` tells git to only pull down one commit worth of historical data.

### Install Dependencies

We have two kinds of dependencies in this project: tools and Angular framework code. The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [Node package manager][npm].
* We get the Angular code via `bower`, a [client-side code package manager][bower].
* In order to run the end-to-end tests, you will also need to have the
  [Java Development Kit (JDK)][jdk] installed on your machine. Check out the section on
  [end-to-end testing](#e2e-testing) for more info.

We have preconfigured `npm` to automatically run `bower` so we can simply do:

```
npm install
```

Behind the scenes this will also call `bower install`. After that, you should find out that you have
two new folders in your project.

* `app/bower_components` - contains the Angular framework files

### Run the Application

We have preconfigured the project with a simple development web server. The simplest way to start
this server is:

```
npm start
```

Now browse to the app at [`localhost:8000/index.html`][local-app-url].

