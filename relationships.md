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
- closest type of relationship (parent child)

## Aggregate

```mermaid 
classDiagram
  Title -- Genre
  Title *-- Season
  Title *-- Review
  Title o-- Actor
```
- closer than association but looser than composite
- parent child where the child can exist independently 
