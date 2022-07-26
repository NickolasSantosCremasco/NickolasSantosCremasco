## Bem-vindo(a) ao perfil do Nickolas 😁

 <div>
   <a href="https://github.com/Nickolas">
   <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Nickolas&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
   <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nickolas&layout=compact&langs_count=6&theme=tokyonight"/>

</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg ">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg ">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg ">
</div>
 
 <br>
 
  ### Para acessarmeu Linkedin, Link Abaixo!
 
<div>

  <a href="https://www.linkedin.com/in/Nickolas Dos Santos Cremasco" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style= for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
 
  ![Animação de cobra](https://github.com/devemdobro/devemdobro/blob/output/github-contribution-grid-snake.svg)

</div>
nome : Gerar Dados

em :
  schedule : # executa a cada 12 horas
-cron     : " * */12 * * * "
  workflow_dispatch :

empregos :
  construir :
    name : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : Nickolas
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ secrets.GITHUB_TOKEN }}
