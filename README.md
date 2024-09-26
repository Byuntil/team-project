# team-project

Windows Programming 기말과제

윈도우 데스크탑 애플리케이션 작성에 사용되는 XAML 기반 UI 방식인 WPF 프레임워크 위에서 작업

## 팀원

1. 노준혁
2. 김소연
3. 구성재

# 프로젝트
 동기 :
 
    자료 업로드 알림을 서버상태에 따라 받지 못하는 경우가 빈번하게 발생. -> 과제 및 정보를 뒤늦게 확인하는 문제
    
    지속적으로 LMS 사이트에서 정보를 확인해야 함.
    
    LMS 앱에서 발생되는 push알림을 카톡, SNS, Mail과 같은 생활형 앱보다 비교적 덜 신경쓰게 됨.
    
 
 목표 :
 
    LMS 시스템 상 불편함을 일시적으로 개선시키는 것을 궁극적 목표로 잡고 진행

 개발환경 :
 
    WPF 프레임워크로 C#환경에서 개발
    
    WPF 프레임워크 & Selenium & SMTP & kakao api & MVVM 패턴
    
 구조 :
 
    MVVM 패턴 적용 (  디자인패턴 )

------------------------------------------------
    selenium을 통해 LMS Web Data Crawling + 취합 -> 자신의 lms data 업로드 -> 정해둔 시간마다 업데이트 -> 

    기존 data와 비교 -> 변경된 사항을 SMTP네이버메일 & 카카오톡api를 통해 알림 
