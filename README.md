# Holy Grail Layout with scrollable main content using Angular Flex-layout in Angular

This is a bare bone Holy Grail Layout with scrollable main content using CSS Flexbox for Angular website.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.1

**Table of contents:**

1. [Prerequisites and Installation](#prerequisites-and-installation)
2. [Quick Start](#quick-start)
3. [Build Tasks and Commands](#build-tasks-and-commands)
4. [Changelog](#changelog)
5. [Issue Tracker](#issue-tracker)

## Prerequisites and Installation

Library | Version | Notes
:-------|:--------:|-------
[Node](https://nodejs.org/) | 10.15.0 | Recommended NodeJS version
[NPM](https://nodejs.org/) |6.4.1 | Recommended NPM version
[Angular](https://angular.io/) | ~7.2.x | JavaScript-based open-source front-end SPA framework
[Angular CLI](https://github.com/angular/angular-cli) | 7.3.1 | Set of development tools for Angular
[Angular Flex-layout](https://github.com/angular/flex-layout) | 7.0.0-beta.23 | Provides a sophisticated layout API using Flexbox CSS + mediaQuery for Angular applications


## Quick Start

To launch the demo application, you can try below steps yourself on your computer, or launch the application on StackBlitz, by [clicking here](https://stackblitz.com/github/kumaran-is/angular-flexlayout-scroll).

1. Clone repository and checkout the `master` branch

    ```bash
    git clone https://github.com/kumaran-is/angular-flexlayout-scroll.git
    cd angular-flexlayout-scroll
    git checkout master
    ```

1. Install NPM dependencies

    ```bash
    npm install
    ```

1. Run linting

    ```bash
    npm run lint
    ```

1. Start application in development mode

    ```bash
    ng serve -o
    ```

1. Application opens in browser [http://localhost:4200](http://localhost:4200)

## Build Tasks and Commands

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Profiling the Build

The more the application grows, the slower the build gets. Angular CLI version 7.0.0 introduced a --profile flag that outputs the build events and lets you profile them in chrome://tracing. You can use this feature as follows:

1. Build your project with --profile flag on (ng build --prod --profile)
2. Angular CLI will produce a file called chrome-profiler-events.json
3. Open [chrome://tracing](chrome://tracing/) and click on “Load” in the top left corner
4. Select chrome-profiler-events.json
5. For more detail refer the [link](https://blog.mgechev.com/2019/02/06/5-angular-cli-features/)

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## GitHub Working Agreement

We will be working off the master branch. When working on a new feature or fixing a bug,
create a new branch out of the master branch and follow the below naming convention for the branch name.
Remember that GitHub and MacOS are case-sensitive. Our standard will be for all branch names and file
names to be all lower-case.

 - **For features**: feature/{feature-name}
    - Example:
                
            git checkout -b feature/auth_flow  # using feature name
 - **For bugs**: fix/{bug-name}
    
    - Example:
             git checkout -b fix/login_fails  # using  bug name


Before submitting a Pull Request for the  repository make sure to check the following:

  - There should be zero jshint and jscs errors.
  - Make sure the application runs without any errors.
  - Code coverage does not drop under 80%
  - All possible test cases are added, both happy path and failure path like exceptional or error conditions.  
  - Pull Request would be reviewed by me.
  - As a reviewers i`ll verify:
    - `npm run lint` should pass
    - Verify PR code changes works as expected by running it on local machine
    - No errors in the browser console
    - Review the code changes to makesure it is written as per Angular coding standard recommended in [angular.io](https://angular.io/) for syntax, conventions, and structuring Angular application.
    - Review if any changes needed to Readme prescription or any project documents
    - Review the changelog and application version
    - Delete the branch after merging back with the master branch.

## Changelog

* [Changelog](./CHANGELOG.md).

## Issue Tracker

* [Issue tracker](https://github.com/kumaran-is/angular-flexlayout-scroll/issues?state=open)
