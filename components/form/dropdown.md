# DropdownComponent
> FormPack

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| autoExecute | boolean  | 자동 실행에 대한 옵션                                  |

---
#### Methods

DropdownFieldComponent does not provide any methods.

---
#### Events
|이벤트명|설명|
|---|---|
|register|화면에 등록시 발생|
|completed|어떤? 완료시 발생|
|destroy|화면에 해제시 발생|
|change[^2]|값을 선택시 발생|

[^2]: *change event information*.
```json
{
    name: "change",
    label: "값 선택 이벤트",
    description: "값 선택 이벤트 입니다.",
    properties: [{
        name: "value",
        type: "string",
        default: "",
        description: "새로운 값입니다."
    }]
}
```

#### WScript Example
<!-- js-console -->
```js
// DropdownComponent의 목록이 Sample01,Sample02로 변경되고, sample02가 선택되어지는 예제
this.options = [{text:"Sample01",value:"sample01"},
                {text:"Sample02",value:"sample02"}];
this.value = "sample02";
```