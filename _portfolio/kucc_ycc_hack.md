---
layout: post
title: 유사 강의 추천시스템
feature-img: 'assets/img/portfolio/blackboard.jpg'
img: 'assets/img/portfolio/blackboard.jpg'
date: 30 July 2022
tags: [TextMining, LDA, TopicModeling]
---

## Introduction

22년 진행된 고려대 및 연세대 중앙컴퓨터동아리 KUCC&YCC의 연합 해커톤에서 작성한 코드입니다. 해당 해커톤은 "대학생에게 도움이 되는 서비스"라는 주제로 진행되었으며 저희 팀은 수강신청에 포커스를 맞추어 서비스를 기획하였습니다.

본 레포지토리는 "유사 강의 추천"을 위한 코드로, 사용자가 특정 강의를 선택하면 해당 강의와 유사한 강의 목록을 출력하는 방식으로 동작합니다. 이를 통해 사용자가 자신의 흥미와 유사한 강의가 어떤 것들이 있는지 쉽게 찾을 수 있도록 하였습니다.

저희 팀은 "유사 강의 추천" 외에도 마일리지형 수강신청을 위한 적정 마일리지 제안 알고리즘을 작성하였으며, 이를 실제 웹으로 구현하였습니다.

## My Contribution

저는 유사 강의 추천 알고리즘을 제안하고 구현하는 역할을 맡아 수행하였습니다. 유사 강의 추천은 LDA (Latent Dirichlet Allocation) 알고리즘을 통한 토픽 별 클러스터링을 기반으로 이루어집니다. 이에 강의계획서의 텍스트 정보를 크롤링하여 저장하고, 이를 전처리한 뒤, LDA 알로리즘을 적용하는 전 과정에 대한 코드를 모두 작성하였습니다. 이는 아래 레포지토리 내 코드를 통해 확인 가능합니다.

Link: [Click](https://github.com/hyewwn/KUCC_YCC_hack)
