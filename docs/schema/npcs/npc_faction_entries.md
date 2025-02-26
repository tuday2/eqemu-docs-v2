# npc_faction_entries

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbnBjX2ZhY3Rpb25fZW50cmllcyB7XG4gICAgICAgIGludHVuc2lnbmVkIG5wY19mYWN0aW9uX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGZhY3Rpb25faWRcbiAgICB9XG4gICAgZmFjdGlvbl9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgfVxuICAgIG5wY19mYWN0aW9uIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludCBwcmltYXJ5ZmFjdGlvblxuICAgIH1cbiAgICBucGNfZmFjdGlvbl9lbnRyaWVzIHx8LS1veyBmYWN0aW9uX2xpc3QgOiBcIk9uZS10by1PbmVcIlxuICAgIG5wY19mYWN0aW9uX2VudHJpZXMgfHwtLW97IG5wY19mYWN0aW9uIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbnBjX2ZhY3Rpb25fZW50cmllcyB7XG4gICAgICAgIGludHVuc2lnbmVkIG5wY19mYWN0aW9uX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGZhY3Rpb25faWRcbiAgICB9XG4gICAgZmFjdGlvbl9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgfVxuICAgIG5wY19mYWN0aW9uIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludCBwcmltYXJ5ZmFjdGlvblxuICAgIH1cbiAgICBucGNfZmFjdGlvbl9lbnRyaWVzIHx8LS1veyBmYWN0aW9uX2xpc3QgOiBcIk9uZS10by1PbmVcIlxuICAgIG5wY19mYWN0aW9uX2VudHJpZXMgfHwtLW97IG5wY19mYWN0aW9uIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbnBjX2ZhY3Rpb25fZW50cmllcyB7XG4gICAgICAgIGludHVuc2lnbmVkIG5wY19mYWN0aW9uX2lkXG4gICAgICAgIGludHVuc2lnbmVkIGZhY3Rpb25faWRcbiAgICB9XG4gICAgZmFjdGlvbl9saXN0IHtcbiAgICAgICAgaW50IGlkXG4gICAgfVxuICAgIG5wY19mYWN0aW9uIHtcbiAgICAgICAgaW50IGlkXG4gICAgICAgIGludCBwcmltYXJ5ZmFjdGlvblxuICAgIH1cbiAgICBucGNfZmFjdGlvbl9lbnRyaWVzIHx8LS1veyBmYWN0aW9uX2xpc3QgOiBcIk9uZS10by1PbmVcIlxuICAgIG5wY19mYWN0aW9uX2VudHJpZXMgfHwtLW97IG5wY19mYWN0aW9uIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | faction_id | [faction_list](../../schema/factions/faction_list.md) | id |
| One-to-One | npc_faction_id | [npc_faction](../../schema/npcs/npc_faction.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| npc_faction_id | int | [NPC Faction Identifier](npc_faction.md) |
| faction_id | int | [Faction Identifier](../../schema/factions/faction_list.md) |
| value | int | Value |
| npc_value | tinyint | NPC Value: -1 = Attack, 0 = Neutral, 1 = Assist |
| temp | tinyint | Temeporary: 0 = Faction is permanent, player recieves a message, 1 = Faction is temporary, player does not recieve a message, 2 = Faction is temporary, player recieves a message, 3 = Faction is permanent, but player does not recieve a message. |

