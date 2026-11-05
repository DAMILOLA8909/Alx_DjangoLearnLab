# Update Operation

## Command
```python
from bookshelf.models import Book

book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()
```

## Output
```
# Title updated successfully
```

## Verify
```python
print(book.title)
```
Output:
```
Nineteen Eighty-Four
```