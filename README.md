# 나의 연금 계산기 · My Pension Calculator

Air Canada IAM&AW 직원용 연금 예상 계산기 (DB 플랜 / IAM MEPP + CPP + OAS).
A phone web app estimating Air Canada IAM&AW pension (DB or MEPP) plus CPP and OAS.

- 정적 사이트(빌드 없음). Static site, no build step.
- 모든 입력값과 급여 명세서 이미지는 폰 안에서만 처리·저장됩니다. All inputs and pay stub images stay on the device.
- 급여 명세서 글자 인식: Tesseract.js 5.1.1 (`tess/`, self-hosted). `tess/worker.min.js` is patched so language objects initialize by `code`.

공개 자료 기반 추정치입니다. 실제 연금은 Air Canada 공식 명세서가 기준입니다.
