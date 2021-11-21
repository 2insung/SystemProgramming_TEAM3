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

$git clone https://github.com/2insung/SystemProgramming_TEAM3.git

```
![image](https://user-images.githubusercontent.com/84179188/142755918-b1ee59d7-b5bd-4295-b056-93ada21a38b8.png)


4. branch 설정

```
##clone한 폴더 안에 .git 폴더가 존재하는 폴더(SystemProgramming_TEAM3) 로 다시 cd 이후에 작업
git branch   --> 현재 branch들 보기

->본인 branch 만들기. 이 branch로 push/pull 작업 수행
git branch {하고 싶은 이름} 

```

```
->본인 branch로 상태 변경 
git checkout {자신의 branch name}

```
![image](https://user-images.githubusercontent.com/84179188/142755956-61187d1e-dfe0-441e-b8ab-962d67adc480.png)



5. 수정 후 올릴 때

```
1. 수정 사항 변경 (일부만)

git add {파일}         
git commit -m {"text"}
git push origin {branch name}

```
![image](https://user-images.githubusercontent.com/84179188/142756128-f82d0016-68da-4d83-9aac-d68f52327dc0.png)

![image](https://user-images.githubusercontent.com/84179188/142756135-31233d07-742d-4793-aad0-c834491ce6ec.png)

![image](https://user-images.githubusercontent.com/84179188/142756122-b27bcbc5-c780-44c4-8217-7d4784a61876.png)


![image](https://user-images.githubusercontent.com/84179188/142756198-415712c6-8da7-437d-8577-8d674360c7be.png)

![image](https://user-images.githubusercontent.com/84179188/142756208-fafc505b-d81b-4410-8f32-51dd25520669.png)


![image](https://user-images.githubusercontent.com/84179188/142756182-e41c30c9-40a2-4108-ae0b-c0c146967e3e.png)


```
1. 수정 사항 전부 변경할 때

git add .     //add . 사용시 수정사항 전부 반영 -> 파일 삭제된 것까지 반영함
git commit -m {"text"}
git push origin {branch name}

```



- main을 내 branch로 받을 때

```
git pull origin {main branch}

```

- 병합 요청하기

[github.com](http://github.com/) → repository → pull request → new pull request → ...
