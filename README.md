# SET IT UP
- create file structure in terminal

`cd ~/sei/sei_322/fundamentals/css`

`mkdir contact-card && cd contact-card`

`mkdir styles && touch index.html styles/main.css`


- make your local project a git project

`cd contact-card`

`git init`

`touch README.md`

`git add -A`

`git commit -m "init commit"`

`git branch -M main`
*I choose to rename from master --> main because I believe it's important to use decolonizing language


- create a new repository in your github enterprise account and copy the url it creates


- connect your project to your repo

`git remote add origin https://github.com/aprilkrgonzales/css-contact-card.git`

`git remote -v`

`git push -u origin main`

<br>

# STUB IT UP
- open project in vscode

`code .`


- create html boiler plate

<<b>!</b> + <b>tab</b>>

- change the title to something more descriptive

- link css to html

`<link rel="stylesheet" href="styles/main.css>`

- create a div to hold your card

`<div class="card"></div>`

- create elements for the text

`<p>ONLINE</p>`

`<h1>John Shoshone</h1>`

`<p>Psychic Healer</p>`

`<h2>5 mins free</h2>`

`<p>then $5.99/min</p>`

- create sanity check in css file

*{
    box-sizing: border-box;
}
body{ 
    margin: 0px;
    background-color: fuchsia;
}

- open the html file in a web browser

<<b>option</b> + <b>b</b>>

- rejoice that they're connected and you're ready to code!

<br>

# Code It Up

- change background color of the card 

body {
    margin: 0px;
    background-color: fuchsia;
    display: grid;
    place-content: center;
}
.card {
    background-color: white;
    height: 400px;
    width: 250px;
    display: grid;
    place-items:center;
    margin:100px;
}

- add background colors to different sections of the card

<div class="card-details">
    <span>ONLINE</span>
    <h1>John Shoshone</h1>
</div>
<p>Psychic Healer</p>
<div class="card-details">
    <h2>5 mins free</h2>
    <span>then $5.99/min</span>
</div>

.card-details {
    background-color: greenyellow;
}