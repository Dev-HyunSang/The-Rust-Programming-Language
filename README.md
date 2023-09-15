# The Rust Programming Language
[The Rust Programming Language]()를 통해서 Rust의 기본적인 문법에 대해서 배웁니다.

## 주의사항

### `cargo` 명령어를 통한 프로젝트 생성 시
- 본 프로젝트 구조는 하나의 디렉토리 내에서 `cargo` 명령어를 통해서 생성하는 경우 `.git` 디렉토리가 생성되어 커밋이 안 되는 경우가 발생함.
  - `does not have a commit checked out` 오류 메시지 발생함.
  - 해결 방법으로 프로젝트 생성 시 `.git` 디렉토리가 생성되지 않게 할 수 있음.

```bash
$ cargo new --vsc node <PROJCET_NAME>
```