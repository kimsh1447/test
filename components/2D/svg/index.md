# SVG Pack
> Vector UI를 구성할 수 있는 컴포넌트 팩

|Component|Description|
|---|---|---|
|Line|직선을 표현하는 컴포넌트|
|Broken Line|꺽인 선을 표현하는 컴포넌트|
|Curve|곡선을 표현하는 컴포넌트|
|Circle|원을 표현하는 컴포넌트|
|Rect|사각형을 표현하는 컴포넌트|
|Stream Line|흐름이 있는 직선을 표현하는 컴포넌트|
|Stream Curve|흐름이 있는 곡선을 표현하는 컴포넌트|
|Stream Broken|흐름이 있는 꺽인 선을 표현하는 컴포넌트|


#### SVG Line Common Properties
| Name | Type | Desc |
| --- | --- | --- |
| startMarker | boolean | 시작 화살표 표시 유무 |
| endMarker | boolean | 끝 화살표 표시 유무 |
| points | Array<`Point`[^1]> | 선을 그리기위한 점 정보 |
| pointCount | number | 선을 만드는 점의 수 |

[^1]: Point
```json
{
    x:0,y:0,
    add:function(p:Point):Point{...},
    clone:function():Point{...},
    degreesTo:function(p:Point):number{...},
    distance:function(p:Point):number{...}
}
```