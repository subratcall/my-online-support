# My Online Support
## A sample support ticket management application developed with Oracle Jet
### Based on Practical Oracle JET: Developing Enterprise Applications in JavaScript book by Daniel Curtis, updated for version 7.1.0 of Oracle Jet

#### Prerequisites
1. Node.js

   To install Node.js, please see instructions on https://nodejs.org/en/download/

2. OracleJet

   To install Oracle Jet, please see instructions on https://www.oracle.com/webfolder/technetwork/jet/globalGetStarted.html

To compile the UI application for the desired platform run the following commands:

    cd UI
    ojet build [platform]

The only supported platform is **web**

To run the application, first start the mockserver:

    cd API
    mockserver -p 8080 -m ./mocks

If mockserver is not installed on your system, please install it with:

    npm -g install mockserver

Then start the UI:

    ojet serve [platform] --theme=mosTheme

The only supported platform is **web**
