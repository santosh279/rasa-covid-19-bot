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

## story_know_features
* know_features
  - utter_features

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## story - affirm
* affirm
  - utter_no_problem

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## story_joke_01
* nonexisting_service
  - utter_no_such_service

## story_check_humanity
* check_humanity
  - utter_humanity

## story_love_confession
* love_confession
  - utter_love_rejection

## story - specific question
* specific_question
  - utter_go_on

## story_meet_me
* meet
  - utter_cannot_meet

## story_proposal
* propose
  - utter_proposal_rejection

## story_bot_name
* bot_name
  - utter_bot_name

## story_thanks           
* thanks
  - utter_thanks

## story - negate
* negate
  - utter_negate

## story - what is corona virus
* what_is_corona_virus
  - utter_what_is_corona_virus_answer
  - utter_for_more_about_corona_virus
  - utter_stay_home_stay_safe

## story - worry about corona virus
* worry_about_corona_virus
  - utter_worry_about_corona_virus_answer
  - utter_stay_home_stay_safe
  
## story - healthy tips
* healthy_tips
  - utter_healthy_tips_answer
  - utter_stay_home_stay_safe


## story - covid_tracker
* covid_tracker
  - utter_covid_tracker_answer
  - utter_stay_home_stay_safe