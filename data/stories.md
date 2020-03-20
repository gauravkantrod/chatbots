## veg_path
* greet
  - utter_greet
* user_requirement
  - utter_veg_non_veg
* food_type_veg
  - utter_veg
* veg_order
  - utter_anythingelse
* deny
  - utter_ending_message

## non_veg_path
* greet
  - utter_greet
* user_requirement
  - utter_veg_non_veg
* food_type_non_veg
  - utter_non_veg
* non_veg_order
  - utter_anythingelse
* deny
  - utter_ending_message

## beer_path
* greet
  - utter_greet
* user_requirement
  - utter_veg_non_veg
* food_type_non_veg
  - utter_non_veg
* beer_order
  - utter_anythingelse
* deny
  - utter_ending_message


## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
