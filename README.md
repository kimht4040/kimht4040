<div style="background-color: #242424; color: #eaeaea; padding: 40px; border-radius: 8px;">

# kimht4040

방위산업 및 자동차 산업의 임베디드 시스템 및 시스템 소프트웨어 엔지니어를 목표로 하는 개발자입니다. 하드웨어 제어, 로우레벨 프로그래밍, 그리고 시스템 최적화에 집중하고 있으며 C/C++ 기반의 펌웨어 제어 로직 구현과 RTOS 환경에서의 멀티태스킹 설계에 익숙합니다.

## 기술 스택 및 개발 환경
* Languages: C, C++, Python, C#
* Embedded & OS: STM32, Raspberry Pi, Arduino, Orange Pi Zero 3, Linux, Ubuntu, Yocto, WSL2
* Tools & Libraries: CLion, PyCharm, DataGrip, CMake, OpenCV, FreeRTOS

## 주요 프로젝트

### Target Tracking System (자동 추적 터렛 시스템)
카메라 영상으로 목표 객체를 실시간 탐지하고 STM32로 제어 명령을 전달하여 모터를 구동하는 추적 플랫폼입니다.
* Tech: C/C++, OpenCV, STM32, FreeRTOS, CAN/UART
* Details: HSV 색상 검출 및 칼만 필터를 적용하여 추적 위치의 흔들림을 보정했으며, FreeRTOS를 활용해 제어 로직과 입력 처리 태스크를 분리하여 안정적인 구동 환경을 구축했습니다.

### Conveyor Belt Sorting System (컨베이어 자동 분류 로봇팔)
물체를 인식해 정상품과 불량품을 구분한 뒤, 로봇팔과 컨베이어 벨트를 연동해 자동으로 처리하는 시스템입니다.
* Tech: C/C++, STM32, FreeRTOS, CAN
* Details: 카메라 노드, 로봇팔, 벨트 제어 노드 간의 CAN 통신(500kbps)을 구축하고, 생산자-소비자 패턴의 세마포어 처리를 통해 모터 동작 비동기 제어 시스템을 구현했습니다.

### Osu! Rhythm Game (4-Key 리듬 게임)
`.osu` 비트맵 파일을 파싱하여 노트 낙하 및 사용자 입력을 실시간으로 처리하는 데스크톱 리듬 게임입니다.
* Tech: C++17, SFML 3.0, BASS, SQLite3
* Details: SFML 3.0 표준에 맞춰 그래픽 렌더링 및 게임 상태 전환을 구현했으며, BASS 오디오 라이브러리 연동, SQLite를 이용한 로컬 사용자 최고 점수 데이터베이스 관리를 구축했습니다.

### IoT .NET Repository
IoT 환경 구축 및 데스크톱 애플리케이션 연동을 위한 시스템 구현 리포지토리입니다.
* Tech: C#, .NET, WPF
* Details: WPF 기반의 사용자 인터페이스(UI) 설계와 컨트롤 템플릿 구성을 통해 기기 상태를 모니터링하고 제어할 수 있는 데스크톱 클라이언트를 작성했습니다.

</div>
