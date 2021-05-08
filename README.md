# earphone
### Deep learning sound detection system
---

## 📱 담당한 기능 (Android)

- ForegroundService를 이용 24시간 소리를 듣는 알고리즘 구현
- SharedPreferences 사용하여 로그기록 유지
- 데시벨 측정
- AudioRecord를 사용하여 PCM 데이터를 추출하여 WAV변환 알고리즘 구현
- 모바일 / 웨어러블 푸쉬알림 기능 구현
- Tmap API 사용 네비게이션 기능 구현
- Animation

## 💡 프로젝트를 통해 느낀 점

- ForegroundService는 앱이 메모리 부족 시 시스템에 의해 강제로 종료되지 않는다.
- ForegroundService를 이용하면 배터리 소모가 많이 발생한다.
    - 배터리 전력을 최소화 하기 위해 취침 시간 등 사용자가 대기모드를 on / off 할 수 있는 기능을 구현했습니다.
- Github 오픈소스 분석 후 프로젝트 적용 능력
- 지도 API의 다양한 라이브러리의 사용법
- AudioRecord
    - 생명주기에 따른 적절한 자원 관리하는 방법
    - PCM파형 데시벨로 변환하는 방법
    - PCM파형 WAV파일로 저장하는 방법
