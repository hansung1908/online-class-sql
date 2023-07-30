# [한신대학교] IT현직자가 알려주는 SQL로 배우는 데이터 추출 실무 백서 A to Z

### 1주차
- 주어진 여러 테이블 데이터에 대해 분석
- 각 컬럼의 데이터 형,자릿수 역할 파악까지 잘함, 더 나아가 각 테이블의 관계에 대해서 생각

### 2주차
- 현업이 제출한 데이터 추출 요청서를 확인 후 요구사항의 애매모호성의 제거하여 데이터 추출 작업 준비하기
- 컬럼 생성시 좀더 세분화해서 구현하는 것이 판별시 더 유리, sql 작성시 인라인 뷰를 활용

### 3주차
- 분석한 내용을 바탕으로 간단한 sql 작성
- to_char로 변경해서 날짜를 컨트롤, 적절한 join 사용 및 쌍둥이를 판별할 때 != 도 사용은 잘함
- 추가로 join시 inner, left outer를 적극적으로 활용, union all을 통해 각 데이터 통합도 고려

### 4주차
- 다양한 함수들을 통해 좀더 심화적인 sql 작성
- rank함수를 통해 해당 테이블에 순위를 매기고 일정 등수까지만 보고 싶으면 rownum함수를 통해 순위에 대한 순서값을 저장하고 조건을 생성
