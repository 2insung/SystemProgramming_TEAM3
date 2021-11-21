# SystemProgramming_TEAM3

## 시스템프로그래밍 팀프로젝트 3조

> Github Repo
> 

[https://github.com/2insung/SystemProgramming_TEAM3.git](https://github.com/2insung/SystemProgramming_TEAM3.git)

## 참가자

```
PM: 정인준
아키텍트: 박경모
개발자: 박경모, 이인성, 윤서영, 정인준, 최준호 , 권혁원
운영자: 이인성, 윤서영

```

## Github 사용법

1. Git 설치 [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Git bash 나 Git CMD 사용
3. Git Clone -> 자신이 작업하고 싶은 폴더를 만들어서 cmd로 cd {폴더} 후 명령어 입력

```
->자신의 작업 폴더를 정하고 repo 내려받기, 처음 세팅할 때만 입력

$git clone <https://github.com/2insung/SystemProgramming_TEAM3.git>
```

![https://user-images.githubusercontent.com/84179188/142755918-b1ee59d7-b5bd-4295-b056-93ada21a38b8.png](https://user-images.githubusercontent.com/84179188/142755918-b1ee59d7-b5bd-4295-b056-93ada21a38b8.png)

1. branch 설정

```
##clone한 폴더 안에 .git 폴더가 존재하는 폴더(SystemProgramming_TEAM3) 로 다시 cd 이후에 작업
git branch   --> 현재 branch들 보기

->본인 branch 만들기. 이 branch로 push/pull 작업 수행
git branch {하고 싶은 이름}

->본인 branch로 상태 변경
git checkout {자신의 branch name}
```

![https://user-images.githubusercontent.com/84179188/142755956-61187d1e-dfe0-441e-b8ab-962d67adc480.png](https://user-images.githubusercontent.com/84179188/142755956-61187d1e-dfe0-441e-b8ab-962d67adc480.png)

1. 수정 후 올릴 때

```
1. 수정 사항 변경 (일부만)

git add {파일}                  // 여러 파일 가능-> git add {파일} {파일}
git commit -m {"text"}         // text에는 아무 말이나 쓰는 것 가능
git push origin {branch name} //본인 branch name 으로..
```

![본인 작업 환경에서 수정](https://user-images.githubusercontent.com/84179188/142756128-f82d0016-68da-4d83-9aac-d68f52327dc0.png)

본인 작업 환경에서 수정

![변경 명령어](https://user-images.githubusercontent.com/84179188/142756135-31233d07-742d-4793-aad0-c834491ce6ec.png)

변경 명령어

![깃허브에 반영된 모습](https://user-images.githubusercontent.com/84179188/142756122-b27bcbc5-c780-44c4-8217-7d4784a61876.png)

깃허브에 반영된 모습

![a.html 을 삭제하고 b.js를 추가한 모습](https://user-images.githubusercontent.com/84179188/142756198-415712c6-8da7-437d-8577-8d674360c7be.png)

a.html 을 삭제하고 b.js를 추가한 모습

![변경 명령어 (파일 2개 add)](https://user-images.githubusercontent.com/84179188/142756208-fafc505b-d81b-4410-8f32-51dd25520669.png)

변경 명령어 (파일 2개 add)

![깃허브에 반영된 모습](https://user-images.githubusercontent.com/84179188/142756182-e41c30c9-40a2-4108-ae0b-c0c146967e3e.png)

깃허브에 반영된 모습

```
2. 수정 사항 전부 변경할 때

git add .     //add . 사용시 수정사항 전부 반영 -> 파일 삭제된 것까지 반영함
git commit -m {"text"}
git push origin {branch name}
```

![변경한 파일이 여러 개일 때](https://user-images.githubusercontent.com/84179188/142756289-3b7e7d11-fe47-4030-8dd9-9aba71a2a503.png)

변경한 파일이 여러 개일 때

![변경 명령어](https://user-images.githubusercontent.com/84179188/142756296-0407d45c-47bd-4531-9aa6-838ee000c3f0.png)

변경 명령어

![깃허브에 반영된 모습](https://user-images.githubusercontent.com/84179188/142756278-72efa7dc-6c52-4278-be94-358686319736.png)

깃허브에 반영된 모습

- main을 내 branch로 받을 때

```
git pull origin main  // 본인 branch인 상태에서 명령어
```

![현재 pull.c 가 추가된 상황이지만,](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c4ff4df-fb90-481d-aacc-efc54ad86f8a/Untitled.png)

현재 pull.c 가 추가된 상황이지만,

![내 작업 공간에서는 설정이 되지 않은 상태.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/76f5da64-c460-4cb6-8a7e-e880d3ee80fc/Untitled.png)

내 작업 공간에서는 설정이 되지 않은 상태.

![git pull origin main / main branch에 있는 내용 내 작업 공간으로 내려받기](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e0703089-a964-4a69-974f-8ff0353d2c6a/Untitled.png)

git pull origin main / main branch에 있는 내용 내 작업 공간으로 내려받기

![작업 공간에 pull.c 가 추가된 모습](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f0687a29-8d62-4d88-9335-4f4cf69a9304/Untitled.png)

작업 공간에 pull.c 가 추가된 모습

- 병합 요청하기 / 수정 사항 반영하는 법
1. 깃허브 들어가기

[https://github.com/2insung/SystemProgramming_TEAM3](https://github.com/2insung/SystemProgramming_TEAM3)

1. 코드 수정 후 push 했다면 pull request 들어가기

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/84b04101-286c-4a53-9095-0a4a924ee059/Untitled.png)

1. New pull request 클릭 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dfffeb6d-8a0d-431f-a5b1-81560218a5c0/Untitled.png)

1. 이후 본인 branch에 들어가기

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5f833d03-01a3-40d4-85b5-b383649fc8bd/Untitled.png)

1. Create pull request 클릭 후 코멘트는 선택 →  Create pull request!

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/191fc2a5-482f-411b-b9fe-a094f6b33d62/Untitled.png)

1. merge 과정 기다리고 merge pull request 클릭 → confirm 하기

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a8194659-27f6-4545-b2a7-50aac3e33216/Untitled.png)

1. merge 확인 후 적용된 것 확인

![앞에서 했던 파일들 다 삭제한거에요](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/491e943a-7f78-4677-ab1b-2ff3f8193def/Untitled.png)

앞에서 했던 파일들 다 삭제한거에요
