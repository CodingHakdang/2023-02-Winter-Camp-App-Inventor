# 두더지 잡기 게임

|                                                            이미지                                                             |    이름    |             링크              |
| :---------------------------------------------------------------------------------------------------------------------------: | :--------: | :---------------------------: |
| <img src="https://user-images.githubusercontent.com/110290146/222441364-9a8d40a1-2200-41ee-accf-bc93963ecc92.png" width="100"> | CatchMole | [CatchMole 파일 바로가기](https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/tree/master/day3/CatchMole) |

<br>

## 설계 목표

함수 이용 방법을 학습한다. \
게임 내 제한시간 적용법을 학습한다.

<br>

## 설명 

화면을 터치하여 두더지를 잡는 게임

<br>

## 이벤트 

*Screen 1*

```
⏹ Button Event(1)
```

> **다시하기 버튼을 클릭했을 때** \
> 점수 및 타이머를 초기화한다.

> **두더지를 터치했을 때** \
> 잡기성공 점수가 1 증가한다.

> **배경을 터치했을 때** \
> 잡기실패 점수가 1 증가한다.

```
📡 Sensor Event(1)
```
> **타이머가 작동할 때** \
> 두더지가 랜덤 위치로 이동한다.

> **타이머가 0일 때** \
> Screen 2 로 이동한다. \
> 점수를 Screen 2 로 전달한다.

*Screen 2*

```
📡 Sensor Event(2)
```

> **Screen 2 가 초기화되었을 때** \
> 점수를 화면에 표시한다.

```
⏹ Button Event(2)
```

> **다시하기 버튼을 클릭했을 때**\
> Screen 1 로 이동한다.

<br>

## 소스 파일 

|         FileName        | Description | Extenstion |
|    :----------------:   | :---------: | :--------: |
| CatchMoleBackground.png |     배경    |    png     |
|         Mole.png        |    두더지   |    png     |


<br>

## 멘토 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/CatchMole/Mento_CatchMole.aia

<br>

## 멘티 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/CatchMole/Menti_CatchMole.aia
