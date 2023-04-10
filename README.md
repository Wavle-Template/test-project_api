
# 테스트용 백엔드 서버
<br />
<br />

## deploy 결과
``` bash
[Deploy-Setting] setting project description to package.json 
[Deploy-Setting] setting project name to package.json 
[Deploy-Setting] 진행할 셋팅이 없습니다. 
```
## 추가적으로 수정 할 곳
- 회원탈퇴
apps/api/src/user/user.admin.resolver.ts#L93  
=> 탈퇴 가능여부 또는 탈퇴 후 처리
- 일라스틱 서치 셋팅 체크
- 소셜 키 셋팅 -> env파일
    - 애플
    - 카카오
    - 네이버
    - Toast
- 이메일
메일 전송이 필요할시      
