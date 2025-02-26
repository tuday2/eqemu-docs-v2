# raid_details

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmFpZF9kZXRhaWxzIHtcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2xlYWRlcnMge1xuICAgICAgICBpbnR1bnNpZ25lZCByaWRcbiAgICB9XG4gICAgcmFpZF9tZW1iZXJzIHtcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2RldGFpbHMgfHwtLW97IHJhaWRfbGVhZGVycyA6IFwiSGFzLU1hbnlcIlxuICAgIHJhaWRfZGV0YWlscyB8fC0tb3sgcmFpZF9tZW1iZXJzIDogXCJIYXMtTWFueVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmFpZF9kZXRhaWxzIHtcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2xlYWRlcnMge1xuICAgICAgICBpbnR1bnNpZ25lZCByaWRcbiAgICB9XG4gICAgcmFpZF9tZW1iZXJzIHtcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2RldGFpbHMgfHwtLW97IHJhaWRfbGVhZGVycyA6IFwiSGFzLU1hbnlcIlxuICAgIHJhaWRfZGV0YWlscyB8fC0tb3sgcmFpZF9tZW1iZXJzIDogXCJIYXMtTWFueVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcmFpZF9kZXRhaWxzIHtcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2xlYWRlcnMge1xuICAgICAgICBpbnR1bnNpZ25lZCByaWRcbiAgICB9XG4gICAgcmFpZF9tZW1iZXJzIHtcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IHJhaWRpZFxuICAgIH1cbiAgICByYWlkX2RldGFpbHMgfHwtLW97IHJhaWRfbGVhZGVycyA6IFwiSGFzLU1hbnlcIlxuICAgIHJhaWRfZGV0YWlscyB8fC0tb3sgcmFpZF9tZW1iZXJzIDogXCJIYXMtTWFueVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | raidid | [raid_leaders](../../schema/raids/raid_leaders.md) | rid |
| Has-Many | raidid | [raid_members](../../schema/raids/raid_members.md) | raidid |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| raidid | int | Unique Raid Identifier |
| loottype | int | Loot Type |
| locked | tinyint | Locked: 0 = False, 1 = True |
| motd | varchar | Message of the Day |

