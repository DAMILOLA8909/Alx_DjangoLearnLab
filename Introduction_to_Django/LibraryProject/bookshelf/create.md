# Create Operation

## Command
```python
from bookshelf.models import Book

book = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
```

## Output
```
# Book instance created successfully
```

## Verify
```python
print(book)
```
Output:
```
1984 by George Orwell (1949)
```