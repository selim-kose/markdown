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
erDiagram
    CUSTOMER }|..|{ DELIVERY-ADDRESS : has
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER ||--o{ INVOICE : "liable for"
    DELIVERY-ADDRESS ||--o{ ORDER : receives
    INVOICE ||--|{ ORDER : covers
    ORDER ||--|{ ORDER-ITEM : includes
    PRODUCT-CATEGORY ||--|{ PRODUCT : contains
    PRODUCT ||--o{ ORDER-ITEM : "ordered in"
```

```mermaid
	erDiagram


	Artist{
	  int ArtistId
	  varchar ArtistName
	  }

	
	Album{
	  int AlbumId
	  varchar AlbumName
	  }

	  Artist ||--o{ Album : has
```
