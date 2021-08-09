# Project-Road_Accident
대전시 교통사고 위험지역 도출 by LH

참가 일정 : 2021.2.25 ~ 2021.4.1

참가 팀명 : Meetwin

팀원 : 고태영, 김권호, 김성관, 박주형, 조형래

링크: https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2102_003

# 1. 과제 개요

 - 분석 목적

본 과제는 유형별 교통사고 데이터와 교통안전시설물, 거주인구, 교통량 데이터 등을 활용, 대전시 내 교통사고 발생 위험지역을 도출하여 교통안전시설물 추가 설치 시 우선 검토 등 정책 기초자료로 활용하기 위한 분석 모델 도출을 목적으로 합니다.

 - 해결 과제

    1. 교통사고 위험지역 100개소 제시
    2. 분석 조건
       - 위험지역 범위는 중심점으로부터 반경 50m를 기준으로 함(단, 분석결과에 따라 반경을 변경하여 제시 가능)
       - 연령대별 교통사고 유형 및 사고유형(차대사람, 차대차 등)과 교통안전시설물간의 인과관계를 고려(분석)한 결과 제시
       - 사용자가 자유롭게 필요 데이터를 발굴하여 사용 가능하나 최종 결과파일 제출 시 데이터 출처와 사용한 데이터도 함께 제출
       - 외부 데이터는 법적인 제약이 없는 경우에만 허용되며 크롤링을 통해 데이터를 생산 한 경우 크롤링 코드도 함께 제출


# 2. 개요

이전에 참여했던 [오산시 어린이 교통사고 위험지역 도출](https://github.com/tjdrhks0808/Project-Child_Road_Accident) 에서는 공간회귀분석(SEM, SLM)과 머신러닝 모델을 기반으로 결과를 도출했다.

이번 대전시 분석과제에서는 공간회귀분석에서 조금 더 나아간 **지리적공간가중회귀(GWR)모델**을 사용함으로써 더 발전된 형태의 분석을 진행했다.

# 3. 데이터 분석

## 발전 요소

  - 더 심도있는 EDA를 통한 파생변수 도출
  - 기존 변수선택 용도로 한정되었던 공간회귀분석을 발전시켜 최종 결론에 사용
  - '교통사고 위험도'라는 새로운 수식을 정의해 결론 도출



※분석보고서 참고
