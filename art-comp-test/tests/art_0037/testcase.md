---
group: validation
steps: generate
ac_output match1: ERROR[0037]|9:13|t8|entry point without incoming
ac_output match2: ERROR[0037]|11:13|t6|state
ac_output match3: ERROR[0037]|13:9|t7|state
ac_output match4: ERROR[0037]|18:9|t2|state
ac_output match5: ERROR[0037]|20:9|t4|exit point without incoming
ac_output match6: ERROR[0037]|40:5|inherited transition|entry point without incoming
ac_output match6a: Inherited transition|t1|32:13
ac_output match7: ERROR[0037]|art_0037_inherited_sm.art:23:24|inherited transition|entry point without incoming
ac_output match7a: Inherited transition|txxx|13:17
ac_output match8: ERROR[0037]|art_0037_passive_class.art|7:9|state
---
Test validation rule `ART_0037_missingTriggers`.
