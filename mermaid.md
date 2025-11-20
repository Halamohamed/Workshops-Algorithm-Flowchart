

## Flowchart Exercise 2

``` mermaid
flowchart TD
    A([Start]) --> B(Total = 0, Average = 0)
    style A fill:lightblue,stroke:black,stroke-width:4px,shadow:shadow
    B --> C[/Input num1, num2, num3/]
    style B fill:yellow,stroke:black,stroke-width:4px,shadow:shadow
    C --> D[Total = num1 + num2 + num3]
    style C fill:green,stroke:black,stroke-width:4px,shadow:shadow
    D --> E[Average = Total/3 ]
    E --> F[/Print Total and Average/]
    F --> S([End])
    style D fill:red,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:orange,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:purple,stroke:black,stroke-width:2px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:4px,shadow:shadow
```

---

## Flowchart Exercise 3

``` mermaid
flowchart TD
    A([Start]) --> B[count = 0 ]
    style A fill:lightblue,stroke:darkblue,stroke-width:4px,shadow:shadow
    B --> C[/Input number/]
    style B fill:yellow,stroke:black,stroke-width:4px,shadow:shadow
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
    style G fill:orange,stroke:darkblue,stroke-width:4px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:4px,shadow:shadow
```

---
## Flowchart Exercise 4

``` mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    style A fill:lightblue,stroke:darkblue,stroke-width:4px,shadow:shadow
    B --> C{ number < 0? }
    style B fill:lightgreen,stroke:black,stroke-width:4px,shadow:shadow
    C --> |No| D{ number > 0? }
    style C fill:lightorange,stroke:black,stroke-width:4px,shadow:shadow
    C --> |Yes| E[/Print Negative/]
    D --> |Yes| F[/Print Positive/]
    D --> |No| G[/Print Zero/]
    E --> S([End])
    F --> S([End])
    G --> S([End])
    style D fill:lightred,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:lighttrcoas,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:lightpurple,stroke:black,stroke-width:2px,shadow:shadow
    style G fill:orange,stroke:darkblue,stroke-width:4px,shadow:shadow
    style S fill:lightblue,stroke:darkblue,stroke-width:4px,shadow:shadow
```

---
