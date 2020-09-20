<h4>Olá! Hola! Hello!</h4>
 <h2>I'm Filipe!</h2>

<p> 🌍 Global citizen living in Brazil!</p>
<p> 🌱 Agroforestry gardener in my spare time...</p>
<p> 👨‍💻 Full-stack developer:</p>
<p>  HTML 5 | CSS 3 | JavaScript ES6 | TypeScript | ReactJS | React-Native | NodeJS | Redux | Hooks | Saga | RTL | Jest | MySQL | MongoDB
</p>
<p> 🚀 I’m currently working at <a
    href="ttps://www.dtidigital.com.br/" 
    alt="dti digital"
  >dti digital
  </a>  helping other organizations 
accelerating their digital transformation!</p>

<h4>You can find me on:</h4>

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ficast/)](https://www.linkedin.com/in/ficast/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:filipeyoga@gmail.com)](mailto:filipeyoga@gmail.com)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<!--END_SECTION:waka-->