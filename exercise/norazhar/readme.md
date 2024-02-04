# Hello World
## Hello World
### Hello World
#### Hello World

My name  **Norazhar Anas**, I'm *43 years old*
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |

| Name            | IC Number    | Gender | Age | Address                           |
|-----------------|--------------|:--------:|-----:|-----------------------------------|
| Ahmad bin Ali   | 950201-14-5678| Male   | 30  | 123 Jalan Merdeka, Kuala Lumpur   |
| Siti binti Tan  | 881011-08-9876| Female | 25  | 456 Jalan Bunga Raya, Penang      |
| Hafizah bt Lim  | 900505-12-3456| Female | 32  | 789 Jalan Damai, Johor Bahru      |
| Amirul bin Raju | 970719-11-2345| Male   | 24  | 321 Jalan Sentosa, Kuching        |

``` mermaid
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }

    }
```
