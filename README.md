# Mermaidtest

```mermaid
  flowchart TD;
      A[Deploy to production] --> B{Is it Friday?};
      B -- Yes --> C[Do Not Deploy!];
      B -- No --> D[Run deploy.sh to deploy!];
      C ----> E[Enjoy your weekend!];
      D ----> E{Enjoy your weekend!];
```
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
