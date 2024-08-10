<!--![burak-kumas's Top Languages](https://github-readme-streak-stats.herokuapp.com/?user=burak-kumas&theme=gotham&hide_border=true )-->

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
<div align="center">
  <a href="https://github.com/burak-kumas">
 <img height=150px src="https://github-readme-stats.vercel.app/api?username=burak-kumas&theme=gotham&show_icons=true&hide_border=true&count_private=true"/>
<img height=150px src="https://github-readme-stats.vercel.app/api/top-langs/?username=burak-kumas&theme=gotham&show_icons=true&hide_border=true&layout=compact"/>
</div>
  
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Node" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg"
  <img align="center" alt="React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Tailwind" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg">
  
##
  
<div>
  <a href="https://instagram.com/burak_kumas" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:brkkumas@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/burak-kumas" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>

##
<div>
  name: 🏆 Achievements
category: github
description: |
  This plugin displays several highlights about what an account has achieved on GitHub.
examples:
  +compact display: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.achievements.compact.svg
  detailed display: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.achievements.svg
index: 19
supports:
  - user
  - organization
scopes:
  - public_access
inputs:

  plugin_achievements:
    description: |
      Enable achievements plugin
    type: boolean
    default: no
    extras:
      - metrics.run.puppeteer.scrapping

  plugin_achievements_threshold:
    description: |
      Rank threshold filter

      Use `X` to display achievements not yet unlocked
    type: string
    default: C
    values:
      - S
      - A
      - B
      - C
      - X

  plugin_achievements_secrets:
    description: |
      Secrets achievements
    type: boolean
    default: yes

  plugin_achievements_display:
    description: |
      Display style

      - `detailed`: display icon, name, description and ranking
      - `compact`: display icon, name and value
    type: string
    default: detailed
    values:
      - detailed
      - compact

  plugin_achievements_limit:
    description: |
      Display limit
    type: number
    default: 0
    min: 0
    zero: disable

  plugin_achievements_ignored:
    description: |
      Ignored achievements

      Use achievements names without their rank adjective (i.e. without "great", "super" or "master")
    type: array
    format: comma-separated
    default: ""
    example: octonaut, automator, explorer

  plugin_achievements_only:
    description: |
      Showcased achievements

      Use achievements names without their rank adjective (i.e. without "great", "super" or "master")

      This option is equivalent to [`plugin_achievements_ignored`](/source/plugins/achievements/README.md#plugin_achievements_ignored) with all existing achievements except the ones listed in this option
    type: array
    format: comma-separated
    default: ""
    example: octonaut, automator, explorer
</div>
