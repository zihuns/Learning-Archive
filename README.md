# TypeScript Practice

이 저장소는 TypeScript의 주요 개념들을 학습하고 실습하기 위한 프로젝트입니다.

## 학습 내용

이 프로젝트는 다음과 같은 TypeScript의 핵심 주제들을 다루고 있습니다:

### 1. Basic Types (`basic-types`)

TypeScript의 기본 타입 시스템에 대한 이해와 실습을 진행합니다.

```typescript
let isDone: boolean = false;
let decimal: number = 6;
let color: string = "blue";
let list: number[] = [1, 2, 3];
let x: [string, number] = ["hello", 10];
```

### 2. Class (`class`)

객체 지향 프로그래밍을 위한 클래스 문법 및 활용을 다룹니다.

```typescript
class Greeter {
  greeting: string;
  constructor(message: string) {
    this.greeting = message;
  }
  greet() {
    return "Hello, " + this.greeting;
  }
}
```

### 3. Interface (`interface`)

객체의 구조를 정의하는 인터페이스의 사용법을 학습합니다.

```typescript
interface Person {
  firstName: string;
  lastName: string;
}

function greeter(person: Person) {
  return "Hello, " + person.firstName + " " + person.lastName;
}
```

### 4. Generic (`generic`)

재사용성을 높이기 위한 제네릭 프로그래밍 기법을 익힙니다.

```typescript
function identity<T>(arg: T): T {
  return arg;
}
```

### 5. Compilation Context (`compilation-context`)

TypeScript 컴파일러의 동작 방식과 컨텍스트 구성을 이해합니다.

### 6. TSC Project (`tsc-project`)

`tsconfig.json`을 이용한 TypeScript 프로젝트 설정 및 관리를 실습합니다.

```json
{
  "compilerOptions": {
    "module": "commonjs",
    "target": "es5",
    "sourceMap": true
  },
  "exclude": ["node_modules"]
}
```

## 구조

- `basic-types/`
- `class/`
- `compilation-context/`
- `generic/`
- `interface/`
- `tsc-project/`
