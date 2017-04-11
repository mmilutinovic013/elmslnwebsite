# elmsln

### Setup

##### Prerequisites

Install [polymer-cli](https://github.com/Polymer/polymer-cli):
(Need at least npm v0.3.0)

    npm install -g polymer-cli


##### Setup
    # Using CLI
    mkdir elmsln
    cd elmsln
    polymer init elmsln
    
    # Or cloning direct from GitHub
    git clone https://github.com/Polymer/elmsln.git
    cd elmsln
    bower install

### Start the development server

    polymer serve

### Run web-component-tester tests

    polymer test

### Build

    polymer build

### Test the build

This command serves the minified version of the app in an unbundled state, as it would be served by a push-compatible server:

    polymer serve build/unbundled
    
This command serves the minified version of the app generated using fragment bundling:

    polymer serve build/bundled
