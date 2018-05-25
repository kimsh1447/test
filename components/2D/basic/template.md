# TemplateComponent
> HTML, CSS를 확장팝업으로 구성하여 나타낼 수 있는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| dataProvider | Array<`Object`>  | 화면에 나타낼 데이터                              |

#### Methods

<style>
    .method_container {padding:20px; background-color:#fff; box-shadow:0 0 4px rgba(0, 0, 0, 0.25); border:1px solid rgba(0, 0, 0, 0.25);}
    .method_container ul {font-size:12px;}
    .method_access {border-radius:2px; margin-right:5px; background-color:#999999;padding:1px 1px 1px 4px;font-size:11px !important;font-weight:normal;}
    .method_title {font-size:20px;font-weight:bold;margin-bottom:20px;}
    .source_description {font-style:italic; font-size:13px; color:#808080; }
    .source_description p { margin: 0}
    .source_description ul { margin: 0}
    .parameters_title { font-size:15px; font-weight:bold; margin-top:20px;}
    .parameters li { font-weight:bold; }
    .data_type { font-style:italic; font-weight:normal; }
</style>
<div class="method_container">
    <a name="addeventlistener" class="tsd-anchor"></a>
    <div class="method_title">
        render(): <span class="data_type">void</span>
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>데이터를 설정된 template으로 화면에 표출 하는 함수</li>
    </ul>
    <ul style="list-style:none;">
        <li><div class="parameters_title">Returns: <span class="data_type">void</span></div></li>
    </ul>
</div>

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||컴포넌트 삭제시 발생|
|change|value|데이터값이 변경될시 발생|


#### How to use
```js
var data = [{ "key" : "test", "value": "textValue" }];

// 해당 컴포넌트의 속성을 변경하는 방법 01.
this.dataProvider = data;
// 해당 컴포넌트의 속성을 변경하는 방법 02.
this.setGroupPropertyValue("setter","dataProvider", data)
// 해당 컴포넌트의 경우 dataProvider 변경 후 render 함수를 사용하여야만 화면 갱신이 이루어집니다.
this.render();

// 이벤트 인자 확인 방법
console.log(event.data.value);
// 결과값(샘플) > [{ "key" : "test", "value": "textValue" }]

```

---

![gras](./images/template.png)
<p align="right" style="margin-top: -.85em;font-style: italic;">템플릿 HTML/CSS/DATA 설정</p>
