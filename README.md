# NgArch
NgArch is an Angular application architecture tool, analyzing Angular application and visually displaying the modules, components, services and data models in multiple diagrams. This repo is the web app(client) of the NgArch

## Description
NgArch is an Angular application architecture tool, analyzing the static structure of the Angular application and visually displaying the modules, components, services and data models in multiple diagrams.

NgArch(Angular application architecture tool) contains two parts.

<ul>
  <li>NgArch Server, is a node and express application. It analyzes the Typescript source code and extracts the elements of the Angular application.</li>
  <li>NgArch, is an Angular 6 application. It visually shows the elements and the structure of the application in multiple diagrams.</li>
</ul>

<p>ngArch application modules overview</p>
<img src="https://github.com/samcodex/ngarch-app/blob/master/assets/ngArch_Modules_Overview.png" width="500px"/>
<br>

<p>ngArch PonentDiagramModule elements and relationship diagram</p>
<img src="https://github.com/samcodex/ngarch-app/blob/master/assets/ngArch_PonentDiagramModule.png" width="500px"/>


## Usage
Install ngarch-app which contains the server(ngarch-server) and the client(ngarch).

`git clone https://github.com/samcodex/ngarch-app.git`

then<br>
`npm install`

### Launch the server
`npm start`
<br>The server uses port 3000

### Access the client
In browser, enter 'http://localhost:3000'

### Install ngarch-server manually
`npm install ngarch-server`

### Install ngarch manually
`npm install ngarch`
