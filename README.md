# 1and2studytTotal
1,2 organize


-----------------------------------------------//////////////////

-인생 언리얼 1권 정리

리얼타임 엔진 = 게임 엔진

컴포넌트
   ↓
 액터
   ↓
 레벨 
(개발순서)
 
프로젝트 = [레벨, 레벨, 레벨]
[레벨] = [액터,액터,액터]
[액터] = [컴포넌트, 컴포넌트, 컴포넌트]

프로젝트[레벨[액터[컴포넌트]]]

액터 xyz 이동 = 기즈모 = 레벨 화면상에서 이동 시킬 수 있는 트랜스폼컴포넌트를 포함하는 모든 액터 변경 수단(회전,크기)
월드 좌표계 로컬 좌표계 변경해서 기즈모 변경 가능
snap = 기준에 맞게 이동(1,10,50,100)

지오메트리 브러시액터 
ㄴ점(Vertex), 선(Edge), 면(Face)

브러시액터(형태 변형 무제한적) , <=> 기본 액터(형태 변형 제한적)

unreal은 cm 단위

Brush type -> Subtractive - > 구멍내기 

--------------/////////////////////


TPP CPP

# TPSCPP2
TPSCPP2
----2.13 오후수업다시ㅏ시작

네비게이션 ㄱ

ai도 포제스 가능 

헤더가 안돼면 포인터, 유프로퍼티 써써 새로 만들어

길찾기 필수요소(pathFinding)
1. 길이 있어야한다(NavMeshBoundVolum)
2. 길 위에서 목적지를 향해 이동할 주체가 있어야한다 (AIController)
3.이동하려면 _> characterMovenmentComponent


순찰 Partrol
추적 chase

NavigationInvoker  네비게이션 다이내믹 하면 요거추가해야함
플레이중 ' 누르면 네비 정보 뜸

sync랑 async랑 다름

-----------------
02.15
EnhancedInput
버튼 bool
이동 xy 
ㄴinput값

class 앞에 붙이면 전방선언 해응

ㅅㅂ 왜 안됌

----------------02016

델리게이트 : 대리자
변수의 형식을 가진다.
담을 수 있는 값 = 함수의 주소
ㄴ  변수인데 함수의 주소를 담고있을수도있따?

델리게이트에 함수를 몇 개 담느냐에 따라 한 개만
또는 여러개
 ㄴ 블루프린츠에서 사용할수있는가>?

nine 까지 가능 

지시자?

델리게이트 어려웡

미니맵 -끝



/-----------------------...........................///////////////////////////////////////////////////////

game

1.31 https://github.com/Squid5O/game

https://nbcamp.spartacodingclub.kr/blog/%ED%98%84%EC%A7%81-%EA%B2%8C%EC%9E%84-%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-%EB%93%A4%EB%A0%A4%EC%A3%BC%EB%8A%94-%EA%B2%8C%EC%9E%84-%EA%B0%9C%EB%B0%9C%EC%9D%98-%EB%AA%A8%EB%93%A0-%EA%B2%83-1447

ㄴ 1인 개발로 제작된 고양이 스프라는 게임은 네오위즈에 200억에 인수 ( 5000만 다운로드) https://m.khan.co.kr/it/game/article/202111172045005

C++ 정리

-------------2.01

포인터
Class 유형의 안전성을 보장해 주는 템플릿 클래스 -- TSubclassOf<class AㅁㅁActor>




//////////////////--//////////////////////////-------------------------------------------------------------------------------------------------------------------


# FindingJob
일찾기
--------
사람인 _ 카카오
잡코리아 _카카오
게임잡 _ 카카오
원티드 _ 카카오
점핏 - 구글
리멤버 -구글
로켓펀치-구글
캣치-카카오
잡플랙스-카카오 
잡플래닛 -카카오
인쿠르트-카카오
링크드인-구글

//
Unreal 
C
C++
C#
영어
3D sass editer
서버 연동
UMG/slate
블루프린트/ C++
OPP 
cS 
python
그래픽스
클라이언트
VR/AR 디바이스
웹기반게임 서버소켓통신
해외(영어)
서드파티 툴
픽셀 스트리밍
자료구조,알고리즘

//
[포트폴리오]
- 개발한 콘텐츠에 대한 동영상
- 개발한 코드의 구조와 로직의 설명이 포함된 문서 

블렌더?

리얼타임 컨텐츠 

네트워크 컨텐츠

게임 서버 아키텍처

VR 언리얼 엔진 
게임로직과 서버간의 통신 개발 및 보안 
VR,AR.MR
webXR, openXP
,클라우드 서버 기반 아키텍처 경험 
머신러닝

//

[게임클라이언트]
컴퓨터 그래픽, directX/openGL 그래픽스API, 컴공,

[게임서버]
DB, 컴공

------------------------------------------------------------------------------------------------------------------
1.15



https://www.saramin.co.kr/zf_user/jobs/relay/view?isMypage=no&rec_idx=47316971&recommend_ids=eJxFkMsRw0AIQ6vJXfwk9pxC3H8XwRmv9%2FhGoMeQchMyrjZ%2B9M3oDO%2B4FvxGKMyASXFjVpWpB3WjfEG0jSBk4K6i0FOwdwULa7y7AUasjcRA5%2FZyVD7pg7JVc8cM2%2BMtHq%2FC2ciTZoz6TcHy5S9aJeOc4aUSD847rE5zFftf9QM3GUAq&view_type=search&searchword=%EC%96%B8%EB%A6%AC%EC%96%BC&searchType=search&gz=1&t_ref_content=generic&t_ref=search&paid_fl=n&search_uuid=5ffd9c65-bccb-4b4a-a993-62b349125459&immediately_apply_layer_open=n#seq=0
-

////////////////////////////////////////---------------------------------//////////////////////////////////////////////////////






리얼타임 엔진 = 게임 엔진

컴포넌트
   ↓
 액터
   ↓
 레벨 
(개발순서)
 
프로젝트 = [레벨, 레벨, 레벨]
[레벨] = [액터,액터,액터]
[액터] = [컴포넌트, 컴포넌트, 컴포넌트]

프로젝트[레벨[액터[컴포넌트]]]

액터 xyz 이동 = 기즈모 = 레벨 화면상에서 이동 시킬 수 있는 트랜스폼컴포넌트를 포함하는 모든 액터 변경 수단(회전,크기)
월드 좌표계 로컬 좌표계 변경해서 기즈모 변경 가능
snap = 기준에 맞게 이동(1,10,50,100)

지오메트리 브러시액터 
ㄴ점(Vertex), 선(Edge), 면(Face)

브러시액터(형태 변형 무제한적) , <=> 기본 액터(형태 변형 제한적)

unreal은 cm 단위

Brush type -> Subtractive - > 구멍내기 

