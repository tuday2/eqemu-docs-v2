# spawn_condition_values

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgc3Bhd25fY29uZGl0aW9uX3ZhbHVlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgICAgICBpbnR1bnNpZ25lZCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25zIHtcbiAgICAgICAgbWVkaXVtaW50dW5zaWduZWQgaWRcbiAgICAgICAgdmFyY2hhciB6b25lXG4gICAgfVxuICAgIGluc3RhbmNlX2xpc3Qge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZVxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBzcGF3bl9jb25kaXRpb25zIDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgc3Bhd25fY29uZGl0aW9uX3ZhbHVlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgICAgICBpbnR1bnNpZ25lZCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25zIHtcbiAgICAgICAgbWVkaXVtaW50dW5zaWduZWQgaWRcbiAgICAgICAgdmFyY2hhciB6b25lXG4gICAgfVxuICAgIGluc3RhbmNlX2xpc3Qge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZVxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBzcGF3bl9jb25kaXRpb25zIDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgc3Bhd25fY29uZGl0aW9uX3ZhbHVlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgem9uZVxuICAgICAgICBpbnR1bnNpZ25lZCBpbnN0YW5jZV9pZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25zIHtcbiAgICAgICAgbWVkaXVtaW50dW5zaWduZWQgaWRcbiAgICAgICAgdmFyY2hhciB6b25lXG4gICAgfVxuICAgIGluc3RhbmNlX2xpc3Qge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgem9uZVxuICAgICAgICB0aW55aW50dW5zaWduZWQgdmVyc2lvblxuICAgIH1cbiAgICB6b25lIHtcbiAgICAgICAgaW50IHpvbmVpZG51bWJlclxuICAgICAgICB2YXJjaGFyIHNob3J0X25hbWVcbiAgICAgICAgdGlueWludHVuc2lnbmVkIHZlcnNpb25cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBzcGF3bl9jb25kaXRpb25zIDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyBpbnN0YW5jZV9saXN0IDogXCJPbmUtdG8tT25lXCJcbiAgICBzcGF3bl9jb25kaXRpb25fdmFsdWVzIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | id | [spawn_conditions](../../schema/spawns/spawn_conditions.md) | id |
| One-to-One | instance_id | [instance_list](../../schema/instances/instance_list.md) | id |
| One-to-One | zone | [zone](../../schema/zone/zone.md) | short_name |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | [Spawn Condition Identifier](spawn_conditions.md) |
| value | tinyint | Value |
| zone | varchar | [Zone Short Name](../../../../server/zones/zone-list) |
| instance_id | int | [Instance Identifier](../../schema/instances/instance_list.md) |

