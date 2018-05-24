# Basic Menu Component
> MenuPack

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| menuSetId | String | 저장되어진 메뉴셋의 고유 키값 |
| active_color | RGB | 활성화된 메뉴의 색상 |
| background_hover_color | RGB | 마우스 오버시 표현되는 메뉴 색상 |

#### Methods

BasicMenuComponent does not provide any methods.

#### Events

|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|어떤? 완료시 발생|
|destroy|화면에 해제시 발생|
|selectMenuItem|메뉴 선택시 발생|

#### WScript Example
<!-- js-console -->
```js
// MenuSetComponent가 다른 메뉴셋을 로드하여 화면에 표시하게 되는 예제
this.menuSetId = "130741114213-....";
```