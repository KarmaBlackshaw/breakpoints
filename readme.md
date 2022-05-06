# Breakpoint
Mobile first breakpoint helpers

[![GitHub Karmablackshaw](https://img.shields.io/github/last-commit/karmablackshaw/breakpoints)](https://github.com/karmablackshaw) 
[![GitHub Karmablackshaw](https://img.shields.io/github/commit-activity/m/karmablackshaw/breakpoints?color=orange&label=Commit%20Activity)](https://github.com/karmablackshaw) 

### Vue Composable
Usage
```js
import useBreakpoint from 'path-to-breakpoint';

const breakpoint = useBreakpoint()
```

```vue
 <div v-if="breakpoint.sm">sm</div>
 <div v-if="breakpoint.md">md</div>
 <div v-if="breakpoint.lg">lg</div>
 <div v-if="breakpoint.xl">xl</div>
```

### Sass
```scss
@import 'path-to-breakpoint';

@include breakpoint_sm { ... };
@include breakpoint_md { ... };
@include breakpoint_lg { ... };
@include breakpoint_xl { ... };
```
