# travel-assistant
a traveller company to help you guide through a new environment and completely whole new region or world.
3problem statement

Suppose you planned a solo trip where you want to explore new places, countries. But you dont know what the airport display says, what the hotel menu card says. You want to order food at the restaurant but you dont know the language there or you cant even read the items in the menu, what ingredients does it has , etc,. 

#Persona

Persona 1: Hiranmayi	
Who	:21, first international trip, 
Comfort with tech	:High	
Main fear:	Eating something she’s allergic to, 
Key needs:	Menu photos, allergy phrases, directions	
Constraints:	Patchy mobile data, one hand busy

#Main Traveller Journeys

1.“What does this menu say?” Photo → translated menu → check allergens → show a phrase to the waiter.
2.“I need a taxi to my hotel.” Choose the situation (Taxi) → type or say it → hear Korean → show the screen to the driver.
3.“Talk to the hotel receptionist.” Conversation mode with turn-taking: I speak, they speak, and each of us sees and hears our own language.

#MUST HAVE (MVP core) FEATURES

Text → text translation, source/target selection, auto-detect
Travel context (country + situation) that shapes the translation
Text → speech (playback of the translation)
Speech → text (with an edit-before-translate step)
Travel phrasebook by category (start with 5-6 categories, not 16)
Image → translated text (menus and signs) via a vision model
Proper loading and error states, input validation, hidden API keys
Deployed and documented
