<h1 align="left" style="color:#1e90ff;">Hello, I'm Ekko</h1>

> <span style="color:#444;">A developer passionate about games and immersive tech.</span>

### <span style="color:#1e90ff;">Tech Stack</span>

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal-313131?style=for-the-badge&logo=unrealengine&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![VR/AR/XR](https://img.shields.io/badge/VR%2FAR%2FXR-0a84ff?style=for-the-badge&logo=apachespark&logoColor=white)

---

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ Ekko-001 }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Ekko-001/Ekko-001/blob/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/Ekko-001/Ekko-001/blob/output/github-snake.svg" />
  <img alt="github-snake" src="https://github.com/Ekko-001/Ekko-001/blob/output/github-snake.svg" />
</picture>
