# The Detective's Notebook — Landing & Legal

**탐정 수첩 · The Detective's Notebook** 공식 랜딩 페이지 + App Store / Google Play 심사용 **개인정보처리방침**·**이용약관** 정적 호스팅. GitHub Pages로 서빙합니다.

## 페이지

- `index.html` — **마케팅 랜딩**(소개·기능·다운로드 CTA·법무 링크). 앱 내 공유 카드의 다운로드 링크가 이 페이지로 유입됩니다.
- `privacy-policy.html` — 개인정보처리방침 (KO/EN 토글)
- `terms-of-service.html` — 이용약관 (KO/EN 토글)
- `icon.png` / `favicon.png` — 앱 아이콘(게임 저장소 `assets/icon.png` 미러)
- `screenshots/` — 앱 화면 캡처(홈·탐문·추리 보드·랭킹). 스포일러(범인·단서·진실) 없는 화면만. UI가 바뀌면 재캡처해 교체.

## 공개 URL (GitHub Pages)

- 랜딩: https://taehun.github.io/detectives-notebook-legal/
- 개인정보처리방침: https://taehun.github.io/detectives-notebook-legal/privacy-policy.html
- 이용약관: https://taehun.github.io/detectives-notebook-legal/terms-of-service.html

App Store Connect의 **개인정보처리방침 URL** 필드에 위 privacy-policy URL을 등록합니다.

## 출시 시 할 일

- 스토어 출시되면 `index.html`의 **다운로드 버튼**(`.store`)에 실제 App Store / Google Play 링크를 연결하고 `aria-disabled`·`coming` 안내를 제거합니다.
- 앱 아이콘이 바뀌면 게임 저장소에서 `icon.png`를 다시 복사해 푸시합니다.

## 갱신

데이터 처리/제3자/광고 정책이 바뀌면 해당 HTML의 `시행일`과 본문을 수정 후 푸시하면 Pages가 자동 재배포됩니다.

> **수익 모델: 광고 전용(IAP 없음).** 인앱결제·가상 재화·유료 구독·광고 제거 상품이 없으므로 통신판매업 신고 대상이 아닙니다. 추후 유료 결제를 도입하면 통신판매업 신고 + 약관에 가상재화·환불·미성년자 보호 조항을 복원해야 합니다.
