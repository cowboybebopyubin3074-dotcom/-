# 대한(주) 자동화 시스템

영업/전략기획 업무 자동화를 위한 프로젝트입니다. 문서(제안서, 기안문, 전략기획 보고서 등) 관리는 이 시스템의 일부입니다.

## 폴더 구조

```
.
├── docs/
│   └── proposals/     # 제안서, 기안문, 전략기획 보고서 (HACCP 규정 및 daehan-proposal-style 준수)
├── src/
│   └── automation/    # 자동화 스크립트, 워크플로우
├── package.json
└── .gitignore
```

## 문서 작성 원칙

`docs/proposals/` 하위 문서는 HACCP 규정과 절차를 준수하고, 어투/스토리 구조/비주얼 원칙은 `daehan-proposal-style` 스킬을 따릅니다.

## 자동화 스크립트

`src/automation/` 하위에 업무별 자동화 스크립트를 추가합니다. (예: 문서 생성, 데이터 수집, 알림 발송 등)
