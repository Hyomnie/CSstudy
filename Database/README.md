### JOIN
---------
두 개 이상의 테이블이나 데이터베이스를 연결하여 데이터를 검색하는 방법. 자신이 검색하고 싶은 컬럼이 다른 테이블에 있을 경우 주로 사용하며, 여러 개의 테이블을 마치 하나의 테이블인 것처럼 활용하는 방법이다.
주로 기본키나, 외래키로 두 테이블을 연결한다.

조인의 종류에는 INNER JOIN, OUTER JOIN, SELF JOIN 등이 있다.
INNER JOIN은 테이블의 교집합, OUTER JOIN은 자기 자신과 다른 테이블과의 교집합을 더한 결과이다. OUTER JOIN 중 FULL OUTER JOIN은 합집합에 해당한다.

INNER JOIN은 EQUI, NATURAL, CROSS JOIN으로 구분된다.
EQUI JOIN의 경우 두 테이블의 한 열의 값이 같은 지를 비교하여 JOIN하게 되는 것이고, NATURAL JOIN의 경우 대상 테이블의 컬럼을 비교하여 같은 이름을 가진 컬럼은 하나만 추출한다. CROSS JOIN은 연산에 참여한 모든 테이블들과 나올 수 있는 결과가 추출되게 된다.

SELF JOIN은 원하는 데이터들이 하나의 테이블에 있을 때 사용한다.

### R DBMS & NOSQL
### 정규화 & 반정규화
