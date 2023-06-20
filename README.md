# COM:ON 프로젝트 (www.comOn.com)

## 카카오톡 1:1 상담톡 기능
### Kakao.js
- kakao api 사용

## 날씨 앱 기능
### Weather.js
- openweathermap api 사용

## 홈페이지 공지사항 게시판

### 데이터베이스 통신
- axios.get
- axios.post
- axios.put
- axios.delete

### 글쓰기 권한 설정
* 'useEffect' 훅을 사용하여 현재 사용자의 권한을 확인하고 그에 따라 'authYn' 상태 설정
* sessionStorage.getItem('token')을 사용하여 세션 스토리지에서 토큰 추출
* jwt-decode 라이브러리를 사용하여 디코드된 토큰에서 authIdx 값을 추출
* authIdx 값과 비교하여 권한이 일치하는 경우에는 setAuthYn(true)를 호출하여 authYn 상태를 true로 설정. 권한이 일치하지 않는 경우에는 setAuthYn(false)를 호출하여 authYn 상태를 false로 설정
