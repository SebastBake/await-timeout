# await-timeout

It's literally just this:

```ts
export default function Timeout(ms: number): Promise<void> {
  return new Promise((resolve) => setTimeout(() => resolve(), ms));
}
```
