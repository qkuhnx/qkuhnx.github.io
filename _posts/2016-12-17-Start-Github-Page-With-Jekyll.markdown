---
layout: post
title:  "Start Github Page With Jekyll"
categories: software
---
## Blog를 만들기 위해 github page와 jekyll 사용하기
Blog를 만드는 이유에 대해서는 [about](/about/)을 참조하세요.

- 웹 프로그래밍 지식 필요

### github page
github page는 github repository를 website로 사용할 수 있는 기능입니다.

구현을 제외한 일(hosting, HTTPS, 서버관리 등)을 github에서 처리해 주기 때문에, 사용자는 웹사이트 구현에 집중할 수 있습니다.

[tutorial page](https://pages.github.com/)는 github page 소개와 user site repository 생성부터 hosting 까지의 절차를 안내합니다.

절차를 마치면 github에 user site source를 가진 repository와 접속 가능한 user site를 얻습니다.

### site generator
모든 웹 사이트들은 html 파일로 구성됩니다. 따라서 웹 사이트에서 서비스 하고 싶은 내용이 있다면, 그 내용을 html 파일을 만들어 업로드하면 됩니다.

html 파일을 쉽게 만들어 주는 도구로 (static) site generator가 있습니다. site generator는 형식에 따라 문서를 입력받고, 적절한 html 파일로 변환해주는 도구입니다. 사용자는 html 파일을 직접 만들지 않아도 됩니다. 

#### jekyll
jekyll은 open source 기반 static site generator 중 가장 [인기가](https://www.staticgen.com/) 많은 application 입니다.

github page는 기본적으로 [jekyll](https://jekyllrb.com/)을 지원합니다. 다른 static site generator를 사용할 수도 있지만, jekyll을 사용하면 github 문서나 Bundler 등 여러 도움을 받을 수 있습니다.

[이 페이지](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-2-install-jekyll-using-bundler)는 jekyll 기반 github page의 local 개발 환경을 설정하는  안내합니다.


---

### github document
github page는 github에서 관리하기 때문에, github 지원 기능들에 익숙하면 편리합니다

[github document](https://help.github.com/)는 github에 대한 모든 것들을 수록한 문서입니다.

page 관련한 내용만 보고 싶다면, 페이지 내 찾기(ctrl + F)를 사용해 'pages'를 검색하세요

- [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/) <= site 운영에 필요한 기본적인 지식들을 소개합니다.
- [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/) <= 다른 모든 기능을 소개합니다.

github site의 제약조건을 더 알고 싶다면 [이곳](https://help.github.com/articles/github-terms-of-service/)을 읽으세요

### addtional
사용하는데 편리한 추가적인 기능입니다.

#### disqus
[disqus](https://disqus.com/)는 comment 지원

### TODO
