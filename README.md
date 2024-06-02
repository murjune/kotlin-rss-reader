# kotlin-rss-reader

## 기능 요구 사항
기술 블로그를 모아 나만의 블로그 모음을 만들어 보자.

- []: 블로그 RSS 주소를 입력받아 저장한다.
- []: 블로그 RSS 주소들을 url 기반으로 조회한다.
- []: 저장한 블로그 RSS 주소를 조회한다.
- []: 각 기술 블로그에 새로운 글이 게시되면 해당 사이트의 RSS가 업데이트된다.
- []: 저장한 블로그 RSS 주소를 조회하면 해당 블로그의 최신 글들을 볼 수 있다.
- [x]: 각 기술 블로그의 글을 수집하여 작성된 날짜별로 내림차순으로 정렬하여 최대 10개의 글을 표시한다.
- [x]: 찾고자 하는 단어를 입력하면 제목에 해당 단어가 포함된 게시물이 표시된다. 

## 선택 요구 사항
- 한 번 실행하면 10분마다 기술 블로그의 RSS 업데이트를 확인한다.
- 새 글이 발견되면 사용자에게 메시지로 알린다.
- 기존 기능 요구 사항은 계속 작동할 수 있어야 한다.
