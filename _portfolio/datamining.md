---
layout: post
title: '데이터마이닝: 맛집 리뷰 분석'
feature-img: 'assets/img/portfolio/restaurant.jpg'
img: 'assets/img/portfolio/restaurant.jpg'
date: 23 June 2022
tags: [TextMining, LDA, TopicModeling]
---

## Introduction

'데이터마이닝' 수업 중 작성했던 프로젝트 파일입니다.
개인 프로젝트로는 유방암 진단 데이터를 이용해 간단한 KNN-clustering을 수행하였고, 팀 프로젝트로는 "맛집 리뷰 분석"을 주제로 Sentiment Analysis 및 Topic Modeling을 수행하였습니다.

팀프로젝트에서 "맛집 리뷰 분석"을 위해 네이버지도와 카카오맵에서 서울 내 25개 자치구 별 50개 음식점 리뷰를 크롤링하였으며 얻어진 데이터에 대해 텍스트 전처리를 통해 적절하게 벡터화하였습니다. 최종적으로 이를 다양한 classifier를 이용해 긍정/부정 리뷰로 분류하였습니다. 각 음식점 리뷰의 키워드를 파악하기 위한 방법으로 LDA 토픽 모델링 알고리즘을 사용하였습니다. 이때 문서는 각 음식점으로 설정하여 음식점 별로 키워드가 도출되도록 하였습니다. 그 결과 각 음식점 별로 긍정 리뷰 키워드, 부정 리뷰 키워드를 도출하여 단순한 평점 정보를 넘어 더욱 구체적인 정보를 포함할 수 있도록 하였습니다.

## My Contribution

팀프로젝트에서 저는 전처리 및 Sentiment Analysis를 수행하였습니다. 특히 전처리 과정에서 다양한 형태소 분석기를 비교하였으며, Sentiment Analysis를 수행하는 과정에서 여러 Classifier를 비교하였습니다.

Link: [Click](https://github.com/hyewwn/Datamining)
