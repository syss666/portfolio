---
layout: post
title: '영화 정보 웹사이트'
---

TMDB의 API를 이용하여 아래 그림과 같이 영화 정보를 보여주는 웹사이트 입니다.
<img data-action="zoom" src='{{ "/assets/img/proj-1/mainpage.JPG" | relative_url }}' alt='absolute'>

영화는 현재 개봉중인 영화와 개봉 예정인 영화 그리고 높은 평점을 받은 영화  목록. 
{%   image="projects/proj-1/main_nowplay.JPG" %}
{%  image="projects/proj-1/main_commingsoon.JPG" %}
{%  image="projects/proj-1/main_toprated.JPG" %}

회원가입 페이지는 아이디 중복 체크 패스워드 체크를 하여 이상없으면 회원가입
{% include image.html  image="projects/proj-1/signup.JPG" %}
가입 성공시 로그인 페이지로 이동
{% include image.html  image="projects/proj-1/login.JPG" %}
로그인 성공시 (session에 회원정보 저장여부) 상단 메뉴창이 전환
{% include image.html  image="projects/proj-1/topmenu.JPG" %}
{% include image.html  image="projects/proj-1/topmenu_login.JPG" %}
아이디 부분 클릭시 메뉴창
{% include image.html  image="projects/proj-1/mypagemenu.JPG" %}
개인정보 및 수정 페이지
{% include image.html  image="projects/proj-1/mydata.JPG" %}
회원 탈퇴 페이지 (체크박스 클릭후 누르면 회원탈퇴)
{% include image.html  image="projects/proj-1/delete.JPG" %}
관심목록
{% include image.html  image="projects/proj-1/myfav.JPG" %}
영화 사진 클릭시 페이지
{% include image.html  image="projects/proj-1/item.JPG" %}
관심 글자 밑에 체크표시 클릭시 아래 사진 처럼 이미지가 변하며 관심 목록 페이지에 추가
{% include image.html  image="projects/proj-1/itemfav.JPG" %}
영화 설명창 밑에는 예고편 표시
{% include image.html  image="projects/proj-1/trailer.JPG" %}

검색 시 해당 검색어에 따른 영화 출력
{% include image.html  image="projects/proj-1/searchpage.JPG" %}

페이지 이동 같은 경우는 10개씩 이하일 경우 해당 수만큼 표시 
{% include image.html  image="projects/proj-1/page.JPG" %}

좌측에는 장르별 검색 
{% include image.html  image="projects/proj-1/sidebar.JPG" %}
체크한 장르 영화 화면
{% include image.html  image="projects/proj-1/genre.JPG" %}

영화 이미지에 마우스 올린 페이지
영화 스토리와 이름 올라옴
{% include image.html  image="projects/proj-1/hover_img.JPG" %}
