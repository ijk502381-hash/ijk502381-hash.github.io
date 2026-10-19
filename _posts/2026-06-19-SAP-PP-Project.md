---
layout: post
title:  "SAP PP 구축 프로젝트"
info: "가구 제조 기업 대상 PP 모듈 구축"
tech : "SAP PP, MM, SD, FI, ABAP"
type: Project
---

## SAP PP 구축 프로젝트
가구 제조 기업을 대상으로 PP 모듈을 구축한 프로젝트입니다.
기준정보 생성부터 생산오더 실적 확정까지 생산 프로세스를 구성하고, SD·MM·FI 모듈과 연계했습니다.
작업장, BOM, 라우팅을 생성한 뒤 MRP를 수행하고 생산오더를 처리했습니다.
또한 생산계획을 지원하는 커스텀 ABAP 프로그램을 개발했습니다.


## 기술
* PP 설정: CR01, CS01, CA01, CO01, CO11N
* 수요 계획 및 MRP: MD61, MD62, MD04
* ABAP: BAPI_REQUIREMENTS_CREATE / BAPI_REQUIREMENTS_CHANGE를 활용한 PIR 프로그램, 커스텀 MRP 프로그램, 커스텀 테이블(SE11)
* 문제 해결: OPK4 설정 변경으로 생산오더 실적 확정 오류 해결


## 기간
2026/03 ~ 2026/06
