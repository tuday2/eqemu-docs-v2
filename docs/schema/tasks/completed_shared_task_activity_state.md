# completed_shared_task_activity_state

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHtcbiAgICAgICAgaW50IGFjdGl2aXR5X2lkXG4gICAgICAgIGJpZ2ludCBzaGFyZWRfdGFza19pZFxuICAgIH1cbiAgICB0YXNrX2FjdGl2aXRpZXMge1xuICAgICAgICB2YXJjaGFyIGdvYWxpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhY3Rpdml0eWlkXG4gICAgICAgIHZhcmNoYXIgZGVsaXZlcnRvbnBjXG4gICAgICAgIGludHVuc2lnbmVkIHRhc2tpZFxuICAgICAgICB2YXJjaGFyIHpvbmVzXG4gICAgfVxuICAgIHNoYXJlZF90YXNrcyB7XG4gICAgICAgIGJpZ2ludCBpZFxuICAgICAgICBpbnQgdGFza19pZFxuICAgIH1cbiAgICBjb21wbGV0ZWRfc2hhcmVkX3Rhc2tfYWN0aXZpdHlfc3RhdGUgfHwtLW97IHRhc2tfYWN0aXZpdGllcyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHx8LS1veyBzaGFyZWRfdGFza3MgOiBcIk9uZS10by1PbmVcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHtcbiAgICAgICAgaW50IGFjdGl2aXR5X2lkXG4gICAgICAgIGJpZ2ludCBzaGFyZWRfdGFza19pZFxuICAgIH1cbiAgICB0YXNrX2FjdGl2aXRpZXMge1xuICAgICAgICB2YXJjaGFyIGdvYWxpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhY3Rpdml0eWlkXG4gICAgICAgIHZhcmNoYXIgZGVsaXZlcnRvbnBjXG4gICAgICAgIGludHVuc2lnbmVkIHRhc2tpZFxuICAgICAgICB2YXJjaGFyIHpvbmVzXG4gICAgfVxuICAgIHNoYXJlZF90YXNrcyB7XG4gICAgICAgIGJpZ2ludCBpZFxuICAgICAgICBpbnQgdGFza19pZFxuICAgIH1cbiAgICBjb21wbGV0ZWRfc2hhcmVkX3Rhc2tfYWN0aXZpdHlfc3RhdGUgfHwtLW97IHRhc2tfYWN0aXZpdGllcyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHx8LS1veyBzaGFyZWRfdGFza3MgOiBcIk9uZS10by1PbmVcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHtcbiAgICAgICAgaW50IGFjdGl2aXR5X2lkXG4gICAgICAgIGJpZ2ludCBzaGFyZWRfdGFza19pZFxuICAgIH1cbiAgICB0YXNrX2FjdGl2aXRpZXMge1xuICAgICAgICB2YXJjaGFyIGdvYWxpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhY3Rpdml0eWlkXG4gICAgICAgIHZhcmNoYXIgZGVsaXZlcnRvbnBjXG4gICAgICAgIGludHVuc2lnbmVkIHRhc2tpZFxuICAgICAgICB2YXJjaGFyIHpvbmVzXG4gICAgfVxuICAgIHNoYXJlZF90YXNrcyB7XG4gICAgICAgIGJpZ2ludCBpZFxuICAgICAgICBpbnQgdGFza19pZFxuICAgIH1cbiAgICBjb21wbGV0ZWRfc2hhcmVkX3Rhc2tfYWN0aXZpdHlfc3RhdGUgfHwtLW97IHRhc2tfYWN0aXZpdGllcyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY29tcGxldGVkX3NoYXJlZF90YXNrX2FjdGl2aXR5X3N0YXRlIHx8LS1veyBzaGFyZWRfdGFza3MgOiBcIk9uZS10by1PbmVcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | activity_id | [task_activities](../../schema/tasks/task_activities.md) | activityid |
| One-to-One | shared_task_id | [shared_tasks](../../schema/tasks/shared_tasks.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| shared_task_id | bigint | [Shared Task Identifier](shared_tasks.md) |
| activity_id | int | Activity Identifier |
| done_count | int | Done Count |
| updated_time | datetime | Updated Time |
| completed_time | datetime | Completed Time |

