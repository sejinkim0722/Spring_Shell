# Spring_Shell

* 타겟 서버에 사전 정의되어 있는 작업들을 원격으로 실행하는 Spring-Shell 기반의 CLI 어플리케이션 샘플(프로토타입)입니다.
* 타겟 서버의 역할을 모의로 수행하는 **CLI_App** 프로젝트와 한 쌍이 됩니다.
* 주 목적은 타겟 서버의 로컬 디렉토리에 위치한 특정 Shell(Bash) Script를 실행하고, 그 결과값과 성공 여부를 확인하여 서버 관리 업무에 활용하는 것입니다.
* 일반적으로 CLI 어플리케이션에서 기대될 만한 기능들(ANSI 출력, 명령어 히스토리 및 목록 확인, 가변 인자 전달 등)을 수행할 수 있습니다.
* 접속을 시도할 서버의 주소 정보와 예외 로그는 Embedded DB(Apache Derby)에 저장, 관리됩니다.
