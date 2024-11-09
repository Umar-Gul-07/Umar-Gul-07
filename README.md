<!--
- 👋 Hi, I’m @Umar-Gul-07
- 👀 I’m a Professional Full Stack MERN Developer.
- 📫 How to reach me: umargul692002@gmail.com
-->

<h1>
👋 Hello World! <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="24px">
</h1>

I'm Umar Gul, a Professional Full Stack MERN Developer. 🎨

I specialize in building modern, responsive, and scalable web applications that prioritize user experience, performance, and maintainability. My approach combines efficient logic with creative problem-solving to deliver high-quality, customized solutions that meet client objectives and foster business success. 🚀

<br/>

<img src="https://raw.githubusercontent.com/Umar-Gul-07/Umar-Gul-07/main/dist/github-contribution-grid-snake.svg" alt="Snake animation" />

## 🛠 Skills

![HTML](https://img.shields.io/static/v1?message=HTML&logo=html5&label=&color=E34F26&logoColor=white&labelColor=&style=for-the-badge)
![CSS](https://img.shields.io/static/v1?message=CSS&logo=css3&label=&color=1572B6&logoColor=white&labelColor=&style=for-the-badge)
![JavaScript](https://img.shields.io/static/v1?message=JavaScript&logo=javascript&label=&color=F7DF1E&logoColor=black&labelColor=&style=for-the-badge)
![ES6](https://img.shields.io/static/v1?message=ES6&logo=javascript&label=&color=F7DF1E&logoColor=black&labelColor=&style=for-the-badge)
![React](https://img.shields.io/static/v1?message=React&logo=react&label=&color=20232A&logoColor=61DAFB&labelColor=&style=for-the-badge)
![Next.js](https://img.shields.io/static/v1?message=Next.js&logo=next.js&label=&color=000000&logoColor=white&labelColor=&style=for-the-badge)
![Node.js](https://img.shields.io/static/v1?message=Node.js&logo=node.js&label=&color=339933&logoColor=white&labelColor=&style=for-the-badge)
![Express.js](https://img.shields.io/static/v1?message=Express.js&logo=express&label=&color=000000&logoColor=white&labelColor=&style=for-the-badge)
![MongoDB](https://img.shields.io/static/v1?message=MongoDB&logo=mongodb&label=&color=47A248&logoColor=white&labelColor=&style=for-the-badge)
![Git](https://img.shields.io/static/v1?message=Git&logo=git&label=&color=E44C30&logoColor=white&labelColor=&style=for-the-badge)
![GitHub](https://img.shields.io/static/v1?message=GitHub&logo=github&label=&color=181717&logoColor=white&labelColor=&style=for-the-badge)
![Bootstrap](https://img.shields.io/static/v1?message=Bootstrap&logo=bootstrap&label=&color=563D7C&logoColor=white&labelColor=&style=for-the-badge)
![Figma](https://img.shields.io/static/v1?message=Figma&logo=figma&label=&color=F24E1E&logoColor=white&labelColor=&style=for-the-badge)

## Additional Tools & Technologies

![Python](https://img.shields.io/static/v1?message=Python&logo=python&label=&color=3776AB&logoColor=white&labelColor=&style=for-the-badge)
![Java](https://img.shields.io/static/v1?message=Java&logo=java&label=&color=007396&logoColor=white&labelColor=&style=for-the-badge)
![Docker](https://img.shields.io/static/v1?message=Docker&logo=docker&label=&color=2496ED&logoColor=white&labelColor=&style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<br/>

## 🤝🏻 Let's Connect!

If you're as passionate about web development or if you're looking for a Professional Full Stack MERN Developer, I'd love to connect with you. Feel free to reach out! 🌐

---

### Notes

- Make sure the file path for the snake animation (`dist/github-contribution-grid-snake.svg`) matches the GitHub Actions setup.
- Verify that GitHub Actions are enabled for your repository.

### GitHub Actions Setup

1. **Create the GitHub Actions Workflow**: Add a workflow in `.github/workflows/snake.yml`.
2. **Add this configuration**:

    ```yaml
    name: Generate Snake Animation

    on:
      push:
        branches:
          - main
      schedule:
        - cron: "0 0 * * *" # Runs daily

    jobs:
      generate:
        runs-on: ubuntu-latest
        steps:
          - name: Checkout Repository
            uses: actions/checkout@v2

          - name: Generate Snake Animation
            uses: Platane/snk@v2
            with:
              github_user_name: Umar-Gul-07
              svg_out_path: dist/github-contribution-grid-snake.svg

          - name: Commit and Push Snake Animation
            run: |
              git config --global user.name "github-actions[bot]"
              git config --global user.email "github-actions[bot]@users.noreply.github.com"
              git add dist/github-contribution-grid-snake.svg
              git commit -m "Updated snake animation"
              git push
    ```

This setup should generate and push the updated snake animation to your repository automatically.
