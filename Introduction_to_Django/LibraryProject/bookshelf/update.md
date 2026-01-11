
---

## 📄 3️⃣ `update.md`

```markdown
# Update Book Record

```python
from bookshelf.models import Book
book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()
book
