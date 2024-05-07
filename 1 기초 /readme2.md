### 전체 오타 확인 하기.


### 주사위 게임

label select후 alignment 해서 중앙정렬

- -> enbede in view, stack view, => 여러 객체 병합
- spacing, -> 두개 사이의 간격

fill equally -> 해당 하는 영역 비율 표시

가로 위치 잡아주기. 20, 20


img view를 선택 -> select 해서 ctrl

- aspect ratio
- multipiler 1:1 비율로 설정





---
---




image 를 assets xcassests폴더 안에 이동

command + b 로 빌딩

image view - image select 

image view ctrl로 누른 상태에서 끌어다 넣기

var dicarray : [uiimage] = [#imageliter()] ->하면 이미지 뜸

image literal 눌러서 이미지 추가

command + r 눌러서 실행

FirstImageView.image = diceArray.randomElement()
- randome element를 사용해서 랜덤한 array가 나올 수 있게

---
---

### 디자인

1. lebel, imageview, labe 생성
2. stack view로 통합
3. alignment fill
4. 스페싱 15

6. 맨위 label, 맨아래 label / height 30 설정
7. ctrl해서 비율 설정 aspect ratio
8. 이미지 1:1 안되면 view들어가서 설정

9. 옵션 눌러서 객체 복사

10. 두 객체 stack view 통합
11. 가장 큰 stack 스페싱 15
12. 버튼 생성 백그라운드, 폰트컬러, 폰트 크기 수정 후 복사해서 3개 만들기

13. 3개 스택뷰 넣기
14. 스페싱 10
15. distribution 10

16. shift command l 눌러서 버튼 추가
17. reset 버튼 예쁘게 꾸미기

18. reset 버튼 복사해서 맨 밑에 복사 버튼 2개 만들기

19. stack view 로 묶기
20. 스페싱 10정도 주기
21. , 밑오늘쪽 밑에 add new contraints 에 맨 위 라벨 width 100, height 35 / height 에 80추가


22. 그 후 밑 오른쪽 2번째꺼 horizontraincontainer 선택
23. 마지막으로 text 가운데 정렬

24. 큰 스택뷰도 110/20/20
25. 각 큰 스택 안에 있는 label text 가운데 정렬

26. 이제 밑에 있는 버튼 3개부터 40/20/20으로 크기 설정

27. 버튼 3개중 한개 클릭후  ctrl을 이용해서 aspect ratio / 오른쪽 위 오른쪽에서 왼쪽으로 2번째 클릭후 aspect ratio 더블클릭 1:1로 변경

28. 버튼 클자 수정

29. 맨 밑 버튼 20/20/20 height 45



---

1. stack view 에서 110 맨위에 있는걸 길이 수정. constant 50으로 수정
2. 이미지 넣고 command + b 누르기

3. 


### 내부로직

매인 라벨

이미지 뷰 2개

이미지 뷰 에따른 결과 출력 라벨

액션

- @IBAction func rpsButtonTapped(_ sender: UIButton){}
- 에서 버튼 3개를 연결

reset button

select button

---
---

UIImage(named: "ready.png")
comChiceLabel.text = "준비"

- Rps.swift 생성, enum으로

- Rps.papper


``` swift

// guard let title = sender.currentTile else{return}


let title = sender.currentTitle!
print(title)




```












