# react-native-practice

window 환경에서 yarn 설치시 정책문제로 reject 되는 경우 발생
FullyQualifiedErrorId : UnauthorizedAccess

--> 해결책 window Powershell 관리자 권한으로 실행 후
 Set-ExecutionPolicy Unrestricted 명령어 입력시 스크립트 실행 허용이 됨
  **Unrestricted는 모든 스크립트 허용이라 RemoteSigned 하면 신뢰된 게시자 디지털 서명이 있는 스크립트 허용이니까 이거 쓰는게 나음;