


command shift y - debug창 키

command shift l - lib창 키

ctrl option command enter - assistant

navigaion pane

document outline

debug area

library

editor options

top status bar

attributes

size

inspector

assistant

bounds rectangle check

inspector pane

---
---

horizontally in container

vertically in container

---


view controller

``` swift
@IBOutlet weak var mainLabel:UILabel!


connection - action
type

@IBAction func buttonPressed(_ sender: UIButton)

mainLabel.textAlignment = NSTextAlignment.right


```
ui를 코드로 드래그 해서 코드 추가


---

### 스토리 보드 구조

- 코드 -> @iboutlet -> 스토리보드 -> ui lebel ->
    1. interface builder(뷰-객체)와 연결된 outlet

- 스토리보드 -> @ibaction -> 코드 func bu..tap(..uibutton){}
    1. interface builder(뷰-객체)와 연결된 action
 
override func viewDidLoad

---

2개 연결되었을경우 하나는 무조건 끊어주기.

그냥 코드 적기

myButton.setTitleColor(UIColor.black, for: UIControl.State.normal)

### 스토리 보드 코드 연결


변수 지정해서 접근
``` swift
class VC:UIViewC.. {
var my_Label: UILabel!
var button:UIButton!

func bu..tap(..uibutton){
my button.color..
}
```

---

### ios arc / framework

- 프레임워크 - 개발자 이밎짜여진 룰 따라 작업
- 라이브러리 - 미리 만들어 놓은 필요 부분 사용

### Foundation 

기본적 swift언어
foundation framwork


### 4 layer 
1. cocoa touch framework
   1.  unkit/addressbookui/eventkitui/gamekit/mapkit/notificationcenter ...

- uikit
  1. 사용자 상호작용
  2. 카메라 /디바이스api
  3. 뷰/윈도우관리/시스템뷰 뷰컨트롤러
  4. 프린트/pdf변환api
  5. ui에니메
 
- addressbookui - 주소록
- eventitui - 달력, 일정
- gamekit
- mapkit - 앱 추가 지도
- notificationcenter


2. media framework
   1. assetslibrary/photos/coregraphics/avfoundation ...

- 사진 동영상관련
- coregraphocs - 2d 화면 그리기
- avfoundation - 오디오, 비디오 재생
   
3. core services framework
   1. foundation/webkit/cloudkit/corelocation/storekit ...
- 문자열/ 날짜처리
- 런루프/gcd/쓰레드/url

- webkit
- cloudkit
- corelocation
- storekit
  
4. core os framework
   1. corebluetooth/externalaccessory/localauthentication ...

- corebluetooth
- localauthentication
- security
   
  


---
