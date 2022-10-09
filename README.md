### Hi 👋

- 🔭 I’m currently studying on UFRGS in Brazil (computer engineering).
- 🌱 I’m currently learning HTML, CSS, JavaScript, SQL and NodeJS
- 🤔 I’m looking for help with Calculo II 😅
- 📫 How to reach me: alamirbobroski12@gmail.com

<div>
  <a href="https://github.com/Alamito">
  <img height="180em"   align="center" src="https://github-readme-stats.vercel.app/api?username=Alamito&show_icons=true&theme=react&include_all_commits=true&count_private=true"/>
  <img height="180em"  align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alamito&layout=compact&langs_count=7&theme=react" />
  
  - uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ Alamito }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
