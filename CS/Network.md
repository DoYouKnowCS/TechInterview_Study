<details>
   <summary><span style="border-bottom:0.05em solid"><strong>OSI 7계층에 대해서 설명해 주세요.</strong></span></summary>
<hr>
    <p>
    Application Layer - 클라이언트에게 인터페이스를 제공해주는 계층, 우리가 접속하는 웹브라우저 등이 이 계층에 속한다. FTP, HTTP, SMTP 등의 프로토콜로 통신한다.
    </p>
    <p> Presentation Layer - 데이터의 표현 형식을 결정하는 레이어이다. 파일의 인코딩, 압축등을 담당. JPEG, SSL, MPEG, ASCII등이 속한다.
    </p>
    <p>Session Layer - 응용 프로그램간의 연결, 유지, 종료를 관리한다. 에러가 발생하면, 체크포인트를 통한 동기화 지점을 두어 재 전송한다.</p>
    <p>Trasnport Layer - 전송계층은 송신자와 수신자를 연결하는 계층이다. TCP/ UDP를 통하여 연결을 수립하며, PDU는 세그먼트입니다. </p>
    <p>Network Layer - 논리 주소인 IP를 통하여 통신. 데이터그램(패킷)을 전송하는 계층이다. ARP, RARP 프로토콜 사용. 대표적인 것은 라우터입니다.</p>
    <p>Datalink Layer - 물리주소인 MAC주소를 통하여 전달, PDU는 프레임입니다.</p>
    <p>Physical Layer - 비트로 전송하는 계층, 광섬유, 퉁신 케이블 장치가 속합니다.</p>
<hr>
</details>

<details>
   <summary><span style="border-bottom:0.05em solid"><strong>흐름제어, 혼잡제어, 오류제어에 대해 설명해주세요.</strong></span></summary>
<hr>
<p>흐름제어는 송신자의 전송속도와 수신자의 수신속도 차이를 해결하기 위한 방안입니다. stop and wait 방식과 sliding window 방식이 있습니다.</p>
<p>혼잡제어는 송신자의 데이터 전송속도와 네트워크 내 데이터 처리 속도의 차이로 인한 버퍼 오버플로우를 방지할 수 있습니다. slow start, congestion avoidance, fast recovery방식이 있습니다.</p>
<p>오류제어는 데이터를 보내어 손실되었을때 다시 재전송하는 방식 입니다. ARQ방식이 존재합니다.</p>
<hr>
</details>

<details>
   <summary><span style="border-bottom:0.05em solid"><strong>브라우저에 https://www.naver.com 을 입력했을때 일어나는일에 대해서 설명하세요</strong></span></summary>
<hr>
<p>1. DNS에서 재귀 쿼리로 도메인에 해당하는 IP주소를 찾는다.</p>
<p>2. 찾은 주소에 대해서 3way handshaking 방식으로 TCP 연결을 요청한다.</p>
<p>3. 연결이 수립되면 브라우저가 http통신을 통하여, 서버에 웹페이지를 요청한다.</p>
<p>4. 서버는 요청을 받아 브라우저에 페이지를 띄워준다. 여기서 CSR이면 번들파일을 넘겨주어, 브라우저가 자체해석하여 페이지를 띄워주고, SSR이면, 페이지를 서버에서 구성하여 브라우저에 보여준다.</p>
<hr>
</details>
