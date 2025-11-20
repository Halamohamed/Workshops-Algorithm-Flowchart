
## Flowchart Exercise 1


```mermaid
flowchart TD
    A([Start]) --> I[/ Input N/]
    I --> B{N % 2 == 0 ?}
    B -->|Yes| C[/Print Even/]
    B -->|No| D[/Print Odd/]
    C --> E([End])
    D --> E([End])
    style A fill:lightblue,stroke:black,stroke-width:2px,shadow:shadow
    style I fill:green,stroke:black,stroke-width:2px,shadow:shadow
    style B fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style C fill:violet,stroke:black,stroke-width:2px,shadow:shadow
    style D fill:tomato,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:lightblue,stroke:black,stroke-width:2px,shadow:shadow
```
--- 

## Flowchart Exercise 2

``` mermaid
flowchart TD
    A([Start]) --> B(Total = 0, Average = 0)
    style A fill:lightblue,stroke:black,stroke-width:2px,shadow:shadow
    B --> C[/Input num1, num2, num3/]
    style B fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    C --> D[Total = num1 + num2 + num3]
    style C fill:green,stroke:black,stroke-width:2px,shadow:shadow
    D --> E[Average = Total/3 ]
    E --> F[/Print Total and Average/]
    F --> S([End])
    style D fill:red,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:purple,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---

## Flowchart Exercise 3

``` mermaid
flowchart TD
    A([Start]) --> B[count = 0 ]
    style A fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
    B --> C[/Input number/]
    style B fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    C --> D[count = count + 1]
    style C fill:green,stroke:black,stroke-width:4px,shadow:shadow
    D --> E[result = number * count]
    E --> F[/Print "number * count = result"/]
    F --> G{ count <= 10? }
    G --> |No| C
    G --> |Yes| S([End])
    style D fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:red,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:purple,stroke:black,stroke-width:2px,shadow:shadow
    style G fill:orange,stroke:darkblue,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---
## Flowchart Exercise 4

``` mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    style A fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
    B --> C{ number < 0? }
    style B fill:lightgreen,stroke:black,stroke-width:2px,shadow:shadow
    C --> |No| D{ number > 0? }
    style C fill:tomato,stroke:black,stroke-width:2px,shadow:shadow
    C --> |Yes| E[/Print Negative/]
    D --> |Yes| F[/Print Positive/]
    D --> |No| G[/Print Zero/]
    E --> S([End])
    F --> S([End])
    G --> S([End])
    style D fill:tomato,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:slateBlue,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:violet,stroke:black,stroke-width:2px,shadow:shadow
    style G fill:orange,stroke:darkblue,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---

## Flowchart Exercise 5

``` mermaid
flowchart TD
    A([Start]) --> B[/Input P, R, T/]
    style A fill:lightblue,stroke:black,stroke-width:2px,shadow:shadow
    B --> C[SI = P*R*T ]
    style B fill:green,stroke:black,stroke-width:2px,shadow:shadow
    C --> D[/Print SI/]
    style C fill:tomato,stroke:black,stroke-width:2px,shadow:shadow
    D --> S([End])
    style D fill:Violet,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---

## Flowchart Exercise 6

``` mermaid
flowchart TD
    A([Start]) --> B[count = 0, total = 0]
    style A fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
    B --> C[/Input day/]
    C --> D[count ++]
    style B fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style C fill:green,stroke:black,stroke-width:2px,shadow:shadow
    D --> E[total = total + day]
    E --> F{ count <= 7? }
    F --> |No| C
    F --> |Yes| G[average = total/7]
    G --> I[/Print average/]
    I --> S([End])
    style D fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:slateBlue,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style G fill:tomato,stroke:darkblue,stroke-width:2px,shadow:shadow
    style I fill:violet,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---

## Flowchart Exercise 7

``` mermaid
flowchart TD
    A([Start]) --> B[/Input Length, Width/]
    style A fill:lightblue,stroke:black,stroke-width:2px,shadow:shadow
    B --> C[Area = Length * Width ]
    style B fill:green,stroke:black,stroke-width:2px,shadow:shadow
    C --> D[/Print Area/]
    style C fill:tomato,stroke:black,stroke-width:2px,shadow:shadow
    D --> S([End])
    style D fill:Violet,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---


## Flowchart Exercise 8

```mermaid
flowchart TD
    A([Start]) --> I[/Input Average/]
    I --> B{Average >= 50?}
    B -->|Yes| C[/Print Pass/]
    B -->|No| D[/Print Fail/]
    C --> E([End])
    D --> E([End])
```

---

## Flowchart Exercise 9

``` mermaid
flowchart TD
    A([Start]) --> B[count = 0, fact = 0]
    style A fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
    B --> C[/Input number/]
    C --> D[count ++]
    style B fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style C fill:green,stroke:black,stroke-width:2px,shadow:shadow
    D --> E[fact = fact * count]
    E --> F{ count <= number? }
    F --> |Yes| C
    F --> |No| I[/Print fact/]
    I --> S([End])
    style D fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:slateBlue,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style I fill:violet,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---

## Flowchart Exercise 10

``` mermaid
flowchart TD
    A([Start]) --> B[discount = 0, final_amount = 0]
    style A fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
    B --> C[/Input Amount/]
    C --> F{ Amount > 1000 ? }
    style B fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style C fill:green,stroke:black,stroke-width:2px,shadow:shadow
    F --> |Yes| D[discount = Amount * 0.1]
    D --> E[final_amount = amount - discount]
    F --> |No| E
    E --> I[/Print final_amount/]
    I --> S([End])
    style D fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:slateBlue,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style I fill:violet,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:2px,shadow:shadow
```

---