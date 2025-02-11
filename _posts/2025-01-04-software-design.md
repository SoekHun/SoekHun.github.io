---
layout: single           
title: "소프트웨어 설계"    # 포스트 제목
excerpt: "정보처리 기사 1과목"    # 포스트 설명
categories: [정보처리기사]    # 카테고리 지정
tag: [소프트웨어 설계, 소프트웨어 개발 방법론, 폭포수 모형, 애자일 방법론, UI/UX 설계, 프로토타입]    # 태그 목록
toc: true             # 목차 사용
toc_sticky: true      # 목차 고정
author_profile: false
sidebar:                 # 사이드바 설정
    nav: "docs"         # docs 네비게이션 사용
---

# 정보처리기사 1과목: 소프트웨어 설계 - 정리

---

## 1. 소프트웨어 설계란?

소프트웨어 설계는 요구사항 분석 이후 소프트웨어의 구조와 구성 요소를 정의하고, 이를 기반으로 개발 과정을 체계화하는 단계입니다. 이는 소프트웨어 품질과 성능을 좌우하는 중요한 과정으로, 올바른 설계 없이는 효율적인 개발과 유지 보수가 어렵습니다.

### 소프트웨어 설계의 목적
1. **요구사항 충족**: 고객의 요구를 정확히 반영  
2. **품질 보증**: 오류를 최소화하고 신뢰성을 향상  
3. **유지 보수성 확보**: 수정과 확장에 유연한 구조  
4. **효율성 증대**: 개발 비용 및 시간을 절감  

### 설계의 핵심 원칙
- **모듈화(Modularity)**: 시스템을 작은 모듈로 나누어 설계  
- **캡슐화(Encapsulation)**: 각 모듈이 독립적으로 동작하도록 설계  
- **추상화(Abstraction)**: 불필요한 세부 사항을 감추고 본질적인 것에 초점  
- **단일 책임 원칙(Single Responsibility Principle)**: 모듈은 하나의 책임만 가져야 함  

---

## 2. 소프트웨어 설계 프로세스

소프트웨어 설계는 일반적으로 다음의 단계를 따릅니다.

### 2.1 시스템 설계(System Design)
- **시스템 아키텍처 정의**: 전체 시스템의 구조와 데이터 흐름 설계  
- **하드웨어와 소프트웨어의 분리**: 하드웨어 요구사항 정의  
- **데이터 설계**: 데이터베이스 스키마와 데이터 구조 설계  

### 2.2 상세 설계(Detailed Design)
- 각 모듈의 내부 구조를 설계  
- 프로그래밍 언어와 환경에 적합한 알고리즘과 데이터 구조 정의  

---

## 3. 소프트웨어 설계 방법론

정보처리기사 시험에서 자주 등장하는 소프트웨어 설계 방법론을 살펴보겠습니다.

### 3.1 폭포수 모형(Waterfall Model)
- **단계적 개발 모델**: 계획 → 분석 → 설계 → 구현 → 테스트 → 유지 보수  
- 장점: 체계적이고 관리가 용이  
- 단점: 요구사항 변경이 어려움  

### 3.2 애자일(Agile)
- **반복적 개발 모델**: 고객과의 지속적인 소통 및 피드백 기반  
- 대표적인 방법론: 스크럼(Scrum), XP(Extreme Programming)  
- 장점: 유연하고 빠른 개발 가능  
- 단점: 프로젝트 관리가 어렵고 일정이 불확실  

### 3.3 나선형 모형(Spiral Model)
- **위험 중심의 반복적 개발**: 계획 → 위험 분석 → 개발 및 고객 평가  
- 장점: 리스크를 줄이고 유연한 개발 가능  
- 단점: 복잡하고 비용이 높음  

---

<<<<<<< Updated upstream
## 4. UML과 설계 다이어그램
=======
### 애자일 방법론
>>>>>>> Stashed changes

### 4.1 UML(통합 모델링 언어)
UML은 소프트웨어 설계를 시각적으로 표현하는 도구입니다.  
- **유즈케이스 다이어그램(Use Case Diagram)**: 사용자와 시스템의 상호작용  
- **클래스 다이어그램(Class Diagram)**: 클래스와 객체 간의 관계  
- **시퀀스 다이어그램(Sequence Diagram)**: 시스템 내 이벤트 순서  

### 4.2 설계 다이어그램의 종류
- **컴포넌트 다이어그램(Component Diagram)**: 시스템의 구성 요소 간 관계  
- **배치 다이어그램(Deployment Diagram)**: 하드웨어 구성과 배치  

---

## 5. 설계 패턴(Design Patterns)

소프트웨어 설계 패턴은 반복적으로 나타나는 문제를 해결하기 위한 일반적인 방법론입니다.

### 5.1 생성 패턴(Creational Patterns)
- **싱글톤(Singleton)**: 하나의 객체만 생성되도록 보장  
- **팩토리 메서드(Factory Method)**: 객체 생성을 캡슐화  

### 5.2 구조 패턴(Structural Patterns)
- **어댑터(Adapter)**: 호환되지 않는 인터페이스를 연결  
- **데코레이터(Decorator)**: 객체의 기능을 동적으로 확장  

### 5.3 행위 패턴(Behavioral Patterns)
- **옵저버(Observer)**: 객체 상태 변경을 다른 객체에 알림  
- **전략(Strategy)**: 알고리즘을 캡슐화하여 교체 가능  

---
