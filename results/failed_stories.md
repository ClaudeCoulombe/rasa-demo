## happy path 1 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: affirm: amazing -->
    - utter_happy   <!-- predicted: utter_aurevoir -->


## happy path 2 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: affirm: amazing -->
    - utter_happy   <!-- predicted: utter_aurevoir -->
* goodbye: bye-bye!   <!-- predicted: greet: bye-bye! -->
    - utter_goodbye   <!-- predicted: utter_greet -->


## sad path 1 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: affirm: not good -->
    - utter_cheer_up   <!-- predicted: utter_aurevoir -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* affirm: yes   <!-- predicted: greet: yes -->
    - utter_happy   <!-- predicted: utter_greet -->


## sad path 2 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: affirm: not good -->
    - utter_cheer_up   <!-- predicted: utter_aurevoir -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: not really   <!-- predicted: greet: not really -->
    - utter_goodbye   <!-- predicted: utter_greet -->


## sad path 3 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* greet: hi   <!-- predicted: affirm: hi -->
    - utter_greet   <!-- predicted: utter_aurevoir -->
* mood_unhappy: very terrible   <!-- predicted: mediation: very terrible -->
    - utter_cheer_up   <!-- predicted: utter_mediation -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: no
    - utter_goodbye   <!-- predicted: utter_divorce -->


## say goodbye (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* goodbye: bye-bye!   <!-- predicted: greet: bye-bye! -->
    - utter_goodbye   <!-- predicted: utter_greet -->


## bot challenge (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpecce68i4/98b6157a8f0f42dba62be5cac3d9b5ee_conversation_tests.md)
* bot_challenge: are you a bot?   <!-- predicted: greet: are you a bot? -->
    - utter_iamabot   <!-- predicted: utter_greet -->


