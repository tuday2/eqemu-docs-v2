# merc_stance_entries

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbWVyY19zdGFuY2VfZW50cmllcyB7XG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCBzdGFuY2VfaWRcbiAgICB9XG4gICAgbWVyY19zcGVsbF9saXN0X2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjX3NwZWxsX2xpc3RfaWRcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHN0YW5jZV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzcGVsbF9pZFxuICAgIH1cbiAgICBtZXJjX3N0YW5jZV9lbnRyaWVzIHx8LS1veyBtZXJjX3NwZWxsX2xpc3RfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbWVyY19zdGFuY2VfZW50cmllcyB7XG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCBzdGFuY2VfaWRcbiAgICB9XG4gICAgbWVyY19zcGVsbF9saXN0X2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjX3NwZWxsX2xpc3RfaWRcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHN0YW5jZV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzcGVsbF9pZFxuICAgIH1cbiAgICBtZXJjX3N0YW5jZV9lbnRyaWVzIHx8LS1veyBtZXJjX3NwZWxsX2xpc3RfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgbWVyY19zdGFuY2VfZW50cmllcyB7XG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCBzdGFuY2VfaWRcbiAgICB9XG4gICAgbWVyY19zcGVsbF9saXN0X2VudHJpZXMge1xuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjX3NwZWxsX2xpc3RfaWRcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHN0YW5jZV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzcGVsbF9pZFxuICAgIH1cbiAgICBtZXJjX3N0YW5jZV9lbnRyaWVzIHx8LS1veyBtZXJjX3NwZWxsX2xpc3RfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | stance_id | [merc_spell_list_entries](../../schema/mercenaries/merc_spell_list_entries.md) | stance_id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| merc_stance_entry_id | int | Unique Mercenary Stance Entry Identifier |
| class_id | int | [Class Identifier](../../../../categories/player/class-list) |
| proficiency_id | tinyint | Proficiency Identifier |
| stance_id | tinyint | [Stance Type Identifier](../../../../server/bots/stance-types) |
| isdefault | tinyint | Is Default: 0 = False, 1 = True |

