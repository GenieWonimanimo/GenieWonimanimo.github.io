---
title: "훌륭한 아키텍처가 갖추어야 할 항목들"
permalink: /code%20complete/Ch03/architecturemeasure/
layout: single
toc: true
toc_sticky: true
toc_label: "항목 목록"
---

## 구체적인 아키텍처 주제
- 좋은 아키텍처의 개요와 설명을 포함한 전체적인 프로그램 구조가 명확한가?
- 주요 빌딩 블록을 그 책임 영역과 다른 빌딩 블록에 대한 인터페이스를 포함해 잘 정의했는가?
- 요구사항에 있는 모든 기능을 적절한 수의 빌딩 블록으로 다루었는가?
- 가장 중요한 클래스를 기술하고 정당성을 증명했는가?
- 데이터베이스의 구조와 내용을 명시했는가?
- 핵심 비즈니스 규칙을 모두 명시하고 그 규칙이 시스템에 미치는 영향을 기술했는가?
- 사용자 인터페이스 설계 전략을 기술했는가?
- 사용자 인터페이스를 일부 변경해도 프로그램의 나머지 부분에 영향을 미치지 않도록 모듈화했는가?
- I/O 처리 방법을 기술하고 정당성을 증명했는가?
- 스레드와 데이터베이스 연결, 핸들, 네트워크 대역폭 등과 같이 부족한 자원에 대해서 자원 사용 예측 및 자원 관리 방법을 기술했는가?
- 아키텍처의 보안 요구사항을 기술했는가?
- 아키텍처가 각 클래스나 서브시스템, 기능 영역에 대한 공간과 속도를 설정했는가?
- 아키텍처가 확장성을 어떻게 구현할지 기술했는가?
- 아키텍처가 상호운용성을 다루는가?
- 국제화와 지역화를 위한 방법을 기술했는가?
- 일관된 오류 처리 방법을 제공했는가?
- 장애 허용에 대한 접근 방법을 정의했는가?(장애 허용이 필요한 경우)
- 시스템의 모든 부분에 대해서 기술적 구현 가능성을 확인했는가?
- 과도한 엔지니어링에 대한 해결책을 명시했는가?
- 구입할 것인지 구현할 것인지에 대한 결정을 포함했는가?
- 재사용된 코드가 아키텍처의 다른 목표와 어떻게 부합할 것인지 기술했는가?
- 아키텍처가 가능성 있는 변경 사항을 수용할 수 있도록 설계했는가?

## 일반적 아키텍처 품질
- 아키텍처가 모든 요구사항을 설명하고 있는가?
- 지나치거나 부족한 부분은 없는가?
- 이 부분에 대한 기대치를 명확하게 설정하고 있는가?
- 전체적 아키텍처가 개념적으로 일관성을 갖는가?
- 최상위 설계가 구현에 사용될 기계와 언어에 독립적인가?
- 모든 중요한 결정에 대한 근거를 제공하는가?
- 시스템을 구현할 당사자로서 아키텍처에 만족하는가?