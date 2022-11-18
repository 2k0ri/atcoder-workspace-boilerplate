# atcoder-workspace-boilerplate

[AtCoder](https://atcoder.jp/) workspace template for C++ Language, powered by VSCode and [atcoder-tools](https://github.com/kyuridenamida/atcoder-tools)

## 0. Register https://atcoder.jp/

## 1. Get and start [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## 2. Clone this repository as `atcoder-workspace`

```sh
git clone https://github.com/2k0ri/atcoder-workspace-boilerplate.git atcoder-workspace
```

## 3. Open via VSCode

```sh
cd atcoder-workspace
code .
```

## 4. Build and reopen with devContainer

- Ctrl + Shift + P (Command + Shift + P)
- `> Reopen in Container`

## 5. Get tests with `atcoder-tools gen`
- Ctrl + Shift + Alt + B (Command + Shift + Option + B)
- `atcoder-tools gen`
- Type `abs` and enter
  - AtCoder Beginners Selection ([https://atcoder.jp/contests/__`abs`__](https://atcoder.jp/contests/abs))
- Log in with AtCoder account in console
- Tests will be generated under `abs/` directory

## 6. Build and check the test

- Open `abs/PracticeA/main.cpp`
- Ctrl + Shift + B (Command + Shift + B)
- Results will be shown in console

## 7. Debug the test

- Set the breakpoint in L20 `solve(a, b, c, s)`
- Ctrl + Shift + Alt + D (Command + Shift + Option + D)
- Choose `1.txt(lldb)`
- Variables will be shown

## 8. Submit the test

- Solve the `solve` method
- Ensure `Passed all test cases!!!` is shown in check
- Ctrl + Shift + Alt + B (Command + Shift + Option + B)
- `atcoder-tools submit`
- Codes will be submitted to AtCoder
