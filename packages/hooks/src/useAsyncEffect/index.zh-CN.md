---
title: useAsyncEffect
nav:
  title: Hooks
  path: /hooks
group:
  title: SideEffect
  path: /side-effect
---

# useAsyncEffect

<Tag lang="zh-CN" tags="ssr&crossPlatform"></Tag>

useEffect 支持异步函数。

## 代码演示

### 基础用法

<code src="./demo/demo1.tsx" />

### 中断执行

<code src="./demo/demo2.tsx" />

## API

```typescript
function useAsyncEffect(
  effect: () => AsyncGenerator | Promise,
  deps: DependencyList
);
```