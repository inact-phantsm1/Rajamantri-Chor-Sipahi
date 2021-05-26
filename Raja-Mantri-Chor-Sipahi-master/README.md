# Raja(Prince)-Mantri(Minister)-Chor(Thief)-Sipahi(Police)

### Live Game Link
[Current live version!](https://prashantchhabra89.github.io/Raja-Mantri-Chor-Sipahi)

### Description
* This is a classical Indian game which can be played among 4 players.
* 4 players play the game. Each player gets role of either a Prince, Minister, Thief or Police.</br>
* The player who gets the role of a prince asks "who is my minister?"</br>
* Minister reveals that "I am your minister".</br>
* Prince then says "You have to figure out who is thief and who is police".</br>
  Minister makes the guess.</br>

### Score
* Prince gets 1000 points and plice gets 500 points.</br>
* If miniter's guess was correct, miniter will get 800 points else 0.</br>
* Theif will get 800 points if minister's guess was wrong else 0.</br>
* This game can continue as long as everyone wants to play or winner can be declared when any player reaches 10000 points.</br>

### Instructions
#### How to run locally?
* Make sure git and node is installed</br>
* Clone repo using git clone</br>
* npm install</br>
* npm start</br>
* It will open browser with app running at localhost:3000/</br>
* To stop in cmd use ctrl+c</br>
#### How deploy on github?
* Edit package.json by adding a new field named homepage: "homepage": "https://github-username.github.io/projectrepo"</br>
* npm run build</br>
* npm install --save-dev gh-pages</br>
* Add a new script to the scripts field inside package.json. Let’s call the script deploy : "deploy" : "npm run build&&gh-pages -d build"</br>
* npm run deploy</br>
* Now go to repo page on github->settings</br>
* it should say "Your site is published at ...."</br>

