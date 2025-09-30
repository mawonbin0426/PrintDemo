# Python Print & Rich Demo

이 프로젝트는 **Python의 다양한 출력 방법**과 **`rich` 라이브러리**를 활용한
터미널 출력 꾸미기 예제를 포함하고 있습니다.  

## 📂 파일 구성

### 1. `main_print_v1.py`
- Python 기본 출력 방식 정리
  - 일반 `print()`
  - 여러 값 출력 (콤마 구분)
  - f-string (Python 3.6+)
  - `.format()` 함수
  - `%` 포맷팅 (C 스타일)
  - 줄바꿈, `end`, `sep` 옵션
  - 딕셔너리/리스트 출력
  - f-string 내 계산식/함수
  - 멀티라인 출력

➡️ **Python 출력 기초 문법을 복습하기 좋은 예제**

---

### 2. `main_print_v2.py`
- `rich` 모듈을 사용한 터미널 출력 꾸미기
  - 컬러/스타일 적용
  - `Panel`(박스) 출력
  - `Table` 출력
  - `sep`, `end` 옵션 활용 (기존 `print()`와 동일)

예시:
```python
pprint(f"[bold green]Hello, {name}![/] Your score is [cyan]{score:.2f}[/].")
