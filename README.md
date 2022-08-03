# nodemailer

> 메일을 송수신하기 위해 nodemailer 모듈을 학습합니다.
>
> 추후에 smart-green-campus 레퍼지토리에 적용하기 위한 연습 과정입니다.

<br/>

### 세팅
```bash
$ Express [프로젝트 이름]
$ npm i
$ npm i nodemailer
```

<br/>

보안을 위해 config/senderinfo.json 을 .gitignore에 추가하였습니다.
- senderInfo.json 의 내용은 아래와 같습니다.
```json
{
  "user": "본인의 이메일",
  "pass": "이메일 비밀번호"
}
```