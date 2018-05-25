# Basic Menu Component
> MenuSet(Page구성)에 따라 메뉴 네비게이터를 구성하는 컴포넌트

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| menuSetId | String | 저장되어진 메뉴셋의 고유 키값 |
| active_color | RGB | 활성화된 메뉴의 색상 |
| background_hover_color | RGB | 마우스 오버시 표현되는 메뉴 색상 |

#### Methods

BasicMenuComponent는 함수를 제공하지 않습니다.

#### Events

|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||화면에 해제시 발생|
|selectMenuItem|`json`[^1]|메뉴 선택시 발생|

[^1]: *selectMenuItem*
```json
{
    type:"link/page",
    isPopup:false,
    url:""
}
```

#### How to use
```js
// 해당 컴포넌트의 속성을 변경하는 방법01
this.menuSetId = "130741114213-....";
// 해당 컴포넌트의 속성을 변경하는 방법02
this.setGroupPropertyValue("setter","menuSetId","130741114213-....");

// 이벤트 인자 확인 방법
console.log(event.data);
// 결과값(샘플) > {type: "page", isPopup: false, url: "5ec46ada-65ed-4cb4-a399-8cb0abb2e80f"}
```

#### Example

![gras](./images/menu.png)
<p align="right" style="margin-top: -.85em;font-style: italic;">메뉴셋 설정 화면</p>