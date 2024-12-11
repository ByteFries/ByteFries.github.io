---
title : GitHub 블로그 생성
date : 2024-12-10 16:00:00
author: <ByteFries>
description : "GitHub 블로그 생성"
categories : [GitBlog]
tage : [GitBlog]
comments : true
toc: true
---

## <span style = "font-weight: 800;">GitHub 블로그란?</span>
GitHub가 제공하는 GitHub Pages라는 정적 웹 호스팅 서비스를 이용해 만든 블로그를 의미한다. GitHub의 리포지토리에 파일을 업로드하는 기능을 블로그 제작 형태로 활용하는 방식이다.

기존의 Naver, Tistory와 같은 블로그 서비스와는 다른 스타일을 가진 블로그를 살펴보면, 주소 맨 뒤가 .github.io인 블로그를 본 적 있을 텐데, 바로 이런 블로그들이 GitHub 블로그다.

## <span style = "font-weight: 800;">기존 블로그와 다른 점은?</span>
GitHub 블로그는 기존 블로그 서비스처럼 정형화된 틀에 얽매이지 않는다. 따라서 테마, 레이아웃, 폰트 등 모든 디자인 요소를 사용자가 원하는 대로 커스터마이징 가능하다는 장점이 있다.

"정형화된 틀이 싫다면 직접 블로그를 만들면 되자 않을까?" 라고 생각할 수도 있지만, 직접 블로그를 구축하려면 정말 많은 것들을 배워야 한다. GitHub 블로그는 이런 과정을 간소화한다.

1. 새로운 GitHub 저장소를 생성하고,
2. 배포 브랜치에서 GitHub Pages를 활성화하면
3. 블로그가 생성된다.

또한, 직접 블로그를 구축하면 서버 호스팅 비용이 발생하지만, GitHub Pages는 별도의 서버 호스팅 비용이 들지 않는다는 장점이 있다.

### <span style = "font-weight: 800;">GitHub 블로그의 추가 장점</span>
GitHub와 연동되기 때문에 개발자들이 기술 블로그를 작성하기에 적합한 환경을 제공한다. 이로 인해 GitHub 블로그는 개발자 커뮤니티에서 특히 많이 활용된다고 한다.

## <span style = "font-weight: 800;">GitHub 블로그 생성 방법은?</span>
나는 직접 디자인하는 과정을 생략하고 jekyll 테마를 이용하여 빠르게 블로그를 구축하였다.

우선 GitHub 계정을 생성한다.
그 다음 해당 페이지에서 마음에 드는 테마를 선택하자.
<div style="display: flex; flex-direction: column; align-items: center;">
  <span>테마 선택 사이트 : <a href="https://github.com/topics/jekyll-theme">https://github.com/topics/jekyll-theme</a></span>
  <img src="/assets/image/themeRinkImg.png" alt="이미지 설명" style="margin-left: 10px;" />
</div>


![ThemeImg1](/assets/image/ThemeImg1.png)
_나는 이 테마를 선택했다._

보통 다른 사람들의 배포 리포지트리를 사용하고 싶으면 README를 찾아보면 된다.

![ThemeImg2](/assets/image/ThemeImg2.png)
_아래로 스크롤하면 README를 찾을 수 있다_

LiveDemo를 클릭하면 테마 설명 페이지로 이동한다.
![ThemeDesImg](/assets/image/ThemeDesImg.png)
_테마 사용 설명 페이지_

이제 Getting Started 페이지에서 사용법을 알아보자.

## <span style = "font-weight: 800;">테마 사용법</span>

설명에는 사이트 생성 두 가지 방법을 제시한다.
1. 업데이트가 간편하고, 불필요한 파일을 제외한 초심자용
2. jekyll과 테마에 익숙하고, 테마의 기능, UI 등을 자유롭게 수정가능한 숙련자용

나는 초심자니 1번을 선택했다.

1. starter 클릭
![ThemeDesImg](/assets/image/create1Img.png){: .shadow }
2. Use this template 버튼을 누르고 Create a new repositiory 선택
![ThemeDesImg](/assets/image/create2Img.png)
![ThemeDesImg](/assets/image/create3Img.png)

3. 리포지트리의 이름을 자신의 GitHub username.github.io로 설정
![ThemeDesImg](/assets/image/create4Img.png)

이러면 정말 간단하게 블로그를 생성할 수 있다.
