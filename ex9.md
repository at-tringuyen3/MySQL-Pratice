### Câu 9: Lấy số lượng comment của các blog
```
SELECT blog.id, blog.title, COUNT(blog.id) AS 'So comment cua moi blog' 
FROM comment 
INNER JOIN blog  ON comment.target_id = blog.id 
WHERE target_table = 'blog' 
GROUP BY blog.id
```