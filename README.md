# Hi! I am [Peranut Toomnus](https://toomnusatwork.github.io/toomnus.github.io/) 🙌🏻

![Banner](./image/Banner.png)


<p>
<div id="puppycat" align="right">
    <img width=40% src="https://media.giphy.com/media/8qcYTvEiKBGCI/giphy.gif" align="left" />
</div>

[![Peranut's GitHub stats](https://github-readme-stats.vercel.app/api?username=ToomnusAtWork&show_icons=true&theme=tokyonight)](https://github.com/ToomnusAtWork/github-readme-stats)
</p>

### About
- 🏫 I study at **Silpakorn University**.
- 📝 Typo often come from me lol.
- 🧑🏽‍💻 I'm currently learning **PHP** and **Javascript**.
- 🗿 I don't use arch btw **(yet)**.
- 🙇🏻‍♂️ **(But):** I will surely fix code and organize it.


  # Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Bangkok
          plugin_achievements: yes
          plugin_achievements_display: detailed
          plugin_achievements_secrets: yes
          plugin_achievements_threshold: C
          plugin_fortune: yes
          plugin_habits: yes
          plugin_habits_charts: yes
          plugin_habits_charts_type: classic
          plugin_habits_days: 14
          plugin_habits_from: 200
          plugin_habits_languages_limit: 8
          plugin_habits_languages_threshold: 0%



### Language:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-FFE467?style=for-the-badge&logo=python&logoColor=black)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)




