---
layout: post
title:  "Start Github Page With Jekyll"
categories: software
---
## Blog를 만들기 위해 github page와 jekyll 사용하기
Blog를 만드는 이유에 대해서는 [about](/about/)을 참조하세요.

### github page
github page는 github repository를 website로 사용할 수 있는 기능입니다.

구현을 제외한 일(hosting, HTTPS, 서버관리 등)을 github에서 처리해 주기 때문에, 사용자는 웹사이트 구현에 집중할 수 있습니다.

[tutorial page](https://pages.github.com/)는 github page 소개와 user site repository 생성부터 hosting 까지의 절차를 안내합니다.

절차를 마치면 github에 user site source를 가진 repository와 접속 가능한 user site를 얻습니다.

    예제) qkuhnx
    user site repository : https://github.com/qkuhnx/qkuhnx.github.io/ 
    user site : https://qkuhnx.github.io/about/

#### github document
github page는 github에서 관리하기 때문에, github 지원 기능들에 익숙하면 편리합니다

[github document](https://help.github.com/)는 github에 대한 모든 것들을 수록한 문서입니다.

page 관련한 내용만 보고 싶다면, 페이지 내 찾기(ctrl + F)를 사용해 'pages'를 검색하세요

- [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/) <= site 운영에 필요한 기본적인 지식들을 소개합니다.
- [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/) <= 다른 모든 기능을 소개합니다.

github site의 제약조건을 더 알고 싶다면 [이곳](https://help.github.com/articles/github-terms-of-service/)을 읽으세요

### jekyll
github page는 일반적인 웹 서버처럼 html 파일을 사용해 서비스가 가능합니다.

하지만 사용자가 html을 사용해 모든 글을 작성하는 것은 매우 힘듭니다.

따라서 github 에서는 기본적인 site generator로 [jekyll](https://jekyllrb.com/)을 사용합니다.([한국어 번역](https://jekyllrb-ko.github.io/))

site generator는 사용자의 파일들을 바탕으로 간편하게 글을 생성해 줍니다.

    다른 site generator를 사용할 수도 있지만 jekyll은 theme, markdown, template 등을 지원하면서도 간단한 글 생성이 가능합니다.
  
#### site generator

### set up local development 
jekyll을 이용한 page는 github에 업로드하지 않고도 볼 수 있습니다.

[여기](https://help.github.com/categories/customizing-github-pages/)에서 어떻게 local 환경에 jekyll page 개발 환경을 구성할 수 있는지 알아보세요.

### addtional
사용하는데 편리한 추가적인 기능입니다.

#### disqus
[disqus](https://disqus.com/)는 comment 지원

### TODO
