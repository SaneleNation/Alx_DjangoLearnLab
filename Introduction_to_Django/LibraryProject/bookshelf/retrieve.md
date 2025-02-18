```python:
from bookshelf.models import Book

get_book = Book.objects.get(publication_year = 1984)
