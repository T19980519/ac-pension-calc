# 나의 연금 계산기 · My Pension Calculator

개인이 만든 연금 예상 계산기입니다 (DB 플랜 / MEPP + CPP + OAS).
A personal phone web app estimating a DB or MEPP pension plus CPP and OAS.

- 정적 사이트(빌드 없음). Static site, no build step.
- 모든 입력값과 급여 명세서 이미지는 폰 안에서만 처리·저장됩니다. All inputs and pay stub images stay on the device.
- 급여 명세서 글자 인식: Tesseract.js 5.1.1 (`tess/`, self-hosted). `tess/worker.min.js` is patched so language objects initialize by `code`.

회사나 노조의 공식 도구가 아니며, 공개 자료 기반 추정치입니다. 실제 연금액은 회사 연금 포털에서 확인하세요.
This is not an official company or union tool. Estimates only; check your actual pension on your plan's portal.
