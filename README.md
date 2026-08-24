# blog-images

[현명한 부자가 되는 길](https://rich.crowdniwant.com) 에 쓰는 이미지 저장소입니다.

## 왜 여기에 두나

Blogger API에는 이미지 업로드 기능이 없어서, 자동화가 만든 이미지를 올릴 곳이
필요했습니다. 무료 이미지 호스팅(ifh.cc 등)은 만료되면 그 사이트의 안내 이미지가
글에 그대로 박히고, DALL-E 같은 임시 URL은 몇 시간이면 죽습니다. 실제로 이 블로그의
기존 글에서도 그렇게 깨진 이미지가 7개 나왔습니다.

이 저장소는 계정 소유자가 통제하므로 남의 사정으로 끊기지 않습니다.

## 사용법

`img/` 아래에 날짜별로 저장하고, jsDelivr CDN으로 불러옵니다.

    https://cdn.jsdelivr.net/gh/Kee-Seok/blog-images@main/img/2026-08-24/thumb.jpg

jsDelivr는 GitHub 저장소를 CDN으로 서빙해 주며, 캐시가 걸려 raw.githubusercontent.com
보다 빠르고 트래픽 제한도 없습니다.

## 규칙

- 파일명은 내용을 설명하는 영문으로 (SEO에서 파일명도 읽힙니다)
- 저작권이 확인된 이미지만 (스톡 사진은 라이선스 확인, 화면 캡처는 개인정보 가림)
- 지우지 마세요. 발행된 글이 이 주소를 참조합니다
