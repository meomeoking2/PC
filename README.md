
# MiniProject
<div align="center">
<p align="center"><img src="https://media.istockphoto.com/id/1349390515/ko/%EC%82%AC%EC%A7%84/%ED%8E%98%EC%9D%B4%ED%8D%BC%EB%A6%AC%EC%8A%A4-%EC%A7%81%EC%9E%A5-%EC%95%84%EC%9D%B4%EB%94%94%EC%96%B4-%EC%A0%84%EC%9E%90-%EC%84%9C%EB%AA%85-%EC%A0%84%EC%9E%90-%EC%84%9C%EB%AA%85-%EB%AC%B8%EC%84%9C-%EA%B4%80%EB%A6%AC-%EC%82%AC%EC%97%85%EA%B0%80%EB%8A%94-%EC%8A%A4%ED%83%80%EC%9D%BC%EB%9F%AC%EC%8A%A4-%ED%8E%9C%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-%EA%B0%80%EC%83%81-%EB%85%B8%ED%8A%B8%EB%B6%81-%ED%99%94%EB%A9%B4%EC%9D%98-%EB%94%94%EC%A7%80%ED%84%B8-%EB%AC%B8%EC%84%9C%EC%97%90-%EC%A0%84%EC%9E%90-%EB%AC%B8%EC%84%9C%EC%97%90-%EC%84%9C%EB%AA%85%ED%95%A9%EB%8B%88%EB%8B%A4.jpg?s=1024x1024&w=is&k=20&c=HoqxH4Wsjb7CjijwJx96rPcJltYOiTHc8CnWQZgWlvg=" height="300px" width="300px"></p>

 ### Welcome, This is Han Manage
 <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
 <img src="https://img.shields.io/badge/C-00CCFF?style=flat-square&logo=C&logoColor="white"/>
 <img src="https://img.shields.io/badge/VisualStudioCode-0000FF?style=flat-square&logo=VisualStudioCode&logoColor="black"/>
 <img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=Markdown&logoColor="white"/>
                                                                                                            
 
</div>
  
## 🏢 Han Manage 주제
 - 한동대학교 학생들의 정보를 관리하는 프로그램 

<br/>

## 🏢 Han Manage에 대한 소개
  - 복잡한 학생 정보를 간편하게 관리해주는 Han Manage 입니다. 
  - 간단한 입력을 통하여 학생 정보를 정리해줍니다.
  - 학생 나이 정보를 바탕으로 팀을 꾸려줍니다.

<br/>
  
##  🏢 Han Manage가 가지고 있는 대략적인 기능 설명
  - 학생 정보 추가 기능
  - 학생 정보 수정 기능 
  - 학생 정보 삭제 기능
  - 학생 정보 검색 기능
  - 나이로 분류하여 랜덤으로 팀 설정

<br/>

## 🏢 Han Manage CRUD
> 코드 및 기능
```c
typedef struct{
    char name[20];
    int student_number;
    char gender[2];
    int age;
    char rc[20];
    char building[20];
    }student;
    // 구조체 
    
int selectMenu(); //메뉴 선택 함수

int add_the_stu(student *a,int n); //학생 정보 추가
void show_all_stu(student *a,int n); //학생 정보 조회
int update_the_stu(student *a, int n); //학생 정보 수정
int delete_the_stu( student *a,int n); //학생 장보 삭제

void find_by_name(student *a,int n); //학생 이름으로 정보 검색
void find_by_student_num(student *a,int n); //학생 학번으로 정보 검색
void find_by_age(student *a,int n); //학생 나이로 정보 검색
void find_by_rc(student *a,int n); //학생 RC로 정보 검색

void save_the_stu(student *a,int n); //학생 파일 저장
int load_the_stu(student *a, int n); //저장된 학생 정보 불러오기

void team_in_age(student *a,int n, int n1, int n2); //나이로 분류하여 팀 만들기

```

<br/>

## 🏢 개발환경 및 언어
  - git 
  - vs code

<br/>

## 🏢 팀소개 및 팀원이 맡은 역할
### 팀원
 #### 김수형 [ksh01p GITHUB LINK](https://github.com/ksh01p)
  - Repo Owner
  - 부가기능 구현
  - WIKI 관리
  - 코드 관리 (오류수정)

<br/>

#### 김민서 [meomeking2 GITHUB LINK](https://github.com/meomeoking2)
 - Contributer
 - CRUD 구현
 - 코드 관리 (오류수정)
