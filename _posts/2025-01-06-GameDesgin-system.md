---

layout: single  
title: "시스템 기획의 핵심 접근법"  
excerpt: "시스템 기획에서 필수적인 접근법과 사례를 알아봅니다."  
categories: [GameDesign, Planning]  
tag: [SystemDesign, 기획]  
toc: true  
author_profile: false  
sidebar:  
    nav: "docs"  
search: false  

---

## 🌟 **1. 시스템 기획의 핵심 접근법**

### 🔍 **1.1 기능 단위로의 해체 (Decomposition by Functions)**

- **목적**: 설계의 누락 방지를 위해 초기 단계에서 기능을 세부적으로 나눕니다.
- **주요 사례**:
    - **인벤토리 시스템**:  
      <i class="fas fa-box-open" style="color:orange;"></i> **핵심 기능**: 아이템 저장, 장착, 해제, 정렬 등.  
      <i class="fas fa-box" style="color:green;"></i> **보조 기능**: 인벤토리 확장, 장비 프리셋 관리.
    - **방 꾸미기 시스템**:  
      <i class="fas fa-couch" style="color:blue;"></i> **구조적 설계**: 가구 배치, 캐릭터와의 상호작용.  
      <i class="fas fa-cog" style="color:purple;"></i> **규칙 정의**: 배치 및 저장 규칙, AI 동작.

---

### 🔧 **1.2 속성 단위로의 해체 (Decomposition by Attributes)**

- **속성 설계**: 데이터를 세부적으로 분해하여 기획에 활용합니다.
- **사례**:
    - **젤리 속성 (쿠키런 오븐브레이크)**:  
      <i class="fas fa-gem" style="color:green;"></i> 속도 변화, 체력 회복 등 속성별 규칙 정의.  
      <i class="fas fa-puzzle-piece" style="color:orange;"></i> 속성 조합으로 콘텐츠 확장.
    - **직업 속성 설계**:  
      <i class="fas fa-user-shield" style="color:blue;"></i> 전사, 마법사 등 스테이터스와 스킬 정의.

---

### ⚙️ **1.3 함수 기반 설계 (Function-Based Design)**

- **핵심 개념**:  
  <i class="fas fa-code" style="color:purple;"></i> 함수 설계를 통해 콘텐츠의 규칙과 변수를 체계화.
- **퀘스트 시스템 사례**:  
  <i class="fas fa-flag-checkered" style="color:green;"></i> 기본 함수: "X를 Y번 사냥하기".  
  <i class="fas fa-random" style="color:blue;"></i> 몬스터 유형(X)과 횟수(Y)를 조합하여 다수의 퀘스트 설계.

---

## 🛠️ **2. 시스템 구조화 (System Structuring)**

### 📋 **2.1 시스템 규칙 정의 (Defining System Rules)**

- **명확한 규칙 정의**:  
  <i class="fas fa-check-circle" style="color:green;"></i> 체력 감소 및 회복 규칙 등 명확한 설계로 개발 혼선을 방지.
- **사례**:  
  <i class="fas fa-heartbeat" style="color:red;"></i> 체력 감소: 일정 시간 간격으로 체력 감소 계산.  
  <i class="fas fa-plus-circle" style="color:blue;"></i> 회복: 최대치를 초과하지 않도록 설계.

---

### 🔗 **2.2 시스템 간 상호작용 설계 (Interaction Between Systems)**

- **유기적 연결**:  
  시스템 간 데이터 교환 설계로 플레이어 경험 강화.  
- **예시**:
    - **전투 시스템**:  
      <i class="fas fa-crosshairs" style="color:orange;"></i> 공격 → 대미지 계산 → 사망 처리.  
      데이터 전달 규칙 명확화.
    - **디펜스 타워 시스템**:  
      <i class="fas fa-tower" style="color:blue;"></i> 체력 계산 → 유저 승리/패배 규칙 연결.

---

### 🧩 **2.3 모듈화 설계 (Modularization for Reusability)**

- **재사용성 극대화**:  
  독립적 모듈 설계를 통해 다양한 상황에서 활용.
- **사례**:  
  <i class="fas fa-store" style="color:green;"></i> **상점 시스템**: 구매 시스템, 판매 물품 세팅, 랜덤 상품 등장.

---

## 🎨 **3. 시스템 기획의 세부 사례 분석**

### ⚔️ **3.1 전투 시스템 설계**

- **구조적 설계**:  
  <i class="fas fa-sword" style="color:red;"></i> 공격 → 대미지 계산 → 체력 0 도달 시 사망 처리.  
  <i class="fas fa-link" style="color:blue;"></i> 캐릭터 능력치와 외부 변수 고려.

---

### 🎯 **3.2 퀘스트 시스템 설계**

- **함수 기반 확장성**:  
  속성별 규칙 정의로 다양한 퀘스트 제작 가능.
- **속성별 규칙**:  
  <i class="fas fa-skull" style="color:orange;"></i> 사냥: 대상 사망 시 카운트 증가.  
  <i class="fas fa-box" style="color:green;"></i> 수집: 아이템 획득 시 완료 후 삭제.

---

### 🛒 **3.3 상점 시스템 설계**

- **모듈화 설계**:  
  구매 시스템, 판매 물품 세팅 등 독립적 설계로 확장성 확보.  
  <i class="fas fa-sync-alt" style="color:blue;"></i> 랜덤 상품 등장과 같은 고유 규칙 정의.

---

## 🚀 **4. 기획 전략**

- **분해와 분석**:  
  시스템을 작은 단위로 나누어 설계 완성도 향상.
- **확장성 확보**:  
  체계적인 규칙 정의와 함수 기반 설계.
- **유기적 연결**:  
  상호작용 설계와 모듈화로 유연성 극대화.
- **데이터 중심 설계**:  
  데이터 체계화를 통해 효율성 극대화.

---

## 🔥 **5. 결론**

- 시스템 기획은 게임 개발의 기반을 구축하는 핵심 작업입니다.  
- 체계적이고 효율적인 접근법을 통해 개발 품질을 높이고 유지보수와 확장을 용이하게 만듭니다.

---