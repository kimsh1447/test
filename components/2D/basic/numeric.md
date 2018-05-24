# numericComponent
> 기본으로 제공하는 progressBar Custom 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| bar_value | Number  | Bar Value 정보                                        |
| min_value | Number  | Bar Value 범위의 최솟값                                |
| max_value | Number  | Bar Value 범위의 최댓값                                |
| bt_margin | Number  | Bar Value 범위의 예외값 (기준 : bottom )                |
| bar_color | String  | Bar 의 색상 값                                         |
| bar_radius | String  | Bar 의 Radius 값                                      |
| direction | String  | 툴팁의 방향 ( left, right )                            |
| text_value | String  | 툴팁 text 정보                                         |
| title_BackColor | String  | 툴팁 배경 색상 값                                  |
| title_FontColor | String  | 툴팁 폰트 색상 값                                  |

#### Methods

NumericComponent does not provide any methods.

---
#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|컴포넌트 로딩 완료시 발생|
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
// textComponent 툴팁 text를 바꾸는 예제
this.text_value = "11.1%";

// textComponent bar Value를 바꾸는 예제
this.bar_value = "60";
```

---