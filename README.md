

# Faceit Enhancer

## Project Abstract
Faceit-Enhancer is a web-extension for the Faceit platform. Faceit itself is a platform that provides support for esports leagues, tournaments, and competitive matches. 
The enhancer provides extra tools and functionality that “enhance” the player’s experience. This includes things like automation of pre-match processes and extra statistic gathering. It implements this functionality through the use of Faceit’s developer API. The main language used is Javascript along with json and HTML. 


![Use Case Image](StellaOwl_PayStation.png)

## Project Relevance
This project is relevant in terms of the following educational course goals:

-Object oriented design

-Test driven development 

-Remote procedure calls

-Debugging

-Code profiling and optimization

-Graphic User Interface

-Access to Database

-Project Management

-Version Control

-Build, test, issue tracking

-Github

-Teamwork 



## Conceptual Design
My proposed contribution will include a large addition to the current statistic gathering portion of the project. Currently the project only includes expanded ELO calculations and history. I would like to add the ability to sort statistics by various criteria such as games that include:
-A specific subset or combination of players
-A specific range of dates or past x amount of games 
-More specific match facts such as enemies flashes or utility damage
-Incorporation of these features into the UI


## Background
 

<https://github.com/faceit-enhancer/faceit-enhancer>

Clone repository and install npm dependencies:
```
yarn install
```

Build the extension into a `dist` folder, listen for file changes and automatically rebuild:
```
yarn dev
```

Load into the browser:
<table>
  <tr>
    <th>Chrome</th>
    <th>Firefox</th>
  </tr>
  <tr>
    <td width="50%">
      <ol>
        <li>Open <code>chrome://extensions</code>.</li>
        <li>Check the <i>Developer mode</i> checkbox.</li>
        <li>Click on <i>Load unpacked extension</i>.</li>
        <li>Select the <code>dist</code> folder.</li>
      </ol>
    </td>
    <td width="50%">
      <ol>
        <li>Open <code>about:debugging#addons</code>.</li>
        <li>Click on <i>Load Temporary Add-on</i>.</li>
        <li>Select the <code>dist/manifest.json</code> file.</li>
      </ol>
    </td>
  </tr>
</table>

Build the extension into a `dist` folder for publishing:
```
yarn build
```
