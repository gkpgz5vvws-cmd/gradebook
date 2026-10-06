# 파이썬 성적 관리 프로그램 (Gradebook)

파이썬 패키지 및 모듈 구조화, CSV 입출력, 단위 테스트(unittest) 실습 프로젝트입니다.

## 프로젝트 구조

- `project_root/`: 기본 모듈 및 성적 계산 로직 (`main.py`, `models.py`, `utils.py`)
- `project_root_pkg/`: 패키지 형태 구조
  - `gradebook/`: 성적 처리 패키지 (`cli.py`, `models.py`, `utils.py`)
    - `io/`: 파일 입출력 패키지 (`csvio.py`)
  - `tests/`: 단위 테스트 (`test_utils.py`)
  - `students.csv`: 학생 성적 데이터 파일

## 실행 방법

### CLI 프로그램 실행
```bash
python -m gradebook