 https://simoncastano.com/

Diseñador UI y programador fullstack 
me gusta probar nuevas tecnologías 
<br/>
Figma, AdobeXD, Html, Css, JavaScript, PHP, MySQL, Less, Sass, ReactJS, VueJS, Ionic, React Native, Laravel, Flutter, Strapi, NodeJS, Expressm, Ejs, Python, 

<!---
scr-simon/scr-simon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<h3 align="center">

   ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=scr-simon&show_icons=true&title_color=008b8b&icon_color=008b8b&text_color=008b8b&bg_color=151515)

</h3>

<h2> My GitHub Stats </h2>
 <h3 align="center">

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=scr-simon&show_icons=true&theme=blue-green&icon_color=fff&title_color=ffffff&border_color=fff&bg_color=DEG,4D00AB,2EC7D6&text_color=ffffff)
</h3>

<div align="center">
 <img  src="https://res.cloudinary.com/torre-technologies-co/image/upload/c_scale,fl_progressive.progressive:steep,q_auto:low,w_360/v1648842673/origin/bio/cover-pictures/SimonArbey_Casta%C3%B1o_Rios1648842671655_sq7fhz.jpg">
</div>

![Contribution](https://activity-graph.herokuapp.com/graph?username=scr-simon&theme=react-dark&hide_border=true&area=true)

![Snake animation](https://github.com/scr-simon/github-readme/blob/output/github-contribution-snake.svg)
name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: madushadhanushka
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
