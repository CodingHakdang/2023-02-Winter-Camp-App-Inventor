# 도네이션 앱

|                                                            이미지                                                             |   이름    |        링크        |
| :---------------------------------------------------------------------------------------------------------------------------: | :-------: | :----------------: |
| <img src="https://user-images.githubusercontent.com/110290146/222435729-aeb23e06-dbfe-453a-adff-62ff4b65095e.png" width="100"> | TTSDonation | [TTSDonation 파일 바로가기](https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/tree/master/day3/TTSDonation) |
<br>

## 설계 목표

TTS 음성변환 컴포넌트 사용법을 학습한다.

<br>

## 설명 

인터넷 방송과 같이 후원 창을 표시할 수 있는 앱 \
금액에 따라 이모티콘이 다르게 나타난다. 

<br>

## 이벤트 


*Screen 1*

```
⏹ Button Event(1)
```

> **응원하기 버튼을 클릭했을 때** \
> Screen 2 로 이동한다. \
> Screen 2 로 입력값을 전달한다.

> **입력값이 비어있을 때** \
> 경고창 알림을 화면에 표시한다.


*Screen 2*

```
📡 Sensor Event
```

> **Screen 2 가 초기화되었을 때** \
> 입력값을 화면에 표시한다. \
> 응원메세지를 음성변환으로 출력한다. \
> 조건에 따라 소리 및 이모티콘을 표시한다.
> > < 만원 \
> > ≥ 만원, < 오만원 \
> > ≥ 오만원 

> **5초 지났을 때** \
> 화면에 표시한 요소가 사라진다.

```
⏹ Button Event(2)
```

> **응원하러 가기 버튼을 클릭했을 때** \
> Screen 1 로 이동한다.

<br>

## 소스 파일 

|      FileName     |   Description  | Extenstion |
|   :------------:  |  :----------:  | :--------: |
| TTSBackground.png |       배경     |    png     |
|  LogoCodang.png   |       로고     |    png     |
|  Img1000won.gif   |  천원 이모티콘  |    gif     |
|  Img10000won.gif  |  만원 이모티콘  |    gif     |
|  Img50000won.gif  |  오만원 이모티콘 |   gif     |
|    1000won.mp3    |     천원 소리   |    mp3    |
|    10000won.mp3   |     만원 소리   |    mp3    |
|    50000won.mp3   |    오만원 소리  |    mp3    |

<br>

## 멘토 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/TTSDonation/Mentor_TTSDonation.aia

<br>

## 멘티 

https://github.com/CodingHakdang/2023-02-Winter-Camp-App-Inventor-aia/blob/master/day3/TTSDonation/Menti_TTSDonation.aia
