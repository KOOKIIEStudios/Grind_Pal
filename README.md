# Grind Pal
This project seeks to build an Android tool to assist MMORPG players (specifically GMS and its variants) with tracking their grinding gains and efficiency on a per map basis.


### Status  
Developmental Progress: ![0%](https://progress-bar.dev/0)\
Current Status: **HALTED**


### Language
Currently supported languages:
  - English

---

### OS Version
#### Target/Compiled Android version:
  - **Android 14** - API Level 34 Revision 2
    - Due to the recent changes in Google's policies, I have decided to simply migrate to the latest available SDK at the time of writing

### Implementation

#### Target game(s):
  - MapleStory

#### Key features:
  1) Calculates NX & Meso rates (EXP mode to be added if there is sufficient demand)
  2) Comes with in-built timer
  3) Organised by map and channel (e.g. RMZ-like MapleStory private servers has buffed channels)
  4) Allows input of notable drops as well as any other notes for each instance (not calculated/scaled)
  5) Best maps/instances shown on the main screen
  6) Full list of prior instances are sortable
  7) Data stored on phone

#### Method of use:
  - Tap on any instance on the main screen to view its details.
  - Tap on the View All button to see all saved instances
  - Tap on any instance on the View All screen to view its details.
  - Tap on the New button to start a new session
  - Key in all the details and hit Start to start the timer
  - Hit Stop to stop the timer, and fill in any remaining details
  - (Optional) Key in an offset value (in seconds) to deduct from the total time (i.e. to account for any delays)
  - Choose to Save or Discard the session's data

Written in: Kotlin (1.9.10)  

README created: 11:56AM 2nd May 2020 +8GMT  
Last edited: 5:15AM 6th Jan 2022 +8GMT  
