### Hi there , I am Fred a software engineer and a tech lover 👋

- 🔭 I’m currently working on React.js projects
- 🌱 I’m currently learning Node.js & MongoDb
- 👯 I’m looking to collaborate on Enterprise applications
- 🤔 I’m looking for help with Python
- 💬 Ask me about Code
- ⚡ Fun fact: I am good at making new friends
 ### Technologies I use
- React.js
- Python
- JavaScript



name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: pemtajo/badge-readme@master
          ACCLAIM_USER: <username_acclaim> # optional, but default will use the same from github
