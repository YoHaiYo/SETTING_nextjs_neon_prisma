### aws 세팅시

.env 생성 후 DB연결

1. 로컬

```
DATABASE_URL="mysql://root:{로컬 mysql 비번}@127.0.0.1:3306/db_prisma_basic"
```

2. AWS

```
DATABASE_URL="mysql://admin:{AWS RDS 비번}@{AWS RDS의 엔드포인트 주소}/db_prisma_basic"
```
# SETTING_nextjs_neon_prisma
