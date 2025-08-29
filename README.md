### SETTING_nextjs_neon_prisma

package.json에 "postinstall": "prisma generate" 추가해야 vercel 자동 빌드 에러안남.

```
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint",
    "postinstall": "prisma generate"
  },
```
