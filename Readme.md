# 안녕하세요, 박상준입니다 👋

[![GitHub 주소입니다]([https://github-readme-stats.vercel.app/api?username=your-username](https://github.com/sjun4040))]

<p align="center">
  <img src="profile-readme.png" width="600" alt="Cover" />
</p>

🔭 지금은 공부중(파이썬, 자바 스크립트, Html, sql, ADSP 등)  
📫 문의: a79681108@email.com  

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=ffffff)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=ffffff)

<h2 style="color:#333333;">🚀 Skills</h2>

name: Update visitor count
on: [push, schedule]
jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Update visitor widget
        run: |
          # 스크립트로 visitor.svg 업데이트
      - uses: EndBug/add-and-commit@v9
        with:
          author_name: github-actions
          author_email: actions@github.com
          message: "Update visitor count"
