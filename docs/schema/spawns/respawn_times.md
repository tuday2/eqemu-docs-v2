# respawn_times

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmVzcGF3bl90aW1lcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBzbWFsbGludCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bjIge1xuICAgICAgICBpbnQgcGF0aGdyaWRcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICAgICAgaW50IHNwYXduZ3JvdXBJRFxuICAgICAgICBzbWFsbGludCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgIH1cbiAgICBpbnN0YW5jZV9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICB9XG4gICAgcmVzcGF3bl90aW1lcyB8fC0tb3sgc3Bhd24yIDogXCJPbmUtdG8tT25lXCJcbiAgICByZXNwYXduX3RpbWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmVzcGF3bl90aW1lcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBzbWFsbGludCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bjIge1xuICAgICAgICBpbnQgcGF0aGdyaWRcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICAgICAgaW50IHNwYXduZ3JvdXBJRFxuICAgICAgICBzbWFsbGludCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgIH1cbiAgICBpbnN0YW5jZV9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICB9XG4gICAgcmVzcGF3bl90aW1lcyB8fC0tb3sgc3Bhd24yIDogXCJPbmUtdG8tT25lXCJcbiAgICByZXNwYXduX3RpbWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmVzcGF3bl90aW1lcyB7XG4gICAgICAgIGludCBpZFxuICAgICAgICBzbWFsbGludCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bjIge1xuICAgICAgICBpbnQgcGF0aGdyaWRcbiAgICAgICAgaW50IGlkXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICAgICAgaW50IHNwYXduZ3JvdXBJRFxuICAgICAgICBzbWFsbGludCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgIH1cbiAgICBpbnN0YW5jZV9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICB9XG4gICAgcmVzcGF3bl90aW1lcyB8fC0tb3sgc3Bhd24yIDogXCJPbmUtdG8tT25lXCJcbiAgICByZXNwYXduX3RpbWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | id | [spawn2](../../schema/spawns/spawn2.md) | id |
| One-to-One | instance_id | [instance_list](../../schema/instances/instance_list.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Respawn Time Identifier |
| start | int | Start UNIX Timestamp |
| duration | int | Duration in Seconds |
| instance_id | smallint | [Instance Identifier](../../schema/instances/instance_list.md) |

