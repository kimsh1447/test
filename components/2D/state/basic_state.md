# Basic State Component
> 리소스를 표시해주며 상태에 따라 색상이 변하는 컴포넌트

#### Properties
| Name | Type | Desc |
| --- | --- | --- |
|selectItem|`json`[^1]|선택되어진 리소스 정보|
|severity|`String`[^2]|상태에 대한 정보|

[^1]: selectItem
```json
{
    "path":"리소스 경로"
}
```

[^2]: severity
```json
critical,major,minor,warning,normal
```

#### Methods
Basic State Component는 함수를 제공하지 않습니다.

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||화면에 해제시 발생|

#### How to use

사용법은 추후에 제공하겠습니다.