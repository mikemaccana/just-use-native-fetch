## just-use-native-fetch

Want to avoid a billion unnecessary polyfills for node and browsers, now node 18 has `fetch` support and so does every browser? 

Of course you do.

Install this package and in your [Vite Config](https://vitejs.dev/config/shared-options.html#resolve-alias)

```
export default defineConfig({
  ...
  resolve: {
    alias: {
      "node-fetch": "just-use-native-fetch",
    },
  },
  ...
```

Yaay.
