# RollingPageComponent
> 구성한 페이지를 컴포넌트안에 삽입하여 설정된 주기에 반복적으로 로딩되어 사용하는 컴포넌트입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| overflow | String  | overflow 여부                             |

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
        play(): <span class="data_type">void</span>
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>페이지 반복 로딩을 실행하는 함수</li>
    </ul>
    <ul style="list-style:none;">
        <li>
        <aside class="source_description">
            <ul>
                <li>Defined in static/component/2D/basic/RollingPageComponent/RollingPageComponent.js</li>
            </ul>
        </aside>
        <div class="parameters_title">Returns: <span class="data_type">void</span></div>
        </li>
    </ul>
</div>
<br>
<div class="method_container">
    <a name="addeventlistener" class="tsd-anchor"></a>
    <div class="method_title">
        <!-- <span class="method_access">
            Public
        </span> -->
        stop(): <span class="data_type">void</span>
    </div>
    <ul style="list-style:none;margin-left:-20px;margin-right:-20px;border:1px solid #eee;padding:10px 10px 10px 40px;font-size:17px;">
        <li>페이지 반복 로딩을 멈추는 함수</li>
    </ul>
    <ul style="list-style:none;">
        <li>
        <aside class="source_description">
            <ul>
                <li>Defined in static/component/2D/basic/RollingPageComponent/RollingPageComponent.js</li>
            </ul>
        </aside>
        <div class="parameters_title">Returns: <span class="data_type">void</span></div>
        </li>
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

#### How to use
```js
// RollingPageComponent 페이지 반복 로딩을 멈추는 예제
this.stop();

// RollingPageComponent 페이지 반복 로딩을 실행하는 예제
this.play();
```