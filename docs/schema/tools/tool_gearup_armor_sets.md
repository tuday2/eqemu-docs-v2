# tool_gearup_armor_sets

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdG9vbF9nZWFydXBfYXJtb3Jfc2V0cyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgfVxuICAgIGl0ZW1zIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnQgYm9va1xuICAgICAgICBpbnQgaWNvblxuICAgICAgICBzbWFsbGludCBiYXJkZWZmZWN0XG4gICAgICAgIGludCBjbGlja2VmZmVjdFxuICAgICAgICBpbnQgZm9jdXNlZmZlY3RcbiAgICAgICAgaW50IHByb2NlZmZlY3RcbiAgICAgICAgaW50IHNjcm9sbGVmZmVjdFxuICAgICAgICBpbnQgd29ybmVmZmVjdFxuICAgICAgICBpbnQgcmVjYXN0dHlwZVxuICAgIH1cbiAgICB0b29sX2dlYXJ1cF9hcm1vcl9zZXRzIHx8LS1veyBpdGVtcyA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdG9vbF9nZWFydXBfYXJtb3Jfc2V0cyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgfVxuICAgIGl0ZW1zIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnQgYm9va1xuICAgICAgICBpbnQgaWNvblxuICAgICAgICBzbWFsbGludCBiYXJkZWZmZWN0XG4gICAgICAgIGludCBjbGlja2VmZmVjdFxuICAgICAgICBpbnQgZm9jdXNlZmZlY3RcbiAgICAgICAgaW50IHByb2NlZmZlY3RcbiAgICAgICAgaW50IHNjcm9sbGVmZmVjdFxuICAgICAgICBpbnQgd29ybmVmZmVjdFxuICAgICAgICBpbnQgcmVjYXN0dHlwZVxuICAgIH1cbiAgICB0b29sX2dlYXJ1cF9hcm1vcl9zZXRzIHx8LS1veyBpdGVtcyA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdG9vbF9nZWFydXBfYXJtb3Jfc2V0cyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgfVxuICAgIGl0ZW1zIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnQgYm9va1xuICAgICAgICBpbnQgaWNvblxuICAgICAgICBzbWFsbGludCBiYXJkZWZmZWN0XG4gICAgICAgIGludCBjbGlja2VmZmVjdFxuICAgICAgICBpbnQgZm9jdXNlZmZlY3RcbiAgICAgICAgaW50IHByb2NlZmZlY3RcbiAgICAgICAgaW50IHNjcm9sbGVmZmVjdFxuICAgICAgICBpbnQgd29ybmVmZmVjdFxuICAgICAgICBpbnQgcmVjYXN0dHlwZVxuICAgIH1cbiAgICB0b29sX2dlYXJ1cF9hcm1vcl9zZXRzIHx8LS1veyBpdGVtcyA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | item_id | [items](../../schema/items/items.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| class | tinyint | [Class](../../../../categories/player/class-list) |
| level | smallint | Level |
| slot | tinyint | [Slot Identifier](../../../../server/inventory/inventory-slots) |
| item_id | int | [Item Identifier](../../schema/items/items.md) |
| score | mediumint | Score |
| expansion | tinyint | [Expansion](../../../../server/operation/expansion-list) |

