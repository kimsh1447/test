# TextAreaFieldComponent
> FormPack

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| options | Array<`option`[^1]>  | 옵션 목록                                  |
| value   | String | 선택되어진 옵션 정보                                 |

[^1]*option json*
```json
{
  text: "화면에 표시될 문자열",
  value: "실제 데이터"
}
```
---
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
        updateOptions(): <span class="data_type">void</span>
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>현재 설정되어진 options와 value로 화면을 update해주는 함수</li>
    </ul>
    <ul style="list-style:none;">
        <li>
        <aside class="source_description">
            <ul>
                <li>Defined in static/component/2D/form/DropdownFieldComponent/DropdownFieldComponent.js:68</li>
            </ul>
        </aside>
        <!-- parameter 설명 -->
        <!-- <div class="parameters_title">Parameters</div>
        <ul class="parameters">
            <li>config: <span class="data_type">string</span></li>
        </ul> -->
        <div class="parameters_title">Returns: <span class="data_type">void</span></div>
        </li>
    </ul>
</div>

<!-- <div class="method_container">
    <a name="addeventlistener" class="tsd-anchor"></a>
    <div class="method_title">
        <span class="method_access">
            Protected
        </span>
        _onCommitProperties(config: <span class="data_type">string</span>): void
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>컴포넌트 속성 갱신 처리 함수(기본 속성은 상위 객체에서 처리하도록 구현)</li>
    </ul>
    <ul style="list-style:none;">
        <li>
        <aside class="source_description">
            <p >Implementation of IWVDisplayObject</p>
            <p>Inherited from WVDisplayObject</p>
            <ul>
                <li>Defined in static/component/2D/form/DropdownFieldComponent/DropdownFieldComponent.js:99</li>
            </ul>
        </aside>
        <div class="parameters_title">Parameters</div>
        <ul class="parameters">
            <li>config: <span class="data_type">string</span></li>
        </ul>
        <div class="parameters_title">Returns: <span class="data_type">void</span></div>
        </li>
    </ul>
</div> -->

---
#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|change[^2]|값을 선택시 발생|

[^2]*change event information*
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