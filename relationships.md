# Relationships 

## Association 

```mermaid
classDiagram 
  Title -- Genre
```

- loosest type 
- no owner of relationship 

## Composite 

```mermaid
classDiagram
  Title -- Genre
  Title *-- Season
  Title *-- Review
```

- diamond is the side holding the reference 

## Aggregate

```mermaid 
classDiagram
  Title -- Genre
  Title *-- Season
  Title *-- Review
  Title o-- Actor
```
