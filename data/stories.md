## new rasa user
* greet
  - utter_greet
* name{"name":"Alice"}
  - utter_ask_location
* location{"location":"New York"}
  - utter_used_rasa
* deny
  - utter_docs

## existing rasa user 1
* greet
  - utter_greet
* name{"name":"Tom"}
  - utter_ask_location
* location{"location":"Berlin"}
  - utter_used_rasa
* affirm
  - utter_send_blog
* subscribe
  - action_subscribe
* goodbye
  - utter_goodbye

## New Story

* greet
    - utter_greet
* name{"name":"Tom"}
    - utter_ask_location
* location{"location":"Berlin"}
    - slot{"location":"Berlin"}
    - slot{"location":"Berlin"}
    - utter_used_rasa
* deny
    - utter_docs
* thanks
    - slot{"location":"Berlin"}
    - utter_thanks

## New Story

* greet
    - utter_greet
* name{"name":"Tom"}
    - utter_ask_location
* location{"location":"Berlin"}
    - slot{"location":"Berlin"}
    - slot{"location":"Berlin"}
    - utter_used_rasa
* deny
    - utter_docs
* thanks
    - utter_thanks
* goodbye
    - slot{"location":"Berlin"}
    - utter_goodbye

## New Story

* greet
    - utter_greet
* name{"name":"Tom"}
    - utter_ask_location
* location{"location":"Berlin"}
    - slot{"location":"Berlin"}
    - utter_used_rasa
* deny
    - utter_docs
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* thanks
    - utter_eating
* tv
    - utter_yes

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* thanks

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* greet
    - utter_qst1
* tv
    - utter_eating

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* greet
    - utter_qst1
* tv
    - utter_eating2

## New Story

* greet
    - utter_greet
* name
    - utter_bot
* chitchat
    - utter_eating
* tv

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* location
    - utter_eating
* tv
    - utter_ok

## New Story

* greet
    - utter_greet
* chitchat
    - utter_fine
* location
    - utter_eating
* tv
    - utter_ok
