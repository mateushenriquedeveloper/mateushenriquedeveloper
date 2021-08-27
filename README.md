![](https://github-readme-stats.vercel.app/api?username=mateushenriquefonsecaxavierdasilva&show_icons=true&theme=dracula&include_all_commits=true&count_private=true)
### Olá, eu sou Mateus Henrique. Bem-vindo(a) ao meu Git Hub.  
- [ Youtube ](https://www.youtube.com/channel/UClAIWVdFVyuP6H3DwXmFy_g).
- [ Instagram ](https://www.instagram.com/mateus.henrique.10/).
- [ Facebook ](https://www.facebook.com/Mateus.henrique.010/).

nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * * / 12 * * * "
  workflow_dispatch :

empregos :
  construir :
    nome : Trabalhos para atualizar dados
    roda em : ubuntu-mais recente
    passos :
      # Animação de cobra
      - usa : Platane / snk @ master
        id : snake-gif
        com :
          github_user_name : mateushenriquefonsecaxavierdasilva 
          svg_out_path : dist / github-Contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : output
          build_dir : dist
        env :
          GITHUB_TOKEN : $ {{secrets.GITHUB_TOKEN}}   


