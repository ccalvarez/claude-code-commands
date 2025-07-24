# mermaid-diagrams
You are given the following context:
$ARGUMENTS

Create Mermaid diagrams to visualize the provided code.

**Diagram Types to Generate:**

**1. Flowchart** (for process flows)
```mermaid
flowchart TD
    A[Start] --> B{Decision}
    B -->|Yes| C[Action 1]
    B -->|No| D[Action 2]
```

**2. Sequence Diagram** (for API interactions)
```mermaid
sequenceDiagram
    User->>API: Request
    API->>Database: Query
    Database-->>API: Response
    API-->>User: Result
```

**3. Class Diagram** (for object relationships)
```mermaid
classDiagram
    class User {
        +String name
        +authenticate()
    }
```

**4. Entity Relationship** (for database schemas)
```mermaid
erDiagram
    USER ||--o{ ORDER : places
    ORDER ||--|{ ORDER-ITEM : contains
```

**Instructions:**
1. Analyze the code structure
2. Identify key components and relationships
3. Choose appropriate diagram type(s)
4. Create clear, labeled diagrams
5. Add explanatory text for each diagram

Make diagrams easy to understand for both technical and non-technical stakeholders.