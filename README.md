# Typescript TDD Kata

[String Calculator Kata](https://kata-log.rocks/string-calculator-kata)

## Getting Started

Follow the next instructions to get a copy of the project up and running in your local machine.

### Prerequisites

- Install LTS version of [Node](https://nodejs.org/).
- [pnpm](https://pnpm.io/installation) is optional but highly recommended.

### Installation

Run the following commands:

```
git clone https://github.com/dfvalero/typescript-tdd-kata.git
cd typescript-tdd-kata
pnpm i
```

## Testing

### Unit tests

This kata uses [Jest](https://jestjs.io/) to run Unit tests.

To run those tests, run the following command:

```
pnpm test:unit
```

Run this command to run the tests in `watch mode`:

```
pnpm test:unit:watch
```

Run this command to run a test for a single file:

```
pnpm test:unit ${path-to-test-file}
```

Example:

```
pnpm test:unit src/string-calculator/string-calculator.spec.ts
```

Example in `watch mode`:

```
pnpm test:unit:watch src/string-calculator/string-calculator.spec.ts
```
