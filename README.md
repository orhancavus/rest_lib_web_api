# Python Rest Library Services implemented with Flask

## Credits to Patrick Smyth' tutorial Creating Web APIs with Python and Flask

[programminghistorian.org - Apis with Python and Flask](https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask)

[programminghistorian.org - Github repo](https://github.com/programminghistorian/jekyll/blob/95d0fd1e6c72e8a70f95a9b9485c406c05274ea5/en/lessons/creating-apis-with-python-and-flask.md)

```bash
- python hist_api.py                                    - Simple Flask app
- python library_all_books.py                           - Flask app that serves json list with books
    http://127.0.0.1:5000/api/v1/resources/books/all

- python library_all_id_books.py                        - Flask app that serves json list with books, id resource implemented
    http://127.0.0.1:5000/api/v1/resources/books/all
    http://127.0.0.1:5000/api/v1/resources/books?id=1
     
- python library_all_id_books_db.py                     - Flask app that serves sqlite db with books, id, author, published resources implemented  
    http://127.0.0.1:5000/api/v1/resources/books/all 
    http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis 
    http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis&published=1999 
    http://127.0.0.1:5000/api/v1/resources/books?published=2010
    or
    curl http://127.0.0.1:5000/api/v1/resources/books\?author\=Connie+Willis | jq
```
