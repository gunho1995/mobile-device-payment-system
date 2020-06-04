# 스마트폰을 이용한 신용카드 결제 시스템

##Contents

1. 문제 정의

  1.1 Client's Requirement

    "포항시상인연합회"는 "스마트폰을 이용한 신용카드 결제 시스템" 설계를 의뢰한다.

  1.2 Problem Statement

    "스마트폰을 이용한 신용카드 결제 시스템"과 그 구성요소를 설계한다.

  1.3 설계 목표

    시장성, 휴대성, 유용성, 내구성의 목표를 만족시킬 수 있는 설계를 구상한다.

      1.3.1 세부 목표

        각 목표에 대한 세부 목표를 Objective Tree로 도식화한다.

      1.3.2 목표 우선 순위

        최종 설계의 평가에 가중치를 부여하기 위해 PCC를 이용하여 목표의 우선 순위를 매긴다.

        시장성 > 유용성 > 휴대성 > 내구성으로 그 결과가 나타났다.

  1.4 제약조건 분석

    4가지의 제약조건으로 모든 형태의 카드 결제 방식 지원, Android, IOS 지원, 추가 서비스 비용X, VAN사와의 통신을 설정하였다.

  1.5 Revised Problem Statement

    위의 목표와 제약조건을 만족하는 Problem Statement를 기술하였다.

2. 개념 설계

  2.1 역공학

    논문 및 서적, 시장 조사, 제품 분해를 통해 설계를 위해 필요한 요소를 확인하고 대안을 제시할 수 있도록 한다.

      2.1.1 논문 및 서적

        3개의 논문 조사 결과, RFID와 같은 NFC 기능을 사용하기 위해서는 Microprocessor가 필요하다.

      2.1.2 시장 조사

        시장 조사 결과, NFC와 같은 기능을 사용하기 위해서는 5V부근의 전압이 필요하다.

      2.1.3 제품 분해

        제품 분해 결과, Magnetic 카드를 인식하는 모듈은 1V미만의 3.5mm Audio jack과 간단한 구성만 으로 설계가 가능하다.

      2.1.4 조사 결론

        IC칩 카드를 인식하는 방법(수동인식 또는 NFC)에 따라 그 구성과 전력 공급 방식이 달라진다.

  2.2 설계물이 가져야 할 기능

    Device와 App으로 나누어 필요한 기능을 나열하였다.

  2.3 기눙구현수단 수립

    기능을 구현하기 위한 수단들을 나열하였다.

3. 대안 생성

  3.1 설계대안 확장

    C-Sketch 방법을 통하여 설계대안을 확장하였다.

  3.2 설계대안 축소

    현실적인 어려움을 감안하여 설계대안을 축소하였다.

  3.3 설계대안 선정

    대안 A는 초저가형 컨셉, 대안 B는 기능형 컨셉, 대안 C는 USB형 컨셉으로 나누어 대안을 선정하였 다.

  3.4 설계대안 분석

    예상 디자인을 스케치고 각 대안의 필요한 구성 요소들을 확인하였다.

4. 대안 선정

  4.1 대안 평가 기준

    위에서 선정한 목표에 따라 목표를 어떻게 측정할지 기준을 세우고 기준을 세우기 어려운 부분들은 여러 가정을 통해 통제 할 수 있도록 하였다.

  4.2 대안 평가

    WGC를 이용하여 대안 A, B, C를 평가하고 목표의 우선순위에 따라 그 가중치를 부여하였다.

  4.3 최종 설계 선정

    대안 A를 최종 설계로 선정하였다.

  4.4 App Design

5. 결론

6. 부록

  6.1 Detailed Techniques
  6.2 관련 제품 조사
  6.3 참고 논문
  6.4 Project Managementt
