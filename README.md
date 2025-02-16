# n8n-test

Stands up n8n from a docker compose
assumes that the volume has already been created for the config

also sets the domain to be one I owm and have configured externally - this was to make some oauth callbacks work 

## Seems good

it uses lang chain under the hood.
seems quite good - but want to do more work with lang-chain directly before i start to use this as am unsure what compromises / assumptions / opportunities are being traded off


Once credentials were configured then things were simple - but felt like not much control. However didn't really get into prompt engineering.
'Debugging' is very vague because at the end of the day there is nothing like a state machine - to get the consistency i want it would almost be easier to just write a load of functions using ittt or something and have this trigger those chains.

taking an trigger (eg chat) and doing a chain of events eg creating calendar invites, emailing people setting up reminders etc
was easy 


