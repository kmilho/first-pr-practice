# first-pr-practice

GitHub에서 첫 Pull Request를 연습하기 위한 아주 작은 계산기 라이브러리입니다.

## 설치

```bash
pip install -r requirements.txt
```

## 사용법

```python
from calculator import add, subtract

add(2, 3)       # 5
subtract(5, 2)  # 3
```

## 테스트 실행

```bash
python -m unittest discover
```
