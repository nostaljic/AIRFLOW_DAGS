# 기록

Airflow가 기동되는 스케쥴러용 서버를 독립적으로 실행시키고 있다고 가정한다.
독립적으로 가동되는 이유는 여러가지 있을 수 있지만, 분석환경이 제각각이고, 가용 하드웨어들이 제한적일때 
효과적인 방안이라고 생각한다.

### SSHOperator

필요 패키지 : [ ](https://pypi.org/project/apache-airflow-providers-ssh/3.5.0/)

