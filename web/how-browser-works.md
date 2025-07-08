### Q3. 주소창에 google.com을 입력하면 일어나는 일
아래 다섯가지 과정으로 나눌수 있습니다? 조금 ... 구어체 적인 느낌이야.
1. 탐색(Navigation)
2. 응답(Response)
3. 구문분석(Parsing)
4. 렌더(Render)
5. 상호작용(Interactivity)


1. DNS 조회
사용자가 주소창에 www.google.com을 입력하면, 해당 도메인을 dns 서버에서 대응하는 ip가 무엇인지 찾습니다.

2. tcp 연결
그리고 tcp 3 way handshake 과정을 통해 서버와 연결합니다.

3. http 요청
연결이 완료되면 브라우저는 서버에 http요청을 보냅니다.

4. 서버 응답
서버는 이 요청을 처리하고. 응답으로 데이터를 보냅니다.

5. 파싱과 렌더링
브라우저가 네트워크를 통해 응답받은 데이터를 DOM, CSSOM으로 변경합니다.
파싱과정에서 얻은 DOM, CSSOM을 렌더트리로 생성하여 레이아웃을 구성합니다.

6. 상호작용
자바스크립트 함수등 인터렉티브한 것들을 설정합니다 ??




참고자료
https://developer.mozilla.org/ko/docs/Web/Performance/Guides/How_browsers_work
https://velog.io/@jiyunk/%EC%A3%BC%EC%86%8C%EC%B0%BD%EC%97%90-URL%EC%9D%84-%EC%9E%85%EB%A0%A5%ED%95%98%EB%A9%B4-%EC%9D%BC%EC%96%B4%EB%82%98%EB%8A%94-%EC%9D%BC%EB%93%A4-%EC%9B%B9%EC%9D%98-%ED%9D%90%EB%A6%84-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0