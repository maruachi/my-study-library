1\.
```mermaid
flowchart LR
    A[구매] --> B;
    B[유저, 파라미터, \n 어뷰징 검증] --> C;
    C{client가 안드로이드} -->|Yes| E;
    C -->|No| G;
    E[안드로이드 Proxy 처리] --> G;
    G[DB 저장] --> I;
    I[응답 반환];
```

2\.
```mermaid
flowchart LR
    id[(Database)]
```

3\.
```mermaid
flowchart LR
    id{조건}
```

4\.
```mermaid
flowchart LR
    A[Service]
    B[(Database_1)]
    C[(Database_2)]
    A --> B --- C
```

5\.
```mermaid
flowchart LR
    C -.-> id2{box}
```

6\.
```mermaid
flowchart LR
    A-->|의존|B
```

7\.
```mermaid
flowchart LR
    A[Service]
    B[(Database_1)]
    C[(Database_2)]
    A-->B
    A-->C
```
