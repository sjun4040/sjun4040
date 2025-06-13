# 안녕하세요, 박상준입니다 👋

<svg height="32" viewBox="0 0 16 16" width="32" fill="currentColor" aria-hidden="true">
  <path d="M8 0C3.58 0 0 3.58 0 8a8 8 0 005.47 7.59c.4.07.55-.17.55-.38
    0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52
    -.01-.53.63-.01 1.08.58 1.23.82.72 1.2 1.87.85 2.33.65.07-.52.28-.85.51-1.05-1.78-.2
    -3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.01.08-2.1 0 0 .67-.21 2.2.82a7.62
    7.62 0 012-.27c.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.09.16 1.9.08
    2.1.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54
    1.48 0 1.07-.01 1.93-.01 2.19 0 .21.15.46.55.38A8.001 8.001 0 008 0z"/>
</svg>


<p align="center">
  <img src="blog_banner.jpg" width="600" alt="Cover" />
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
