# ElysiaJs Books API

**To Get Books:**
```bash
GET /books
```

**To Add A Book:**
```bash
POST /books
```
example value:
```json
{
  "name": "string",
  "author": "string"
}
```

**To Update A Book:**
```bash
PUT /books
```
example value:
```json
{
  "id": 0,
  "name": "string",
  "author": "string"
}
```

**To Get A Book By Id:**
```bash
GET /books/:id
```

**To Delete A Book:**
```bash
DELETE /books/:id
```

**To Sign In:**
```bash
POST /sign/:name
```
