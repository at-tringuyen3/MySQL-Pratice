### Câu 4: Select 10 blog mới nhất đã active
```
SELECT * 
FROM blog 
WHERE is_active = 1 
ORDER BY id DESC
LIMIT 10
```