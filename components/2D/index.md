# 2D Component

#### Common Properties
| Name | Type | Desc |
| --- | --- | --- |
| x | Number | x좌표 |
| y | Number | y좌표 |
| width | Number | 가로길이 |
| height | Number | 세로길이 |
| depth | Number | 깊이 |
| rotation | Number | 회전각도 |

#### Methods

2D Component는 함수를 제공하지 않습니다.

#### How to use
```js
// 컴포넌트의 공통 속성 정보를 확인하는 방법
console.log("좌표 값 : ", this.x,this.y,
            "크기 값 : ", this.width, this.height,
            "깊이 값 : ", this.depth,
            "회전 값 : ", this.rotation);
// 결과값(샘플) > 좌표 값 :  289 460 크기 값 :  100 200 깊이 값 :  10003 회전 값 :  0

// 컴포넌트의 공통 속성 변경하는 방법
this.x = 0, this.y = 0, this.width = 100, this.height = 100, this.depth = 1, this.rotation = 0;
```