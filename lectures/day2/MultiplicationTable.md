# 구구단

|                                                            이미지                                                             |    이름    |             링크              |
| :---------------------------------------------------------------------------------------------------------------------------: | :--------: | :---------------------------: |
| <img src="https://user-images.githubusercontent.com/108293826/226612172-4298051c-43c1-4b0f-b926-f9414543afd1.png" width="100"> | MultiplicationTable | [MultiplicationTable 파일 바로가기](https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/tree/master/day2/MultiplicationTable) |

<br>

## 설계 목표

반복문의 개념을 이해한다. \
스크린이 이동하는 방법을 이해한다.

<br>

## 설명

1-9 중 원하는 단수를 입력하면, 다른 스크린에서 해당 단수를 출력한다.

<br>

## 이벤트

*Screen 1*

```
⏹ Button Event(1)
```

> **확인 버튼을 클릭했을 때** \
> 입력받은 텍스트값을 매개변수로 전달하고 Screen2를 연다. 

```
⏹ Button Event(2)
```

> **다시하기 버튼을 클릭했을 때** \
> Screen1으로 스크린을 이동한다.

*Screen 2*

```
📡 Sensor Event
```

> **Screen2가 초기화 되었을 때** \
> Screen1에서 받은 매개변수 숫자를 출력한다. 
> number 변수는 1-9까지 1씩 증가하며 반복문을 돌게 만든다. 
> Screen1에서 받은 매개변수와 반복문에서 초기화한 number를 곱하여 결과값을 출력한다.
<br>

## 소스 

|    FileName    | Description  | Extenstion |
| :------------: | :----------: | :--------: |
| BackScreen.jpg  |  스크린 뒷배경   |    jpg     |

<br>

## 멘토

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day2/MultiplicationTable/Mentor_MultiplicationTable.aia

<br>

## 멘티

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day2/MultiplicationTable/Menti_MultiplicationTable.aia

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day2/MultiplicationTable/Menti_MultiplicationTable_onlyDesigner.aia
