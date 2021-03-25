- create file structure in terminal
`cd ~/sei/sei_322/fundamentals/css`
`mkdir contact-card && cd contact-card`
`mkdir styles && touch index.html styles/main.css`

- make your local project a git project
`cd ~sei/sei_322/fundamentals/css/contact-card`
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