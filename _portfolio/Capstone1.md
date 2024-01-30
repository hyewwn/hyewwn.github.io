---
layout: post
title: '대형마트의 공조제어 데이터를 활용한 시계열 온도 예측'
feature-img: 'assets/img/portfolio/blue.jpg'
img: 'assets/img/portfolio/market.jpg'
date: 23 December 2023
tags: [TimeSeries, Forecasting]
---

## Introduction

'캡스톤디자인1' 수업 중 작성했던 프로젝트 파일입니다. 대형마트의 공조제어 데이터를 이용한 시계열 온도 예측 프로젝트를 수행하였습니다.

대형마트 공조제어 데이터의 경우 제어변수와 환경변수로 구분됩니다. 제어변수는 AHU, Chiller의 inverter 값으로 기록되며 환경변수의 경우 Temperature, Humidity, Monoxide, Dioxide 등 대형마트 곳곳의 센서에서 수집되는 값으로 기록되어 있습니다. 대형마트의 경우 격벽이 없는 넓은 공간, 각 센서의 위치, AHU 및 Chiller의 동작 방식 등을 종합적으로 고려한 온도 예측을 필요로 합니다. 특히, 각 온도값은 제어값에 의존적으로 나타나기 때문에 제어변수의 변화를 잘 포착하고 이를 잘 반영하는 모델을 사용하여야 합니다.

저희 팀은 도메인 분석을 통한 적절한 데이터 전처리를 수행한 뒤 다양한 모델(LSTM, Transformer, PatchTST, Prophet, ST-GNN 등)을 탐색하고 실제로 구현하여 실험하였습니다. 일반적으로 시계열 예측 수행 시 발생하는 Time Delay(현재 Timestamp의 실제값이 다음 시점에 그대로 예측값으로 사용되는 현상)를 최소화하는 것은 '제어에 따른 온도변화'를 예측하고자 하는 본 태스크에서 가장 중요한 영역이었습니다. 이를 위해 모델의 테스트 단계에서 한 step씩 예측을 수행하며 이때 실제값은 사용하지 않고 이전 시점의 예측값만을 사용하였습니다. 그 결과 도메인에 적합한 예측 모델을 개발할 수 있었습니다.

###### 최우수상(1팀)을 수상하였습니다.

## My Contribution

본 프로젝트 수행 과정에서 전처리, 모델 탐색, 모델 구현, 실험 설계 및 수행 등 전과정에 참여하였습니다.

Link: [Click](https://github.com/hyewwn/CapstoneDesign1)
