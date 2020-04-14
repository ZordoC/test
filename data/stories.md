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

## ask symptoms
* faq/ask_symptoms
-Do you feel any of these symptoms ? Cough, Fever , Tiredness , Difficylty breathing? If so, contact your country's phone support line !

## ask risk
* faq/ask_risk
  - If you are above 60 years old and with pre existing health contions like high blood pleassure, heart , lung dieases , cancer or diabites.

## ask transmission
* faq/ask_transmission
 - The disease spreads from human contact, if someone coughs or exhales, or by touching contaminated surfaces and your nose/mouth

## Some question from FAQ
* faq
    - respond_faq

## ask affected countries
* faq/ask_affected_countries
 - The most affected countries at the moment are: USA , Spain, Italy, France, Germany and the UK.

##  ask counter_measures
* faq/ask_counter_measures
 - There's still no method of getting imunity to the virus, either via vaccine or drugs, protective equipement is found the most effective
