# 提交 sql
```sql
select
  a.FirstName as firstName,
  a.LastName as lastName,
  b.City as city,
  b.State as state
from
  Person a
  left join Address b on a.PersonId = b.PersonId;
```
# 最优sql

