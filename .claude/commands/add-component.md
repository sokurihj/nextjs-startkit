---
name: add-component
description: React 함수형 컴포넌트 생성 (TypeScript + Tailwind CSS)
argument-hint: 컴포넌트 이름 (예: Button, Card, Header)
---

`src/components/$1.tsx` 파일에 다음과 같은 React 함수형 컴포넌트를 생성해주세요:

```tsx
import React from 'react'

interface $1Props {
  // Props를 여기에 추가하세요
}

export const $1: React.FC<$1Props> = () => {
  return <div className="">{/* 컨텐츠 */}</div>
}

export default $1
```

**요구사항:**

- TypeScript를 사용한 함수형 컴포넌트
- Props를 위한 인터페이스 정의 (interface $1Props)
- Tailwind CSS className 속성 사용
- React.FC 제네릭 타입 지정
- named export와 default export 모두 포함
- 파일명은 PascalCase ($1.tsx)
