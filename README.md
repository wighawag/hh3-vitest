# Error

```
FAIL  test/Counter.test.ts [ test/Counter.test.ts ]
TypeError: Unknown file extension ".ts" for /home/wighawag/dev/github.com/bug-reproduction/hh3-tests/hardhat.config.ts
```

Reproduction:

```bash
git clone https://github.com/bug-reproduction/hh3-vitest.git
cd hh3-vitest
pnpm i
pnpm vitest
```
