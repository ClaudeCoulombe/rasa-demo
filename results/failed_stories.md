## happy path 1 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: deny: amazing -->
    - utter_happy   <!-- predicted: utter_aurevoir -->


## happy path 2 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: deny: amazing -->
    - utter_happy   <!-- predicted: utter_aurevoir -->
* goodbye: bye-bye!   <!-- predicted: pension_alimentaire: bye-bye! -->
    - utter_goodbye   <!-- predicted: utter_pension_alimentaire -->


## sad path 1 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: affirm: not good -->
    - utter_cheer_up   <!-- predicted: utter_aurevoir -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* affirm: yes   <!-- predicted: pension_alimentaire: yes -->
    - utter_happy   <!-- predicted: utter_pension_alimentaire -->


## sad path 2 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: affirm: not good -->
    - utter_cheer_up   <!-- predicted: utter_aurevoir -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: not really
    - utter_goodbye   <!-- predicted: utter_aurevoir -->


## sad path 3 (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* greet: hi   <!-- predicted: affirm: hi -->
    - utter_greet   <!-- predicted: utter_aurevoir -->
* mood_unhappy: very terrible   <!-- predicted: deny: very terrible -->
    - utter_cheer_up   <!-- predicted: utter_aurevoir -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: no
    - utter_goodbye   <!-- predicted: utter_aurevoir -->


## say goodbye (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* goodbye: bye-bye!   <!-- predicted: pension_alimentaire: bye-bye! -->
    - utter_goodbye   <!-- predicted: utter_pension_alimentaire -->


## bot challenge (/var/folders/dm/pd9d_lsn07d91v_vxkckz8p80000gn/T/tmpbqg0g_fc/cb2f8046ddc34b929ee38f725514a8a4_conversation_tests.md)
* bot_challenge: are you a bot?   <!-- predicted: jesuisunrobot: are you a bot? -->
    - utter_iamabot   <!-- predicted: utter_jesuisunrobot -->


