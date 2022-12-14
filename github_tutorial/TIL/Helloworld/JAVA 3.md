## 1-2 JAVA (수정 전)


# C는 하드웨어에 메모리나 JVM을 돌릴 환경이 안됨.

특징

웹, 안드로이드, PC APP. 모든 운영체제에서 실행 가능.

객체 지향 프로그래밍 (OOP : Object-Oriented Programming)

메모리 자동 정리. 풍부한 무료 라이센스. 다양한 라이브러리


자바 개발 도구 (JDK: Java Development Kit)

Open JDK < Oracle JDK (안정성) LTS(Long Term Support)


JAVA 8 ver

2020-06 R | Eclipse Packages

전자정부프레임워크가 Eclipse로 개발되어있기 때문에 사용.



대표사진 삭제
사진 설명을 입력하세요.



대표사진 삭제
사용자 변수- 디렉토리 // 시스템 변수 PATH 디렉토리\bin

CMD -> javac -version


JAVA 문법 10일 객체 지향 5일 게임 RPG 개인 게임 프로젝트

오라클 DB 연동 , 팀프로젝트 3~4인.


EclipseJava- Workspace[ D:\A_TeachingMaterial\01_BasicJava\workspace]


Preferences- Search[ encoding <General-Workspace- Text file encoding- Other - UTF-8- Apply

Content Types - UTF-8 ( Update All, Text 세부 확인)

Web- CSS Files, HTML Files , JSP Files, XML- XML files 전부 UTF-8 Apply.

JAVA-installed JREs- 앞선 환경변수 설정 제대로 되어있으면 알아서 적용되어있습니다.


자바는 대,소문자 구분함.

오른쪽 상단 JAVA EE 웹용, JAVA 개발용. 딱히 상관은 없음.

src-ctrl+n

Java Class- public static void main check

Task list (해야할 목록. 잘 안 씀.)

Outline 패키지 구조 확인

Problems 오류


java Explorer -> alt+enter -> location icon

다른 환경에서 개발환경을 그대로 쓰고 싶으면 .metadata를 옮겨라.

.settings 날아가면 안됨.

.classpath ) 고유한 것.

.project )

저장하는 순간 자바 파일을 .class 파일로 변환.

코딩 스페이스 빨간 줄-> 이클립스에서 관측한 에러.

problems error -> 자바 컴파일러.

.java는 소스파일

.class 변환 완료 파일.


class 앞 대문자

package 앞 소문자.

메소드 - 클래스에서 작동하는 동작/기능을 의미.

한줄 주석 ctrl+shift c 범위 주석 : ctrl+shift +/ (해제 \) /* */ /* 사이에 엔터를 치면 계속 범위 주석이 됨.

정수 : 음양 정수.

실수 : 소수점

문자 : 'a' , '3', '가' ,

논리 : true, false

문자열 : "가나다"


프로그래밍 언어의 기준으로 데이터의 종류를 나눠 놓은 것 : 자료형 (data type)

기본형 타입 (괄호 안에는 자료형의 크기)

정수 byte(1) short (2) int (4) long (8)

실수 float(4) double (8)

문자 char(2)

논리 boolean(1)


변수 : 하나의 데이터를 담을 수 있는 그릇

변수를 만들때 타입을 사용한다.

데이터를 다룰 때 일반적으로 변수라는 그릇에 담아서 사용한다.


자바는 선언형 언어. 미리 변수에 대한 것이든 선언을 해야한다. Ex) int age;

한 블럭 안에서 변수명은 중복될 수 없다. { }

변수명은 무조건 소문자 시작. 예외는 변수에 한해서는 없음.

문자를 이어서 변수를 쓰려면 _ (뱀표기법) 혹은 대문자(낙타표기법) 사용.

오류가 왼쪽에서 났는지 오른쪽에서 났는지 확인.

초기화 : 변수에 처음으로 값을 입력함. 변수에 맞는 타입으로 입력.


int abc = 20 ; 선언과 동시에 초기화

long l = 40L; 보통 L을 붙인다. 해야 long 타입이 된다.

float f = 5.5f;

char c = '한'; 한글자만

boolean b = true; // true,false


0열 선택0열 다음에 열 추가
1열 선택1열 다음에 열 추가
2열 선택2열 다음에 열 추가
0행 선택0행 다음에 행 추가
1행 선택1행 다음에 행 추가
2행 선택2행 다음에 행 추가
3행 선택3행 다음에 행 추가
4행 선택4행 다음에 행 추가
5행 선택5행 다음에 행 추가
6행 선택6행 다음에 행 추가
셀 전체 선택
열 너비 조절
행 높이 조절
byte

1바이트

-128 ~ 127

short

2바이트

-215 ~ (215 - 1)

-32,768 ~ 32,767

int

4바이트

-231 ~ (231 - 1)

-2,147,483,648 ~ 2,147,483,647

long

8바이트

-263 ~ (263 - 1)

-9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807

셀 병합
행 분할
열 분할
너비 맞춤
삭제
형변환

int small = 10;

long big = 10L;

small = big; 작은 그릇에 큰 것을 담을 수 없다.

big = small; 표현 범위가 작은 쪽에서 큰 쪽으로 형 변환은 생략 가능.


명명 규칙

영문자 대소문자, 한글 , 숫자, 특수만자 (_, $)를 사용할 수 있다.

숫자로 시작 X

예약어는 사용 불가. int, double 같은 기존의 명명어 불가능. 사용하고 싶다면 vInt 이런 식으로.


상수 : 값이 변하지 않음. 리터럴에 의미를 부여하기 위해 사용한다.

final int MAX_NUMBER;

MAX_NUMBER = 10;

상수명은 대문자를 사용한다.


출력

System.out.print(); 줄바꿈 x println 줄 바꿈

\n 역슬래시 다음에 나오는 글자는 글자가 아니다. 기능.

\t 띄어쓰기 4번 콘솔에선 8번으로 칩니다. 콘솔은 탭에서 기존 것을 계산해서 쓰는데...콘솔에서 이쁘게 띄우기 어렵다.


System.out.println("나이 : " + age ) ; 두 개가 합쳐지면서 문자열이 됩니다.

printf() 출력 포멧을 지정한다.

ctrl+space 툴팁.

Random 난수를 쓰지 않고 Scanner처럼 따로 사용한다. (보안문제)

for문을 두 개 돌리는 것을 잘 활용하면 그림 그리기 좋다.

글자의 비교를 위해 사용하는 메소드.

String str1 = sc.nextLine();

boolean bl = str1.equals("aaa");
