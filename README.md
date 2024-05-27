# OR_gurobi

## 13주차
### Attributes
<model attributes> , linear constraint, general constraint
.NumVars - 변수의 수
.NumConstrs - 제약조건의 수
.Runtime - 구로비 최적화 실행 시간
.objVal - 현재해의 목적 함수 값

<variable attributes>
- 특정변수에 대한 정보를 제공
.VType - 변수의 유형(continuos, binary, integer)
.VarName - 변수명
.X - 현재 도출된 해의 값
.getAttr - attribute들의 속성값을 조회할 수 있음 EX) m.getAttr(GRB.Attr.ObjVal)
