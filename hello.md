#hello git

#git 명령어 요약

- clone : 원격저장소 복사
- add : 스테이지 영역에 작업 파일 추가
- commit : 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)를 만들 수 있다.
- push : 원격 저장소에 커밋을 올릴 수 있다.

#코드뭉치 버리기를 하면 올린 파일로 돌아갈 수 있다궁!


브랜치 어렵다

내가 할 거 그거 아니었음

## 브랜치 변경하기

- 브랜치란 : 기존 내용을 유지한채로 새로운 내용을 추가하고 싶을 때 사용한다.
- 체크아웃 : 특정 브랜치 (혹은 커밋) 으로 돌아가고 싶을 때 사용.
- 소스트리 체크아웃 : 브랜치 이름을 더블 클릭하는 것만으로 체크아웃 가능

## 병합학시1

- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로부터 시작된 경우
- 아주 쉽게 병합가능 = fast forward

## 병합하기 2
- 헤드 브랜치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 안 나면 좋은데, 나도 겁내지 말자.

## 충돌 해결하기
- most important is do not afraid!

## 소스트리는 초기화가 됐느냐!

## = failed

## reset 사용하기

- pro: easy
- cons: remove & cannot come back

# using branch for return
pro : easy
    : good for save information
cons : dirty

## revert
- 단점 : 충돌 가능
 
 ## etc commit

 # stash

 # 주석 너무 많이 금지
 # 커밋 메세지 잘  달자
