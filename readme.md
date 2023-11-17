### Userfront ts bug

An example project for recreating the ts bug in @userfront/core in 0.6.1 <= version <= 0.6.6

```
npm run build

The type `Function` has been replaced with `function` in type definitions.

# node_modules/@userfront/core/build/userfront-core.d.ts(5,51): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(25,12): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(26,20): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(27,13): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(28,13): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(39,12): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(47,13): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(170,28): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(171,23): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(172,24): error TS2552: Cannot find name 'function'. Did you mean 'Function'?
# node_modules/@userfront/core/build/userfront-core.d.ts(173,18): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(174,20): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(222,28): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(223,23): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(224,24): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(225,18): error TS2304: Cannot find name 'function'.
# node_modules/@userfront/core/build/userfront-core.d.ts(226,20): error TS2304: Cannot find name 'function'.
```

