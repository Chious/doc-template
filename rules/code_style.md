# 程式碼風格

> 根據不同的程式語言，需要制定不同的程式碼規範。

## 團隊的 Tech Stack 是？

- React
- TypeScript
- Tailwind
- React Query

## 範例

### React Query

```tsx
import { useQuery } from '@tanstack/react-query';

const { data } = useQuery({
  queryKey: ['posts'],
  queryFn: () => fetch('https://api.example.com/posts').then(res => res.json()),
});
```
