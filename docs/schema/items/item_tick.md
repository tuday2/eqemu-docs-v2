# item_tick

!!! info
	This page was last generated 2023.06.12

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgaXRlbV90aWNrIHtcbiAgICAgICAgaW50IGl0X2l0ZW1pZFxuICAgICAgICB2YXJjaGFyIGl0X3FnbG9iYWxcbiAgICB9XG4gICAgaXRlbXMge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBuYW1lXG4gICAgICAgIGludCBib29rXG4gICAgICAgIGludCBpY29uXG4gICAgICAgIHNtYWxsaW50IGJhcmRlZmZlY3RcbiAgICAgICAgaW50IGNsaWNrZWZmZWN0XG4gICAgICAgIGludCBmb2N1c2VmZmVjdFxuICAgICAgICBpbnQgcHJvY2VmZmVjdFxuICAgICAgICBpbnQgc2Nyb2xsZWZmZWN0XG4gICAgICAgIGludCB3b3JuZWZmZWN0XG4gICAgICAgIGludCByZWNhc3R0eXBlXG4gICAgfVxuICAgIHF1ZXN0X2dsb2JhbHMge1xuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICBpbnQgbnBjaWRcbiAgICAgICAgaW50IHpvbmVpZFxuICAgIH1cbiAgICBpdGVtX3RpY2sgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcbiAgICBpdGVtX3RpY2sgfHwtLW97IHF1ZXN0X2dsb2JhbHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgaXRlbV90aWNrIHtcbiAgICAgICAgaW50IGl0X2l0ZW1pZFxuICAgICAgICB2YXJjaGFyIGl0X3FnbG9iYWxcbiAgICB9XG4gICAgaXRlbXMge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBuYW1lXG4gICAgICAgIGludCBib29rXG4gICAgICAgIGludCBpY29uXG4gICAgICAgIHNtYWxsaW50IGJhcmRlZmZlY3RcbiAgICAgICAgaW50IGNsaWNrZWZmZWN0XG4gICAgICAgIGludCBmb2N1c2VmZmVjdFxuICAgICAgICBpbnQgcHJvY2VmZmVjdFxuICAgICAgICBpbnQgc2Nyb2xsZWZmZWN0XG4gICAgICAgIGludCB3b3JuZWZmZWN0XG4gICAgICAgIGludCByZWNhc3R0eXBlXG4gICAgfVxuICAgIHF1ZXN0X2dsb2JhbHMge1xuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICBpbnQgbnBjaWRcbiAgICAgICAgaW50IHpvbmVpZFxuICAgIH1cbiAgICBpdGVtX3RpY2sgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcbiAgICBpdGVtX3RpY2sgfHwtLW97IHF1ZXN0X2dsb2JhbHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgaXRlbV90aWNrIHtcbiAgICAgICAgaW50IGl0X2l0ZW1pZFxuICAgICAgICB2YXJjaGFyIGl0X3FnbG9iYWxcbiAgICB9XG4gICAgaXRlbXMge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBuYW1lXG4gICAgICAgIGludCBib29rXG4gICAgICAgIGludCBpY29uXG4gICAgICAgIHNtYWxsaW50IGJhcmRlZmZlY3RcbiAgICAgICAgaW50IGNsaWNrZWZmZWN0XG4gICAgICAgIGludCBmb2N1c2VmZmVjdFxuICAgICAgICBpbnQgcHJvY2VmZmVjdFxuICAgICAgICBpbnQgc2Nyb2xsZWZmZWN0XG4gICAgICAgIGludCB3b3JuZWZmZWN0XG4gICAgICAgIGludCByZWNhc3R0eXBlXG4gICAgfVxuICAgIHF1ZXN0X2dsb2JhbHMge1xuICAgICAgICB2YXJjaGFyIG5hbWVcbiAgICAgICAgaW50IGNoYXJpZFxuICAgICAgICBpbnQgbnBjaWRcbiAgICAgICAgaW50IHpvbmVpZFxuICAgIH1cbiAgICBpdGVtX3RpY2sgfHwtLW97IGl0ZW1zIDogXCJPbmUtdG8tT25lXCJcbiAgICBpdGVtX3RpY2sgfHwtLW97IHF1ZXN0X2dsb2JhbHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | it_itemid | [items](../../schema/items/items.md) | id |
| Has-Many | it_qglobal | [quest_globals](../../schema/data-storage/quest_globals.md) | name |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| it_itemid | int | [Item Identifier](items.md) |
| it_chance | int | Chance: 0 = Never, 100 = Always |
| it_level | int | Level |
| it_id | int | [Spell Identifier](../../schema/spells/spells_new.md) |
| it_qglobal | varchar | [Quest Global Identifier](../../schema/data-storage/quest_globals.md) (Deprecated) |
| it_bagslot | tinyint | [Bag Slot](../../../../server/inventory/inventory-slots) |

