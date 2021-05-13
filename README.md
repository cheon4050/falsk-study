# API
## API DOCS
GET /?lat=''&lng=''
```swift
{
    "name": string, //dutyName
    "lat": number, //위도
    "lng": number, //경도
    "hpid": string, //고유 id 값
    "isOfficial": boolean //공공데이터 내 장소인지
}
```
GET /:hpid
```swift
{
    "name": string, // 이름
    "addr": string, // 주소
    "tel" : string, // 전화번호
    "start": object {
        "mon": string, // 월요일 시작 시간 ex) "18:30"
        "tue": string, // 화요일 시작 시간
        "wed": string, // 수요일 시작 시간
        "thur": string, // 목요일 시작 시간
        "fri": string, // 금요일 시작 시간
        "sat": string, // 토요일 시작 시간
        "sun": string, // 일요일 시작 시간
    },
    "close" : {
        "mon": string, // 월요일 종료 시간 ex) "18:30"
        "tue": string, // 화요일 시작 시간
        "wed": string, // 수요일 시작 시간
        "thur": string, // 목요일 시작 시간
        "fri": string, // 금요일 시작 시간
        "sat": string, // 토요일 시작 시간
        "sun": string, // 일요일 시작 시간
    }
}
```
# 담당파트

**이종아** [@jong-a LEE](https://github.com/whddk4415)
- 팀장
- Mongo db 연결 쿼리 제작
- API 구현
- 데이터 전처리

**김진영** [@Jin Kim](https://github.com/gimquokka)
- API 구현
- 데이터 전처리
- 발표 및 README 작성

**고동천** [@cheon4050](https://github.com/cheon4050)
- 데이터 전처리
- README 작성
