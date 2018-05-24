# Basic State Component
> State Pack

#### Properties
| Name | Type | Desc |
| --- | --- | --- |
|selectItem|`Object`[^1]|선택되어진 리소스 정보|
|severity|`String`[^2]|상태에 대한 정보|

[^1]: Object
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
Basic State Component does not provide any methods.

#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|리소스 로드 완료시 발생|
|destroy|화면에 해제시 발생|

#### WScript Example