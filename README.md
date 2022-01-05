# Grind Pal
This project seeks to build an Android tool to assist MMORPG players (specifically GMS and its variants) with tracking their grinding gains and efficiency on a per map basis.


### Status  
Developmental Progress: ![0%](https://progress-bar.dev/0)\
Current Status: **HALTED**


### Language
Currently supported languages:
  - English
    
Languages to support:
  - Chinese
  - Vietnamese
  - Dutch

---

### OS Version
#### Target Android version:
  - **Android 11.0 (R)** - API Level 30 Revision 3
    - Roughly 17.73% of all Android users, as of 13th Oct 2021
    - API Level 30 or higher is mandated by Google Play store requirements, as of 13th Oct 2021  

#### Compiled Android Version:
  - **Android 11.0 (R)** - API Level 30 Revision 3
    - To follow the target API level  

#### Minimum Android version:
  - **Android 7.0 (Nougat)** - API Level 24 Revision 2
    - Supports >91% of all Android users, as of 13th Oct 2021  

---

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

Written in: Kotlin (1.5.31)  

README created: 11:56AM 2nd May 2020 +8GMT  
Last edited: 5:15AM 6th Jan 2022 +8GMT  
