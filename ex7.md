### Câu 7: Xoá tất cả comment của user = 2 trong blog = 5
```
DELETE FROM comment 
WHERE user_id = 2 AND target_table = 'blog' AND target_id = 5
```