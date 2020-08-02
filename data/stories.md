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

## thank
* thank
  - utter_noworries

# faq corona virus
* faq
  - respond_faq

## interactive_story_1
* greet
  - utter_greet

## know_number_of_cases
* number_case
  - utter_state_name

## corona_state_tracker
* corona_state
  - action_corona_tracker

