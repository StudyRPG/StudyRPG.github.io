# Study RPG — official website

**공식 한국어 앱명:** 스터디 RPG – 공부시간·진도관리  
**영문 브랜드:** Study RPG  
**목표 홈페이지 주소 (아직 생성·확인되지 않음):** https://studyrpg.github.io/  
**AdMob app-ads.txt 주소 (아직 생성·확인되지 않음):** https://studyrpg.github.io/app-ads.txt

## 게시 방법 — StudyRPG 조직 전용 GitHub Pages

`studyrpg.github.io` 라는 사용자/조직 GitHub Pages 사이트를 사용하려면 **GitHub 소유자 이름 자체가 `StudyRPG`**이어야 합니다. 현재 사용 중인 개인 GitHub 계정 `MagicSue8809`는 로그인에 그대로 사용하고, 별도의 **GitHub 조직(Organization)** 이름을 `StudyRPG`로 생성합니다. 해당 이름이 이미 사용 중이라면 동일 주소를 사용할 수 없습니다. 이 조직과 주소는 아직 실제 생성 또는 소유가 확인되지 않았습니다.

1. GitHub 개인 계정 `MagicSue8809`로 로그인합니다.
2. GitHub **Settings → Organizations → New organization**에서 **GitHub Free** 조직을 만듭니다. **Organization name = `StudyRPG`**. GitHub가 이름 중복을 표시하면 중단하고 다른 공식 주소를 결정해야 합니다.
3. 조직 `StudyRPG`의 소유자(Owner) 권한으로, **새 공개(Public) 저장소 이름을 `studyrpg.github.io`**로 생성합니다. 기존 비공개 앱 코드 저장소 `MagicSue8809/StudyRPG_7`를 공개하거나 이전하지 않습니다.
4. 이 압축 파일의 최상위 파일(`index.html`, `app-ads.txt`, `.nojekyll`, `README.md`)을 새 저장소의 **main 브랜치 최상위(root)** 에 업로드합니다.
5. 저장소 **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → /(root) → Save**로 설정합니다.
6. 웹페이지 `https://studyrpg.github.io/`가 열리고 `https://studyrpg.github.io/app-ads.txt`의 내용이 정확히 다음 한 줄인지 확인합니다:
   `google.com, pub-3114766749641780, DIRECT, f08c47fec0942fa0`
7. 확인된 **실제 공개 URL**을 Google Play Console의 해당 앱 **개발자 웹사이트**에 등록한 뒤, AdMob 앱의 `app-ads.txt` 상태를 확인합니다. 공개 베타테스트와 AdMob 광고 승인 상태는 별도 문제이며 광고 승인을 자동으로 보장하지 않습니다.

**보안 주의:** 이 사이트 저장소는 공개입니다. 앱 소스, Firebase 키, 서명 키, 학습 데이터, 개인 이메일·계좌 정보를 넣지 마세요. 광고 게시자 ID는 광고 인증을 위해 공개되는 정보입니다.

**상태:** 사이트 파일 제작 완료 / `StudyRPG` 조직 생성과 공개 저장소·GitHub Pages 게시 미완료 / URL 및 AdMob 검증 미완료.
