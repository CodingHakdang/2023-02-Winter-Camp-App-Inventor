# 슈팅 게임

|                                                            이미지                                                             |    이름    |             링크              |
| :---------------------------------------------------------------------------------------------------------------------------: | :--------: | :---------------------------: |
| <img src="https://user-images.githubusercontent.com/110290146/222441652-b235d845-a2a3-41ed-ac2c-2d536dfd1445.png" width="100"> | ShootingGame | [ShootingGame 파일 바로가기](https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/tree/master/day3/ShootingGame) |

<br>

## 설계 목표

다중 함수 이용 방법을 학습한다. \
게임 내 점수 증감 적용법을 학습한다.

<br>

## 설명 

로켓을 움직여 외계인을 공격하는 게임

<br>

## 이벤트 

*Screen 1*

```
⏹ Button Event(1)
```

> **게임시작 버튼을 클릭했을 때** \
> Screen 2 로 이동한다.

> **종료하기 버튼을 클릭했을 때** \
> 앱을 종료한다.

```
📡 Sensor Event(1)
```

> **Screen 1 이 초기화되었을 때** \
> 점수를 화면에 표시한다.

*Screen 2*

```
📡 Sensor Event(2)
```

> **게임시간 타이머가 작동할 때** \
> 미사일을 1초 간격으로 자동 발사한다.

> **게임시간 타이머가 0일 때** \
> Screen 1 로 이동한다. \
> 점수를 Screen 1 로 전달한다.

```
⏹ Button Event(2)
```
> **로켓을 드래그했을 때** \
> 로켓이 수평으로 이동한다.

> **미사일이 행성과 충돌하면** \
> 점수가 5 감소한다.

> **미사일이 외계인과 충돌하면** \
> 점수가 5 증가한다. \
> 외계인의 위치를 변경한다.

<br>

## 소스 파일 

|       FileName      |  Description | Extenstion |
|  :----------------: |  :---------: | :--------: |
|  ShootingStart.jpg  | 게임시작 배경 |    jpg     |
| ShootingPlaying.jpg |  게임중 배경  |    jpg     |
|       UFO.png       |      UFO     |    png     |
|      Planet.png     |     행성     |    png     |
|      Rocket.png     |     로켓     |    png     |

<br>

## 멘토 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/ShootingGame/Mentor_ShootingGame.aia

<br>

## 멘티 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/ShootingGame/Menti_ShootingGame.aia
