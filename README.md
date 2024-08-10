# Learn to Cargo

> 러스트 빌드 시스템 및 패키지 매니저입니다. (`node.js == package.json`)

## Run Cargo

1. 러스트를 다운받고 사용할 단계가 된다면 자동으로 `Cargo`라는 패키지 매니저를 실행할 수 있다.

- `cargo -v`
- `cargo --version`

# 코드 파헤쳐보기

`main.rs` 파일을 열어보면 아래와 같은 코드가 있다.

```rust
// src/main.rs
fn main() {
    println!("Hello, world!");
}
```

1. 러스트에서는 탭 대신 스테이스 4칸을 사용한다.
2. `println!`는 러스트의 매크로 호출 코드. (함수호출 코드였다면 `!`없이 `println`으로 호출한다.)
3. `println`의 인수로 넘겨준 `Hello, world!`는 문자열 리터럴이다.
4. 이라인은 세미콜론(`;`)으로 끝난다.

# 부록

1. 라이브러리를 쓰는 이유.

- 코드빌드나, 코드 작성에 필요한 라이브러리를 다운로드,작성할때 귀찮은 일들을 상당수 줄여주는 편리한 도구.
  - 외부 라이브러리는 (dependency)라고 지칭하겠다.
