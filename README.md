<나중에 리드미는 다시 재설정 해주세요>

## 개발 환경 설정
1. [firebse](https://console.firebase.google.com/)에서 프로젝트 생성
2. 레포지토리 복제 git clone https://github.com/github_username/repo_name.git
3.  npm install
4. `.env`에 1번에서 만든 firebase의 config key를 넣어주세요(값만 넣어주세요. “값” <- 이렇게 넣으면 쌍 따옴표까지 인식돼서 에러가 발생합니다). 
```
REACT_APP_FIREBASE_API_KEY= 'ENTER YOUR API'
```

.env키를 설정하면 firebaseConfig.js에 값이 공개되지 않고 apiKey: process.env.REACT_APP_FIREBASE_API_KEY 식으로 불러와집니다.
## 참고자료
**Authentication**

[비밀번호 인증](https://firebase.google.com/docs/auth/web/password-auth)

[사용자 관리](https://firebase.google.com/docs/auth/web/manage-users)

**FIrestore**

[Cloud Firestore 시작하기](https://firebase.google.com/docs/firestore/quickstart?hl=ko)