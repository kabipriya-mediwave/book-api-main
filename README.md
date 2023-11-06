# express-myimdb-api

## 1. get/books

- get the array of objects with id, title and isbn.

## 2. post/books

- adding movie with title and isbn with validaton for isbn-10
- error handler for the next(arg)

## 3. post /books/:bookid/rating

add rating within the range 0 to 5

```
const rating = [
    {
        rateId,
        rating,
        bookId,
    }
]
```

## 4. GET /books/:bookid

find the rating provided for the book, then display the single book with rating.

```
{
id: 216,
title: '',
isbn: '',
rating: 4,
}
```

by default rating should be 0.
