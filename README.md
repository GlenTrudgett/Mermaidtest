# Mermaidtest
this is to test Mermaid diagrams

```mermaid
flowchart TD
  A[Deploy to production] --> B{Is it Friday?};
  B -- Yes --> C[Do Not Deploy!];
  B -- No --> D[Run deploy.sh to deploy!];
  C ----> E[Enjoy your weekend!];
  D ----> E{Enjoy your weekend!];
```
