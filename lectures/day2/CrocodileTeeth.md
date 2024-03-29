# 악어이빨 게임

|                                                            이미지                                                             |    이름    |             링크              |
| :---------------------------------------------------------------------------------------------------------------------------: | :--------: | :---------------------------: |
| <img src="https://user-images.githubusercontent.com/108293826/222973631-7ef6339c-5b8c-44fe-8c6e-f121ce9b9b4f.png" width="100"> | CrocodileTeeth | [CrocodileTeeth 파일 바로가기](https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/tree/master/day2/CrocodileTeeth) |

<br>

## 설계 목표

변수 & 랜덤 블록을 활용하여 악어이빨 게임을 만들 수 있다. 

<br>

## 설명 

컴퓨터가 1-10까지의 수 중 임의의 숫자를 선택하고, 사용자가 그 숫자버튼을 누르면 악어입이 닫히며 게임이 종료된다.

<br>

## 이벤트 

*Screen 1*

```
⏹ Button Event(1)
```

> **이빨 버튼을 클릭했을 때** \
> 만약 썩은 이빨이라면 스크린을 이동한다. 
> 만약 썩은 이빨이 아니라면 해당 버튼을 비활성화, 글씨 색상, 크기를 변경한다. 

```
⏹ Button Event(2)
```

> **다시하기 버튼을 눌렀을 때** \
> 스크린을 닫고 Screen1을 새로 화면에 띄운다.

```
📡 Sensor Event(1)
```

> **전역변수 설정** \
> 임의의 1-10의 전역변수를 설정한다.

```
📡 Sensor Event(2)
```

> **전역변수 값이 같을 때** \
> 버튼의 번호와 전역변수의 값이 같을 경우, 스크린을 이동하여 Screen2를 화면에 띄운다.

*Screen 2*

```
📡 Sensor Event(3)
```

> **전역변수의 값이 같을 때** \
> 버튼의 번호와 전역변수의 값이 같을 경우, 스크린을 이동하여 Screen2를 화면에 띄운다. 
<br>

## 소스 파일 

|    FileName    | Description  | Extenstion |
| :------------: | :----------: | :--------: |
| IconCrocodile.png  |  앱 아이콘   |    png     |
|    UpTeeth.png    |  위 이빨   |    png     |
|    DownTeeth.png    |   아래 이빨    |    png     |
|  FirstScreen.png  | 첫 번째 스크린 배경 |    png     |
| FinalScreen.png  |      마지막 스크린 배경      |    png     |

<br>

## 멘토 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day2/CrocodileTeeth/Mentor_CrocodileTeeth.aia

<br>

## 멘티 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day2/CrocodileTeeth/Menti_CrocodileTeeth.aia
