# KaNARIA

**KaNARIA** is a human-like AI assistant architecture combining two agent harnesses, **HaNA** and **ARIA**, for natural interaction, human-like memory, and accountable decision-making.

> **KaNARIA** = **Kosmical Agents — HaNA and ARIA**

## Overview

KaNARIA is designed as a dual-agent AI assistant system.

Instead of building one large monolithic assistant, KaNARIA separates the assistant into two different roles:

- **HaNA** — Human-like AI Native Assistant
- **ARIA** — Accountable Recursive Intelligence Architecture

HaNA focuses on natural conversation, memory, emotion-like responses, multimodal interaction, and daily assistance.

ARIA focuses on decision review, permission checks, risk evaluation, action logging, and accountability.

Together, they form KaNARIA: a human-like AI assistant system that can interact naturally while keeping important decisions traceable and responsible.

## Core Concept

HaNA proposes.  
ARIA judges.  
Harness executes.

## Components

### HaNA

**Human-like AI Native Assistant**

HaNA is the assistant-facing side of KaNARIA.

It is responsible for:

- Natural conversation
- Human-like memory
- Daily assistance
- Emotion-like interaction
- Multimodal understanding
- Creative response generation
- Voice and visual module integration

### ARIA

**Accountable Recursive Intelligence Architecture**

ARIA is the accountability side of KaNARIA.

It is responsible for:

- Decision review
- Permission control
- Risk checks
- Action logging
- Refusal reasoning
- Accountability tracking
- Safe execution support

### KaNARIA

**Kosmical Agents — HaNA and ARIA**

KaNARIA combines HaNA and ARIA into one assistant architecture.

Its goal is to create an AI assistant that is not only natural and human-like, but also responsible, reviewable, and safe to extend.

## Planned Architecture

User Input  
→ HaNA  
→ ARIA  
→ Harness  
→ Logs / Memory / Execution

HaNA understands context, generates responses, and creates action proposals.

ARIA reviews important decisions, checks permissions, evaluates risks, and returns approval, revision, or rejection.

The harness executes only approved actions and stores logs for later review.

## Shared State

HaNA and ARIA may run as separate modules or separate processes, but they can share key state files:

- Soul.md
- SSE state / weights
- Permission manifest
- Causal logs
- Identity metadata
- Continuity seed

## Project Status

This project is currently in the early concept and architecture design stage.

Initial goals:

- Define HaNA and ARIA interfaces
- Design the shared state format
- Build the proposal-review-execution pipeline
- Implement basic memory and logging
- Test HaNA and ARIA as separate agent harnesses

## License

No license has been selected yet.

This repository is currently intended for open research and early development.


========KR=========

# KaNARIA

**KaNARIA**는 자연스러운 상호작용, 인간적인 기억, 책임 있는 의사결정을 위해 두 개의 에이전트 하네스인 **HaNA**와 **ARIA**를 결합한 인간형 AI 비서 아키텍처입니다.

> **KaNARIA** = **Kosmical Agents — HaNA and ARIA**

## 개요

KaNARIA는 이중 에이전트 AI 비서 시스템으로 설계되었습니다.

하나의 거대한 단일 비서를 만드는 대신, KaNARIA는 AI 비서를 두 가지 역할로 분리합니다.

- **HaNA** — Human-like AI Native Assistant
- **ARIA** — Accountable Recursive Intelligence Architecture

HaNA는 자연스러운 대화, 기억, 감정과 유사한 반응, 멀티모달 상호작용, 일상 보조에 집중합니다.

ARIA는 의사결정 검토, 권한 확인, 위험 평가, 행동 기록, 책임 추적에 집중합니다.

두 시스템이 결합되어 KaNARIA를 이룹니다. KaNARIA는 자연스럽게 상호작용하면서도 중요한 결정이 추적 가능하고 책임 있게 관리되는 인간형 AI 비서 시스템을 목표로 합니다.

## 핵심 개념

HaNA가 제안합니다.  
ARIA가 판단합니다.  
Harness가 실행합니다.

## 구성 요소

### HaNA

**Human-like AI Native Assistant**

HaNA는 KaNARIA에서 사용자와 직접 마주하는 비서 역할을 담당합니다.

HaNA의 역할은 다음과 같습니다.

- 자연스러운 대화
- 인간적인 기억
- 일상 보조
- 감정과 유사한 상호작용
- 멀티모달 이해
- 창의적인 응답 생성
- 음성 및 시각 모듈 통합

### ARIA

**Accountable Recursive Intelligence Architecture**

ARIA는 KaNARIA의 책임성 담당 구조입니다.

ARIA의 역할은 다음과 같습니다.

- 의사결정 검토
- 권한 제어
- 위험 확인
- 행동 기록
- 거부 사유 생성
- 책임 추적
- 안전한 실행 지원

### KaNARIA

**Kosmical Agents — HaNA and ARIA**

KaNARIA는 HaNA와 ARIA를 하나의 비서 아키텍처로 결합합니다.

목표는 단순히 자연스럽고 인간적인 AI 비서를 만드는 것이 아니라, 책임 있고 검토 가능하며 확장하기 안전한 AI 비서 구조를 만드는 것입니다.

## 계획 중인 아키텍처

사용자 입력  
→ HaNA  
→ ARIA  
→ Harness  
→ 로그 / 기억 / 실행

HaNA는 맥락을 이해하고, 응답을 생성하며, 행동 제안을 만듭니다.

ARIA는 중요한 결정을 검토하고, 권한을 확인하며, 위험을 평가한 뒤 승인, 수정 요청, 또는 거부를 반환합니다.

Harness는 승인된 행동만 실행하고, 이후 검토를 위해 로그를 저장합니다.

## 공유 상태

HaNA와 ARIA는 별도 모듈 또는 별도 프로세스로 실행될 수 있지만, 핵심 상태 파일은 공유할 수 있습니다.

- Soul.md
- SSE 상태 / 가중치
- 권한 매니페스트
- 인과 로그
- 정체성 메타데이터
- 연속성 시드

## 프로젝트 상태

이 프로젝트는 현재 초기 개념 및 아키텍처 설계 단계에 있습니다.

초기 목표는 다음과 같습니다.

- HaNA와 ARIA의 인터페이스 정의
- 공유 상태 형식 설계
- 제안-검토-실행 파이프라인 구축
- 기본 기억 및 로그 시스템 구현
- HaNA와 ARIA를 별도 에이전트 하네스로 테스트

## 라이선스

아직 라이선스는 선택되지 않았습니다.

이 저장소는 현재 공개 연구 및 초기 개발을 목적으로 합니다.