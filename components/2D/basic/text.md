# TextComponent
> 데이터 셋으로 text를 설정할 수 있는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| text | String  | text 정보                                  |

#### Methods

TextComponent does not provide any methods.

---
#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|리소스 로드 완료시 발생|
|destroy|컴포넌트 삭제시 발생|
|change[^1]|값을 선택시 발생|

[^1]*change event information*
```json
{
    name: "change",
    label: "값 변경 이벤트",
    description: "값 변경 이벤트 입니다.",
    properties: [{
        name: "value",
        type: "string",
        default: "",
        description: "새로운 값입니다."
    }]
}
```

#### WScript Example
```js
// textComponent text를 바꾸는 예제
this.text = "textComponent test!";
```