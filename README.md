# Excel VBA Macro Builder

반복되는 Excel 업무를 VBA 매크로로 자동화할 수 있도록 돕는 AI 스킬입니다. 원본 파일과 사람이 수작업으로 완성한 결과 파일을 함께 분석하고, 실제 업무 규칙을 확인한 뒤 재사용 가능한 VBA 매크로(`.bas`)를 제작합니다.

## 제공 버전

| 버전 | 대상 | 파일 |
| --- | --- | --- |
| ChatGPT | ChatGPT에서 사용할 스킬 | `chatgpt/excel-vba-macro-builder_chatgpt.zip` |
| Claude | Claude에서 사용할 스킬 | `claude/excel-vba-macro-builder_claude.zip` |

## 작업 방식

1. 원본 파일과 수작업으로 완성한 예시 파일을 분석합니다.
2. AI가 입력, 처리 규칙, 예외, 출력 형식을 업무 인터뷰로 확인합니다.
3. 업무 프로세스와 핵심 규칙을 사용자에게 제시하고 승인 Gate를 거칩니다.
4. 승인 후 VBA `.bas` 파일을 제작합니다.
5. 정적 검사와 테스트 데이터를 활용해 매크로를 검증한 뒤 결과물을 제공합니다.

## 활용 예시

- 여러 Excel/CSV 파일을 하나의 파일로 취합
- 실험 데이터의 일괄 계산 및 결과 파일 생성
- 장비 데이터 분석과 시험 결과 정리
- 조건별 데이터 분류 및 시트 분리
- 반복 보고서 작성 및 표준 양식 채우기

## 설치 및 사용 방법

1. 사용하는 AI 서비스에 맞는 ZIP 파일을 다운로드합니다.
2. 해당 서비스의 스킬 설치 기능으로 ZIP 파일을 등록합니다.
3. 새 대화에서 스킬을 선택한 뒤 자동화할 업무를 간단히 설명합니다.
4. 원본 파일과 수작업 완성본(예시 결과 파일)을 함께 첨부합니다.
5. AI의 업무 인터뷰에 답하고, 제시된 업무 프로세스와 규칙을 검토·승인합니다.
6. 검증이 완료된 VBA `.bas` 파일을 받아 Excel에서 사용합니다.

세부 설치·사용 절차는 아래 한국어 안내서를 참고하세요.

- [ChatGPT 안내서](docs/Excel_VBA_Macro_Builder_Guide_ChatGPT_KO.pdf)
- [Claude 안내서](docs/Excel_VBA_Macro_Builder_Guide_Claude_KO.pdf)
