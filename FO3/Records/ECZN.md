ECZN
====

Encounter Zone

## Format

Count | Field | Name | Type | Info
------|-------|------|------|-----
+ | EDID | Editor ID | cstring |
+ | DATA | | struct |

### DATA

Count | Name | Type | Info
------|------|------|-----
 | Owner | formid | FormID of an [NPC_](NPC_.md) or [FACT](FACT.md) record, or null.
 | Rank | int8 |
 | Minnimum Level | int8 |
 | Flags | uint8 | See below for values.
 | Unused | uint8 | 
 
#### Flag Values

Value | Meaning
------|--------
0x01 | Never Resets
0x02 | Match PC Below Minimum Level
