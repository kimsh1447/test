# JsonLoaderComponent
> 리소스매니저를 이용하여 애니메이션이 포함되어 있는 json파일을 나타내는 컴포넌트 입니다.

#### Properties
| Name       | Type    | Desc                                                |
| :--------- | :------ | :-------------------------------------------------- |
| selectItem | `json`[^1]  | 리소스매니저에서 전달받은 리소스 경로 정보              |
| originSize | Boolean  | 리소스 원본 사이즈              |

[^1]: *selectItem*
```json
{
  compName: "컴포넌트 이름",
  jsonPath: "리소스 경로",
  texturePath: "리소스의 texture 경로",
  recycleYn: "재사용 여부 ( Pool에 담겨 재사용 )",
}
```

#### Methods

JsonLoaderComponent는 함수를 제공하지 않습니다.

#### Events
|이벤트명|이벤트 인자|설명|
|---|---|---|
|click||마우스 클릭시 발생|
|dblclick||마우스 더블 클릭시 발생|
|register||화면에 등록시 발생|
|completed||리소스 로드 완료시 발생|
|destroy||컴포넌트 삭제시 발생|

#### How to use

JsonLoaderComponent은 기본 사용법을 참고하시기 바랍니다.