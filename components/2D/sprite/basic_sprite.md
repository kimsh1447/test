# Basic Sprite Component
> State Pack

#### Properties
| Name | Type | Desc |
| --- | --- | --- |
|selectItem|`Object`[^1]|선택되어진 리소스 정보|

[^1]: Object
```json
{
    "path":"리소스 경로",
    "data": {
        "width":"이미지 넓이",
        "height":"이미지 높이",
        "columns":"리소스 행의 수",
        "totalFrames":"총 프레임의 수"
    }
}
```

#### Methods
Basic Sprite Component does not provide any methods.

#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|리소스 로드 완료시 발생|
|destroy|화면에 해제시 발생|

#### WScript Example