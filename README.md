# Hello, World!

## 급식 조회
[소스코드](https://github.com/chick0/meal) / [웹 사이트](https://school.ch1ck.xyz/)

쉽고 빠르게 작동하는 급식 조회 웹 사이트

Redis를 사용해 조회한 조회한 학교의 급식 정보를 캐싱해 요청 시간을 단축한다.

localStorage에 즐겨찾기 정보를 저장해 편하게 사용 할 수 있다.

## 택배 조회 API
[소스코드](https://github.com/chick0/parcel-tracker)

각 택배사의 홈 페이지를 크롤링해서 배송 위치를 보여주는 API

그냥 요청할 경우 처음부터 끝 까지의 이동 경로를 보여주지만, 뒤에 `/last`를 붙이면 마지막 위치만 보여준다.

## 익명 게시판
[소스코드](https://github.com/chick0/anon_board)

누구나 글과 댓글이 작성 가능한 서비스

글을 쓰거나 댓글을 남겼을때 IP주소가 기록되지 않고 글 삭제는 글 작성시에 지정한 비밀번호로만 삭제가 가능하다.

## 파일 공유 웹
[소스코드](https://github.com/chick0/share)

로그인 없이 파일 업로드가 가능한 서비스

업로드한 파일인 최소 1일에서 최대 14일 까지 보관 날짜 지정이 가능하다.

업로드된 파일은 신고를 통해 다운로드 전 경고를 보낼수 있고 서비스 관리자가 파일의 다운로드를 차단할 경우 다운로드가 불가능하다.

관리자는 [관리도구](https://github.com/chick0/share_client)를 통해 업로드된 파일을 관리할 수 있습니다.

## 투두 리스트
[소스코드](https://github.com/chick0/todo)

해야 할 일을 작성하고 관리할 수 있는 서비스

사용자가 등록한 할 일을 목록으로 보여주고 수정및 삭제를 지원한다.

할 일을 추가, 수정, 삭제, 불러오기 작업 모두 API로 동작한다.

## aboutus - 팀 소개 페이지
[소스코드](https://github.com/chick0/aboutus) / [웹 사이트](https://calicocheese.xyz)

파이썬 Flask 프레임워크를 사용한 팀 소개 페이지로 멤버를 등록하거나 수정 삭제가 가능하다.

등록된 멤버는 프로젝트를 등록할 수 있다. 등록한 프로젝트는 작성자가 수정, 삭제, 비공개 설정을 할 수 있다.

또 마크다운을 지원하고 SimpleMDE 에디터를 내장하고 있어서 프로젝트 정보를 작성및 수정하기가 편하다.

## 이메일 인증 API
[소스코드](https://github.com/chick0/mail)

GMail SMTP서버를 통해 동작하는 API 서비스이다.

사용 하려면 클라이언트를 등록하고 승인해야 한다.

## 랜덤닉네임
[소스코드](https://gist.github.com/chick0/20b4d213617b4d2512018a7c66b44cfd)

음식 이름과 그 이름을 꾸며주는 말을 이용해 랜덤으로 닉네임을 생성해주는 함수이다.

## pycache
[소스코드](https://github.com/chick0/pycache)

소켓으로 통신하고 데이터를 임시로 저장하기 위한 캐시 서버이다.

서버는 전역 변수에 데이터를 저장해 클라이언트한테 전달하고 전달 받는다.

클라이언트에서는 GET, SET, DEL 명령어를 통해 데이터에 접근할 수 있다.

데이터 전달을 JSON을 통해서 한다.


## urls - 링크 단축기
[소스코드](https://github.com/chick0/urls) / [웹 사이트](https://u.ch1ck.xyz/)

가벼운 웹 사이트를 목표로 해서 나한테 익숙한 Flask 프레임워크말고 Sanic 프레임워크를 사용했다.

CSS나 자바스크립트 파일이 없어서 서버 접속시 발생하는 트래픽의 양이 적어서 빠르게 웹 사이트 로딩이 가능하다.

## 21! - 심플한 카드 게임
[소스코드](https://github.com/chick0/21) / [웹 사이트](https://21.ch1ck.xyz)

개발 연습을 위해서 만든 프로젝트로 파이썬으로 만든 첫 번째 웹 게임이다.

21은 블랙잭과 비슷하지만 다른 느낌을 주고 싶어서 규칙을 수정했다.

플레이어의 닉네임을 기존에 만든 [랜덤 닉네임 생성기](https://gist.github.com/chick0/20b4d213617b4d2512018a7c66b44cfd)를 활용했다.

카드 이미지는 [여기](https://www.kenney.nl/assets/boardgame-pack)에서 다운 받은 이미지 파일을 사용했다.

