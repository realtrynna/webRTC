# webRTC Practice

### SDK
https://docs.knowledgetalk.co.kr/

시그널링: 서로의 미디어 정보 송수신하며 스트림 주고 받는 과정

0. P2P는 내가 상대방에게 일방적으로 연결

0. 방 나갔다 들어왔을 경우 영상 다시 생성

1. 응답 코드 넘버로 주세요.

0. 지정된 이벤트가 발생하지 않았는데 이벤트가 발생

0. 수신 이벤트는 상대방이 나에게 영상을 보내면 발생

0. publish로 보내면 subscribed 이벤트로 수신됨

0. screenStart로 보내면 screen 이벤트로 수신됨

0. 영상 스트림이랑 화면 공유 스트림이랑 다른지

0. 다르다면 화면 공유 스트림은 어떻게 가져오는지

0. 기존 스트림(Media)이 있다면 추가로 생성할 필요 없음

0. publish로 보내면 getStream으로 받을 수 있음

* 공통 이벤트 응답
사용자 아이디: event.detail.user.id