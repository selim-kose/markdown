# markdown
Markdown test

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

```mermaid
  Artist ||--o{ Album : has

    Artist {
        int ArtistId
        varchar Name
    }

    Album {
        int AlbumId
        int ArtistId
        varchar Title
    }

```    
