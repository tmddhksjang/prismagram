# prismagram
 instagram clone with Express + prisma + React and React native


## User Stories

- [x] Create account  계정을 생성
- [x] Request Secret 비밀값 요청 
- [x] Log in=confirm Secret 로그인// 로그아웃기능은 만들지않을것이다 /비밀번호 인증 관련기능도 만들것이다
페이지에 처음접속하면 이메일을 입력할것이다 그러면 우리는 사용자의 이메일로 비밀값을 전송해서진행할것 
nodemailer를 이용할것이다  사용자들이 비밀값을 페이지에 붙여넣기하면 로그인하게되고, 
 이메일에 접근할수 있다는것을 확인하는것이다 비밀값 유효기간을 지정할수도있다
 정리: 로그인하면 토큰을 부여 >사용자가 페이지에 접속 > 이메일 입력하면 > 비밀값 전송 >
 이용자 비밀값 복 붙후 접속
- [x] Like / Unlike a photo 사진에 좋아요 or 취소
- [x] Comment on a photo 사진에 댓글남기기  댓글삭제 수정은 시간낭비라 안함
- [x] Search by user 사용자명으로 검색
- [x] Search by location 위취로 검색
- [x] Follow User  
  [x] Unfollow User 팔로우하거나 끊기
- [x] Edit my profile 사용자가 프로필정보를 편잡할수도 있어야한다
- [x] See user profile 사용자의 프로필 보기
- [x] see MY profile
- [x] See the full photo  사진을 크게 해서보기
- [x] Upload a photo 사진올리기
- [x] Edit the photo (Delete) 사진삭제하기 
- [x] See the feed 사용자는 인스타그램에 접속하면 피드를 보도록할것이다
피드는 어려우니까 마지막에
- [x] See rooms 내 room보기
- [ ] See room 이것은 모든 message를 다받는것
- [ ] send private Massage
- [ ] receive message (realtime)
