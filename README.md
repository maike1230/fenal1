# fenal1
[сайт моих родителей одежда на заказ за разумгную плату](https://fincult.info/article/kak-nachat-svoy-biznes/)
| LEFT | CENTER | RIGHT |
|----------------|:---------:|----------------:|
|USD | 55,03 | 79,50 |
|EUR  | 57,41 | 82,95 |

```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```
