## Getting Started
### Indexing a document

> Index: where the document lives
> Type: class of object document represents
> Id: unique identifier

### If you have an id
```
PUT /{index}/{type}/{id}
```

### If you want ES to generate the id
```
POST /{index}/{type}
```

### An example

```
PUT /dog/breed/1
{
  "name": "Golden Retriever",
  "origin": "England",
  "role": "Companion dog"
}
```

```
POST /dog/breed
{
  "name": "Golden Retriever",
  "origin": "England",
  "role": "Companion dog"
}
```

