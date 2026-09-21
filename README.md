<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Hi,%20I'm%20Ikhwan&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38"/>

### **🎨 Graphic Designer • 💻 Digital Creative • 🌐 Web Enthusiast**
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Graphic+Designer;Digital+Creative;Web+Enthusiast;Visual+Content+Creator;Always+Learning+Something+New" />
 
<br>

<!-- Bio Section -->
<p align="justify">
Saya seorang Graphic Designer dan Digital Creative yang berfokus pada pembuatan konten visual menarik, desain antarmuka web, dan pengembangan kreativitas digital. Memiliki passion yang kuat dalam mempelajari teknologi web terbaru, visual branding, dan selalu terbuka untuk mengeksplorasi ide-ide inovatif.
</p>

<br>

<!-- Social & Contact Badges -->
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://portofolio-i.my.canva.site/portofolio-ikhwan-nur)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ikhwan-nur-arifiyanto-7295953ab?utm_source=share_via&utm_content=profile&utm_medium=member_android)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/ikhwannur__?stkn=dmRhd2M3a3h2YnY4)

</div>

---

### 🔗 Core Tech Stacks
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind" />
  </a>
</p>

### 🎨 Design & Editing Tools
<p align="left">
<img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white" alt="Canva" />

  <img src="https://img.shields.io/badge/Adobe%20Lightroom-31A8FF?style=for-the-badge&logo=adobelightroom&logoColor=white" alt="Lightroom" />

  <img src="https://img.shields.io/badge/CorelDRAW-%2300A150.svg?style=for-the-badge&logo=coreldraw&logoColor=white" alt="CorelDRAW" />


</p>

### 🔗 Other Tech Stacks
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=bootstrap,nodejs,express,php,laravel,python,mysql" />
  </a>
</p>

### 🔗 Tools
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,figma,ai,ps,github,git,notion" />
  </a>
</p>


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

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
