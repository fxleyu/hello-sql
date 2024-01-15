# 提交 sql
```sql
SELECT
  IFNULL(
    (
      SELECT DISTINCT Salary
      FROM Employee
      ORDER BY Salary DESC LIMIT 1, 1
    ),
    NULL
  ) AS SecondHighestSalary;
```
# 备注
注意在 `IFNULL` 函数使用

2月份搞定内置函数的眼熟
