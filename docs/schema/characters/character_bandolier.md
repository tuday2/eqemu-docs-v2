# character_bandolier

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGl0ZW1faWRcbiAgICB9XG4gICAgY2hhcmFjdGVyX2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZV9pbnN0YW5jZVxuICAgIH1cbiAgICBpdGVtcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGJvb2tcbiAgICAgICAgaW50IGljb25cbiAgICAgICAgc21hbGxpbnQgYmFyZGVmZmVjdFxuICAgICAgICBpbnQgY2xpY2tlZmZlY3RcbiAgICAgICAgaW50IGZvY3VzZWZmZWN0XG4gICAgICAgIGludCBwcm9jZWZmZWN0XG4gICAgICAgIGludCBzY3JvbGxlZmZlY3RcbiAgICAgICAgaW50IHdvcm5lZmZlY3RcbiAgICAgICAgaW50IHJlY2FzdHR5cGVcbiAgICB9XG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB8fC0tb3sgY2hhcmFjdGVyX2RhdGEgOiBcIk9uZS10by1PbmVcIlxuICAgIGNoYXJhY3Rlcl9iYW5kb2xpZXIgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGl0ZW1faWRcbiAgICB9XG4gICAgY2hhcmFjdGVyX2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZV9pbnN0YW5jZVxuICAgIH1cbiAgICBpdGVtcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGJvb2tcbiAgICAgICAgaW50IGljb25cbiAgICAgICAgc21hbGxpbnQgYmFyZGVmZmVjdFxuICAgICAgICBpbnQgY2xpY2tlZmZlY3RcbiAgICAgICAgaW50IGZvY3VzZWZmZWN0XG4gICAgICAgIGludCBwcm9jZWZmZWN0XG4gICAgICAgIGludCBzY3JvbGxlZmZlY3RcbiAgICAgICAgaW50IHdvcm5lZmZlY3RcbiAgICAgICAgaW50IHJlY2FzdHR5cGVcbiAgICB9XG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB8fC0tb3sgY2hhcmFjdGVyX2RhdGEgOiBcIk9uZS10by1PbmVcIlxuICAgIGNoYXJhY3Rlcl9iYW5kb2xpZXIgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIGludHVuc2lnbmVkIGl0ZW1faWRcbiAgICB9XG4gICAgY2hhcmFjdGVyX2RhdGEge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZV9pbnN0YW5jZVxuICAgIH1cbiAgICBpdGVtcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGJvb2tcbiAgICAgICAgaW50IGljb25cbiAgICAgICAgc21hbGxpbnQgYmFyZGVmZmVjdFxuICAgICAgICBpbnQgY2xpY2tlZmZlY3RcbiAgICAgICAgaW50IGZvY3VzZWZmZWN0XG4gICAgICAgIGludCBwcm9jZWZmZWN0XG4gICAgICAgIGludCBzY3JvbGxlZmZlY3RcbiAgICAgICAgaW50IHdvcm5lZmZlY3RcbiAgICAgICAgaW50IHJlY2FzdHR5cGVcbiAgICB9XG4gICAgY2hhcmFjdGVyX2JhbmRvbGllciB8fC0tb3sgY2hhcmFjdGVyX2RhdGEgOiBcIk9uZS10by1PbmVcIlxuICAgIGNoYXJhY3Rlcl9iYW5kb2xpZXIgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | id | [character_data](../../schema/characters/character_data.md) | id |
| One-to-One | item_id | [items](../../schema/items/items.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | [Character Identifier](character_data.md) |
| bandolier_id | tinyint | Bandolier Identifier |
| bandolier_slot | tinyint | Slot |
| item_id | int | [Item Identifier](../../schema/items/items.md) |
| icon | int | Icon |
| bandolier_name | varchar | Name |

