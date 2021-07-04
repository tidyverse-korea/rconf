# `useR! 2021 Korea`

디지털 불평등(Digital Divide)과 디지털 경제전환(Digital Transformation)의 가속화가 코로나19로 보다 명확해진 시대다. 이러한 변화의 중심에 빅데이터, 기계학습, 인공지능 등 데이터 기반 기술이 자리 잡고 있으며 또 집중 관심을 받고 있다. 데이터 시대를 맞아 R은 통계에 기반한 프로그래밍 언어임에도 불구하고 다른 범용 프로그래밍 언어와 같은 큰 인기를 얻고 있다.

금번 useR! 2021 Korea 컨퍼런스는 기존 통계학 관련 학계, 산업계, 정부 뿐 아니라 데이터 과학계까지 망라해 데이터를 통해 문제를 해결하고 가치를 창출하고자 하는 모든 분이 모여 경험과 지식을 공유하고 네트워킹을 할 수 있는 자리로 기획하였다. 데이터 활용의 폭과 깊이를 더한 이 자리에서 데이터를 통해 새로운 세상을 열어가고 함께 하실 수 있는 많은 분을 만나는 소중한 시간이 되었으면 하는 바람이다.

# [useR! 2021 Korea 웹사이트 구축 Hands-on](https://festa.io/events/1653)

`useR! 2021 Korea` R 컨퍼런스는 순수 100% R 언어를 사용해서 웹사이트 개발을 비롯한 모든 과정을 진행하고 있습니다.
관련하여 기본 기술이 최근 소개되고 발전된 부분이 있어 `distill` 팩키지를 사용해서 과학기술 웹사이트 및 블로그 제작 Hands-on 실습시간을 가졌습니다.
기본적으로 <use-r.kr> 제작에 사용된 동일한 기술이라 아래 내용을 바탕으로 작업하시면 자체 웹사이트 구축과 함께 `useR! 2021 Korea` R 컨퍼런스 웹사이트 제작에도 참여하실 수 있습니다.

## `distill` 로컬 웹사이트 제작

[Distill for R Markdown : Creating a Website -Share a set of Distill articles as a website](https://rstudio.github.io/distill/website.html) 블로그 게시글을 참고했습니다.

1. RStudio 오픈
1. `install.packages("distill")`
1. File &rarr; New Project &rarr; Distill Website
1. build website - control + shift + B
1. 헬로월드 찍기

## Git 환경설치

1. git 버전관리
    - git bash 윈도우 설치: https://git-scm.com/downloads
1. git 작업흐름
    - `git add -A`
    - `git commit -m "commit message"`

## Git 환경설치

1. 웹사이트 <https://app.netlify.com/drop>
    - `docs` 디렉토리 전체를 Drag and Drop 
1. Hands-On 참여자 `distill` Website 헬로월드
   1. https://flamboyant-montalcini-497600.netlify.app/
   2. https://dreamy-kalam-eaad20.netlify.app
   3. https://boring-bassi-8b26d1.netlify.app/
   4. ...

## 로컬 Git 저장소(디렉토리)와 GitHub 저장소 연결

> git add -A
> git commit -m"initial commit"
> git status
> git remote add origin https://github.com/statkclee/my_website.git
> git remote -v
> git branch --set-upstream-to=origin/master master
> git pull origin master --allow-unrelated-histories
> git push origin master

# 도메인 연결

GitHub 저장소를 가비아 등 도메인 제공업체에서 제공하는 서비스와 연결하여 나만의 도메인명을 갖는 웹사이트를 제작하는 방식은 다음 R 슬라이스쇼를 참고바랍니다.

- [GITHUB에 도메인 연결해서 고정 웹페이지 서비스하기](https://aidenhong.com/presentations/setup-github-for-making-a-static-website/setup-github-for-making-a-static-website.html#/)





