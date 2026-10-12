# FlexTrip 지원 사이트

여행 계획 앱 FlexTrip의 공개 페이지와 문제 보고 게시판입니다. 앱 소스 코드는 이 저장소에 없습니다.

| 페이지 | 한국어 | English |
| --- | --- | --- |
| 홈 | https://flex-trip.net/ | https://flex-trip.net/en/ |
| 개인정보처리방침 | https://flex-trip.net/privacy/ | https://flex-trip.net/en/privacy/ |
| 이용약관 | https://flex-trip.net/terms/ | https://flex-trip.net/en/terms/ |
| 지원 | https://flex-trip.net/support/ | https://flex-trip.net/en/support/ |
| 블로그 | https://flex-trip.net/blog/ | https://flex-trip.net/en/blog/ |

문의: flextrip-support@googlegroups.com · 문제 보고·기능 제안: [Issues](https://github.com/yjinchoi/flextrip-support/issues/new/choose)

GitHub Pages(Jekyll)가 `main` 브랜치 루트를 빌드합니다. 레이아웃은 `_layouts/default.html`, 스타일은 `assets/css/site.css`, 아이콘·로고는 앱 저장소 `design/app-icon/build.py`에서 만듭니다. 맞춤 도메인은 `CNAME`(flex-trip.net)입니다.

## 블로그

사용 안내 글은 `_posts/`(한국어)와 `en/_posts/`(영어)에 같은 파일 이름으로 둡니다. 머리말에 `lang`, `permalink`, 다른 언어 글 주소 `alt`, 연재 이름 `series`를 적습니다. 앱 화면은 `{% include shot.html src="이름" alt="…" caption="…" %}`로 넣고, 이미지는 `assets/img/blog/`에 있습니다. 화면은 앱 저장소 `apps/mobile/e2e/blog/`의 Maestro 흐름으로 iOS 시뮬레이터에서 찍어 1000px로 줄입니다. 피드는 `/blog/feed.xml`, 사이트맵은 `/sitemap.xml`(GitHub Pages 기본 플러그인)입니다.
