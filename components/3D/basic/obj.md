# ObjLoaderComponent
> 리소스매니저를 이용하여 obj파일을 나타내는 컴포넌트 입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| selectItem | Info[^1]  | 리소스매니저에서 전달받은 리소스 경로 정보              |
| originSize | Boolean  | 리소스 원본 사이즈              |

[^1]: *Info json*
```json
{
  compName: "컴포넌트 이름",
  objPath: "리소스 경로",
  texturePath: "리소스의 texture 경로",
  recycleYn: "재사용 여부 ( Pool에 담겨 재사용 )",
}
```

#### Methods

ObjLoaderComponent does not provide any methods.

#### Events
|이벤트명|설명|
|---|---|
|click|마우스 클릭시 발생|
|dblclick|마우스 더블 클릭시 발생|
|register|화면에 등록시 발생|
|completed|컴포넌트 로딩 완료시 발생|
|destroy|컴포넌트 삭제시 발생|

#### WScript Example

ObjLoaderComponent does not provide an example.