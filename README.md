## Installation

```bash
  npm install  
```
To run with local
```bash
  npm run start:local 
```
To run with mysql
```bash
  npm run start:mysql 
```
## API Reference

#### Get all items

```http
  GET http://localhost:1234/movies
```

#### Get item

```http
  GET http://localhost:1234/movies/id
```

#### Post

```http
  POST http://localhost:1234/movies
```

{ "title", "year", "director", "duration", "poster", "genre" }

#### Delete

```http
  DELETE http://localhost:1234/movies/id
```

#### Patch

```http
  PATCH http://localhost:1234/movies/id
```
{ "year": 2024, "duration": 185 }