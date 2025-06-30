# **Website Redesign Project:** 
### 인프런 클론 코딩   

<br/>
  
**박서영, Park seo young**  

<br/>

#### **Schedule** 
> **2025.05.13. - 2025.05.30. (5h - 6h, weekdays only)**

</br>


> 1. Development: 2025.05.13. - 2025.05.30.


<br/>
<br/>
<br/>

## 목차
1. [프로젝트 개요](#1-프로젝트-개요)   
2. [파일 구성](#2-파일-구성)   
3. [주요 기능 소개](#3-주요-기능-소개)    
4. [작업 환경](#4-작업-환경)   
5. [관련 링크](#5-관련-링크)   

</br>
</br>
</br>

---

## 1. 프로젝트 개요

### 1.1. 작업 배경
이 프로젝트는 인프런(Inflearn) 공식 웹사이트를 클래스101(Class101)의 디자인 시스템과 사용자 경험 요소를 참고하여 리디자인한 웹 리뉴얼 작업입니다. 기존 인프런 사이트의 콘텐츠와 핵심 구조는 유지하되, 전반적인 레이아웃과 시각적 구성, 기능적 측면에서 더욱 현대적이고 사용자 친화적인 방향으로 개선하였습니다. 특히 클래스101의 직관적이고 감각적인 디자인 요소를 적극 반영하여, 사용자에게 보다 몰입감 있는 학습 환경을 제공할 수 있도록 기획하였습니다.

이번 리디자인에서는 기존 사이트에서 부족했던 인터랙티브 요소를 강화하기 위해 다양한 기능들을 새롭게 도입하였습니다. 대표적으로 스와이프(슬라이드) 기능을 활용하여 강의 콘텐츠와 추천 항목을 직관적으로 탐색할 수 있도록 구성하였고, 수강 마감 등의 정보를 시각적으로 강조할 수 있도록 D-day 카운트다운 기능도 추가하였습니다. 또한 UI 구성 요소 전반을 재정비하여 사용자 흐름을 명확히 하고, 모바일 환경에서도 최적의 사용성을 보장하는 반응형 웹 디자인을 적용하였습니다. 이로써 본 프로젝트는 단순한 시각적 리디자인을 넘어, 실제 사용자 경험을 개선하고 사이트 전반의 활용성과 완성도를 높이는 데 초점을 맞춘 작업이었습니다.

</br>

이 프로젝트의 목적은 다음과 같다.   
1. 클래스101의 디자인 요소를 참고하여 사용자 중심의 깔끔하고 직관적인 인터페이스를 구현한다.
2. 스와이프, D-day 카운트다운 등 인터랙티브 기능을 적용하여 사용자 참여도를 높인다.
3. 다양한 디바이스 환경에서도 일관된 사용 경험을 제공하기 위해 반응형 웹 디자인을 적용한다.

</br>
</br>
</br>

### 1.2. 키워드

1. **현대적이고 직관적인 UI/UX 구현**   
  1.1. 사이트 전반의 가독성과 접근성을 향상

</br>

2. **사용자 경험(UX) 향상을 위한 기능 도입**   
  2.1. 학습 콘텐츠 탐색을 더욱 직관적이고 효율적

</br>

3. **모바일 친화적인 반응형 웹 환경 구축**   
  3.1. 모바일 사용자의 접근성과 편의성을 강화

   </br>
   </br>
   </br>
   
---

## 2. 파일 구성
```
🌱 Inflearn  
 ┣ 📂 images   
 ┣ 📂 include     
 ┣ 📂 html
 ┣ 📂 scss    
 ┣ 📂 css 
 ┗ 📂 script    
   📄 index.html    
```

   </br>
   </br>
   </br>

---

## 3. 주요 기능 소개

### 3.1. 메인 페이지
#### 3.1.1. 메인비주얼
![메인비주얼](https://github.com/user-attachments/assets/ee30e655-9eb0-435a-a688-ea0a0e0c5e19)
1. 상단에 검색창과 전체메뉴를 통해 사용자의 편리성을 확장하였습니다.
2. 메인페이지는 스와이퍼 형태로 두어 3개의 배너를 확인하실 수 있습니다.
3. 아이콘 바로가기를 두어 사용자가 자주 사용하고 이용하기 편하도록 배치해두었습니다.
4. 하단 우측의 팝업창은 클릭시에 닫히는 형태를 보실 수 있습니다.

</br>
</br>
</br>

#### 3.1.2. 인사이트 카드&스와이프형 콘텐츠
![인사이트](https://github.com/user-attachments/assets/122fea97-7c20-4d97-b2c5-ba8b1c50a0f6)
1. 강의들의 목록을 스와이퍼 형태로 두어 계속 반복되게 만들었습니다.
2. 각 카드엔 이미지, 제목, 강의시간, 별점 등 알찬 정보들을 통해 정보 전달에 효과적입니다.

</br>
</br>
</br>

#### 3.1.3. 베스트 강의 섹션
![베스트강의](https://github.com/user-attachments/assets/7084e9db-d90f-4445-819a-54d518067423)
1. 좌측에는 이미지배너를 두어 홍보 효과를 더했습니다.
2. 우측에는 플랙스형태로 두어 정렬했습니다.
3. 반응형에서는 이미지 배너가 사라지고 하단에 쿠폰 배너를 사용하였습니다.

</br>
</br>
</br>

#### 3.1.4. 얼리버드 섹션
![얼리버드](https://github.com/user-attachments/assets/3eeafd06-3949-4d0d-8976-195fb83a041b)
1. 얼리버드 한정 시간이 적용되어 시간이 줄어드는 모습을 보실 수 있습니다.

</br>
</br>
</br>

#### 3.1.5. 블로그 섹션
![블로그](https://github.com/user-attachments/assets/4c2d847e-6601-44cc-a465-a21f9dfb5d4f)
1. 블로그 내용처럼 3개의 내용들을 위에 강의 섹션들처럼 깔끔하게 정리했습니다.
2 하단의 배너형태처럼 중간에 끊어주는 흐름을 넣어 숨을 고를 시간을 주었습니다.


</br>
</br>
</br>

#### 3.1.6. 팁 & 테크 섹션
![팁&테크](https://github.com/user-attachments/assets/97c2df9f-39b3-4c29-a355-6c0af32ac00f)
1. 정렬된 형태로 사용자의 이용에 불필요한 경로를 없앴습니다.

</br>
</br>
</br>

#### 3.1.7. 푸터 섹션
![푸터](https://github.com/user-attachments/assets/b7df1116-ec7e-4240-83b0-e4b38d261d5f)
1. 정돈된 형태로 푸터의 배경을 어둡게 하여 튀지 않게 만들었습니다.

</br>
</br>
</br>


---

### 3.2. 서브 페이지 (총 2개)

#### 3.2.1. 로그인
![로그인](https://github.com/user-attachments/assets/d2dc8ecd-4af0-4f00-b5dc-cb6fe79ee72b)
1. 로그인페이지는 모달 형태로 만들었습니다
2. 로그인 버튼 클릭시 상단의 내용이 관심, 장바구니 등으로 바뀌는 모습을 보실 수 있습니다.

</br>
</br>
</br>

#### 3.2.2. 회원가입
![회원가입](https://github.com/user-attachments/assets/5290c44a-c93b-45be-b13b-a2015b1f26c2)
1. 회원가입창은 깔끔하게 만드는 것에 집중하였습니다.

</br>
</br>
</br>

#### 3.2.2. 상세페이지
![상세페이지1](https://github.com/user-attachments/assets/6d3c43ee-4468-4770-847b-305c1afb50e7)
1. 상단의 세부네비는 스크롤시에 고정되게 하여 사용자의 편리성을 높였습니다.
2. 내용들을 잘 정돈되게 정리하여 시각적 분산을 차단하였습니다.
![상세페이지2](https://github.com/user-attachments/assets/d5e4787a-910f-4382-8136-9e639accd67d)
3. 아코디언 형태의 강의를 모두접기, 모두펼치기를 이용하여 사용하실 수 있습니다.
![상세페이지3](https://github.com/user-attachments/assets/7ec15cc9-af8b-431e-9a81-abf6cebd17cf)
4. QnA부분의 Q를 누르시면 A답변이 나옵니다.
5. 열린 상태로 다른 Q를 누르시면 닫히고 해당 질문에 대한 답만 보이게 제작하였습니다.

</br>
</br>
</br>

#### 3.2.2. 장바구니
![장바구니](https://github.com/user-attachments/assets/0e965085-db4d-4c70-b13a-afcd03b58c14)
1. 담아져있는 강의들이 보이며 그 강의에 대한 버튼도 클릭이 가능합니다.
2. 우측의 결제창의 옵션들도 클릭 가능하여 사용자의 접근성을 높였습니다.

</br>
</br>
</br>

---

## 4. 작업 환경

1. **개발 환경**  
   <img src="https://img.shields.io/badge/windows10-0078D6?style=flat-square&logo=windows10&logoColor=white"/>

2.  **사용 프로그램**  
   <img src="https://img.shields.io/badge/Vs code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>

3.  **사용 기술**  
 <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3-1572B6?style=flat-square&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=Swiper&logoColor=white"/>
    
    
4.  **작업 해상도**   
    4.1.  PC 기준 1920X1080
    4.2   반응형 대응 태블릿 768px-1024px 
    4.2.  반응형 대응 모바일 768px미만

</br>
</br>
</br>

---

## 5. 관련 링크
- [🎨 디자인 시안](https://www.figma.com/design/FARNKdnAIcQ5WngSMrL0pj/%ED%81%B4%EB%9E%98%EC%8A%A4101?node-id=0-1&m=dev&t=TamZ5RxhDKgN7HvQ-1)
- [🌐 DEMO 페이지](https://young0234.github.io/Inflearn/)
</br>
</br>
</br>


---
