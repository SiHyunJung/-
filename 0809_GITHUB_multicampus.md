# GIT 이란?

Git이란 버전 관리 시스템(VCS, Version Control System) 여러 파일을 하나의 버전으로 묶어 관리하는 것으로 이런 파일들의 다양한 버전들을 전문적으로 관리하는 시스템이며, 깃은 여기에서 수정되고 업로드 되는 각각의 변경사항들을 "스냅샷'으로 저장하기 때문에, 어떤 버전으로도 되돌릴 수 있어 프로젝트에서 필수적으로 사용되어 지고 있다.



```bash
# Git/GitHub/프로젝트 관련 궁금한 점
깃허브에서 파일, 자료 등 깔끔하게 구조화하며 웹/앱으로 개발할 수 방법들이 궁금해요.
```



[ 210809_빅데이터 기반 지능형 서비스 개발.Notion](https://bit.ly/big-0809-notion)



## Markdown 문서 작성



## Git 버전관리





### Basic of Ver.



### Git branch



딥러닝 / 자연어 처리

YOLO

영상이 재생되면 객체를 바로 인식하는 

CCTV, 자율 주행자동차

BEPRO

실시간 분석이 가능한 

스포츠 중계, 





GUI : Graphic User Interface 윈도우는 대표적인 

* 그래픽을 통해 유저와 상호작용 하는 

* 인터페이스가 다르기 때문에 환경(행동)이 달라져야 합니다. 

  

CLI : COmmend Line Interface

* 명령, 줄  touch b.txt



![image-20210809133214515](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809133214515.png)





![image-20210809133247827](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809133247827.png)

modified - Working Directory

stage - Staging Area  (add)

committed -	git directory  (Repository)



![image-20210809133837975](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809133837975.png)

![image-20210809133858443](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809133858443.png)





![image-20210809134029742](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809134029742.png)



메시지를 숙지를 하고 있으면 읽는데 문제 없을 것

![image-20210809134115730](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809134115730.png)

하이픈  -     옵션 

git 최근 2개만 한줄로

.git 폴더에 모든 항목들이 저장되요.



텍스트 파일 작성한 것이 마음에 들지 않을 때, 되돌리는 명령어

git check out master 

상황 1. 보고서 - 발표자료 배경조사 

상황 2. 보고서 오타 수정 - 발표자료 슬라이드 배경 변경   A/B의 커밋을 나누는 것이 효율적



Staging Area  중간 공간에서 활용



git status

On branch master

#####  커밋이 될 변경사항들

##### Staging area에 있는 .. staged 상태의 파일들..

Change to be committed:

​		(use "git restore --staged <file> ..." to unstage)

​					deleted:	b.txt



##### staged(commit을 위한) 아닌 변경사항들

Change not staged for commit:





![image-20210809141108164](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809141108164.png)

![image-20210809141940686](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809141940686.png)

![image-20210809142721578](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809142721578.png)



![image-20210809144310091](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20210809144310091.png)





![image-20210809144754412](md-images/image-20210809144754412.png)





![image-20210809151034963](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809151034963.png)



# 원격 저장소 조회

$ git remote -v 		# verbose

origin  https://github.com/SiHyunJung/SiHyunJung.git (fetch)
origin  https://github.com/SiHyunJung/SiHyunJung.git (push)



# 원격 저장소 추가

$ git remote add <원격저장소 이름> <주소>

$ git remote add orgin http:

![image-20210809152042050](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809152042050.png)

![image-20210809151852325](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809151852325.png)





![image-20210809151652915](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809151652915.png)

* -u 옵션 : upstream 옵션

  * git push 라고 명령을 하더라도 설정된 원격저장소에 브랜치를 push

  * git push -u origin master

    



origin _ 여러개의 원격저장소의 이름을 'origin' 으로 



## 분산버전관리시스템(DVCS)

![image-20210809152819592](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809152819592.png)



git clone <원격저장소>

* 클론 : 원격저장소를 가지고 오는 텐서플로어가 개발된 모든 이력들을 불러 올 수 있다.



commit history

Q&A  버전컨트롤을 같이 진행 할 수 있을 거 같습니다. 그러면 커밋 메시지가 정말 중요한 것 같은데 만약에 커밋 메시지를 잘 못 썻다면 수정 하는 방법도 있나요?



[파이썬 PJT]     ------->

​					git. 원격 저장소 추가해줘    git lab

​																	origin

[데이터 분석 PJT]

[웹]



<-----

복수의 원격저장소를 하나의 원격저장소로 저장 할 수 없습니다.





![image-20210809153518132](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809153518132.png)



여러개의 원격 저장소가 있는 경우 :

![image-20210809153618051](C:/Users/LG/AppData/Roaming/Typora/typora-user-images/image-20210809153618051.png)



![image-20210809161702435](md-images/image-20210809161702435.png)







1. 목록1

   1. tab하면 하위 목록
   2. 엔터하면 계속

2.  Shift + tab 해주시면 상위목록이 됩니다.

   