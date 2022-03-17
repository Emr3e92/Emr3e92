### Hi there 👋


### &#11088; GitHub Stats ~ 
![GHstats](https://github-readme-stats.vercel.app/api?username=Emr3e92&show_icons=true)


name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning  : <img alt="AWS" width="25px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" style="padding-right:11px;" />  <img alt="AWS" width="25px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" style="padding-right:11px;" />  <img alt="AWS" width="25px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" style="padding-right:11px;" />  <img alt="AWS" width="25px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="padding-right:11px;" />
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



### My Daily Routine :

```mermaid
  graph TD;
      Code-->Eat;
      Eat-->Sleep;
      Sleep-->Code;
```
