# BasicGridComponent
> 확장팝업을 제공해 데이터셋, 스타일을 설정할 수 있는 그리드 컴포넌트 입니다.

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
        <!-- <span class="method_access">
            Public
        </span> -->
        render(): <span class="data_type">void</span>
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>데이터를 설정된 template으로 화면에 표출 하는 함수</li>
    </ul>
    <ul style="list-style:none;">
        <li>
        <aside class="source_description">
            <ul>
                <li>Defined in static/component/2D/basic/BasicGridComponent/BasicGridComponent.js</li>
            </ul>
        </aside>
        </li>
    </ul>
</div>

#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|리소스 로드 완료시 발생|
|destroy|컴포넌트 삭제시 발생|
|change[^1]|데이터값이 변경될시 발생|

[^1]*change event information*
```json
{
    name: "change",
    label: "데이터 변경 이벤트",
    description: "데이터 변경 이벤트 입니다.",
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
// BasicGridComponent 데이터를 변경하는 예제
this.dataProvider = 
    [{
        "key" : "test",
        "value": "textValue"
    }];

this.render();

```

---