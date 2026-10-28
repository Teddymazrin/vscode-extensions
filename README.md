# VS Code Extensions

VS Code extensions by Teddy Mazrin. Each extension lives in its own folder.

| Extension | Folder | Marketplace |
|---|---|---|
| True Black: pure black (`#000000`) backgrounds on top of Dark+ | [true-black/](true-black/) | [TeddyMazrin.true-black](https://marketplace.visualstudio.com/items?itemName=TeddyMazrin.true-black) |

## Publish an extension

Run `vsce` from inside the extension's folder:

```bash
cd true-black
npx vsce publish patch
```
