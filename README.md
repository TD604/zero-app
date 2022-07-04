# Itwin + ONEclick LCA
 
1. install [VS Code](https://code.visualstudio.com/download)
2. insate [NodeJS](https://nodejs.org/en/) (Version 16.15.1)
3. Create an [Imodel](https://developer.bentley.com/my-imodels). Please take a note of the Imodel & ITwin ID 
4. Create a [new APP](https://developer.bentley.com/my-apps/). Please take a note of the Client ID 
5. Clone or Download this Repository. 
6. Open the Repository in VS Code. Once open in the [`Root`](#code) find a file called [`.env`](#code). in there on line 2 after [`IMJS_AUTH_CLIENT_CLIENT_ID=`](#code) Paste your Client ID from Step 4. Then on line 9 & 10 inside the [`""`](#code) paste you Itwin and Imodel IDs in the corresponding lines. 
7. In the Terminal run [`npm install`](#code)
8. Save it 
9. In the Terminal Run [`npm start`](#code). Please note this step might take several minutes, but it should open your default web browser on [`http://localhost:3000`](#code) if it doesnt paste this into you web browser. 
