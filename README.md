# Call-Notes
## Overview
Using this for working: https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default

## Changes
---
### Upcoming Changes

##### Update "Compress" button
 - Add option for tag suppression
 - Update name to "Ticket"


##### Formatting Button for "Follow-ups"

#### Button for just the subject

#### Container for next ticket

#### Epic questions
```
Issue / Request Description = ___
Error Message = ___

Is this inpatient or outpatient? = ___

User ID = ___
Job Title/Role = ___
Department = ___
Epic Template used = 
___{
Inpatient - ClinDoc [100017]
Ambulatory [100001]

Professional Billing [100026] 
Hospital Billing [100015]
Inpatient - Orders [100018]

Anesthesia [100002]
ASAP [100003]
Cadence [100007]
Grand Central [100000]
HIM [100012]
OPTIME [100022]
Radiant [100027]
Research [100030]
Stork [100033]
___}

PC Name = ___


*** Troubleshooting steps ***
Result: ___.resolve  nonESD  in-progress
___
Did the user have access before? (if applicable) = ___
Is this occurring for several patients in Epic? = ___
Is this issue affecting several co-workers? = ___
Have you restarted user's VDI session? (If applicable) = ___
Screenshot of error / issue attached? = ___.yes
____
___.Was provided colleague with correct interface: ___
___.Colleague had the following template: ___

---

Ticket Reassignment = Tier 2
Reason = technical / access per KB
Escalation needed? = Y - per KB
> Epic - Ticket# ___ (__)
Priority Change = ___.P3 due to expressed urgency

---

Patient Name = 
MRN =   
Patient DOB = 

<MID_DOC>

---

____
User did not have this > advised user to speak to Epic Final Approver to have this template assigned to them.

Final Approvers can be looked-up at this location: https://share.nychhc.org/sites/ProjectGo/gf/PGL/Epic Security/Forms/AllItems.aspx?RootFolder=/sites/ProjectGo/gf/PGL/Epic Security/Epic Final Approvers Lists

<MID_DOC>
```

##### VDI output section
 - input to PC section
 - leave PC name
 - append VDI format to end of notes


##### Add "OUTBOUND" and "CALL" under list of call types


##### Parallel Tickets
 - Stick another ticket on the side
 - Button in the top row with text box containing alt Ticket number
 - Press a button to swap the active ticket in the collapsed spot.
 - How to clear? Press "Next Call" and then swap and then "Next Call" again.


##### Escalation Revamp

###### Escalate for time

###### Bring escalation text into the Troublshooting notes


##### Make Macro-creator 2

###### Send-up text

###### Template for Chat message for AD Account reactivation
```

AD Account reactivation
Can someone re-enable this account for me please?
User ID = ___
Facility = ___
INC000000000
Activation condition = ___.Active in PeopleSoft / Inactive in PeopleSoft, but IIQ has future start date
```

###### Add quick-format for PC profile
 - `PC is = __.stationary desktop / WOW > ___.separate / combined tower-monitor`

###### Add quick-format for PHI details
```

Patient name = 
DOB = 
MRN = 
```


---

### Most Recent Changes

#### 6/16/2022

#### Name field
 - dedicated field to capture Full Name
 - updated Call formatting to incorporate this


---
### Past Versions' Changes
---
---

#### 6/13/2022

##### "Copy Ticket" button
 - Option for "create" button that just removes ticket number

##### Emojis to replace the buttons on top
 - "Next Call" > ⏭📞
 - "Extra Ticket" > ➕🎫(-)
 - "Copy Ticket" > ➕🎫(📄)

##### Location notation
 - Drop down for "Remote / Onsite"
 - Drop down for Facility and text box for More info

#### 5/25/2022

##### Update "Extra ticket" to keep PC name also

##### Bomgar Button update > Reboot time
 - Move reboot time to troubleshooting notes

##### Escalation option > pull out riders
 - Escalation dropdown
 - "Affecting Patient Care" option > change to check box or secondary option
 - reset with changed ticket

##### Escalation option > Add "PeopleSoft"

---

#### 5/23/2022

#### Fast load / outage templates
 - square on the side that doesn't get deleted
 - button to add to Call Notes & Troubleshooting fields

#### Expand Ticket ID field
 - to hold more than 1 ticket number


#### User ID > UPPERCASE & lowercase
 - not sure if it should go in the processor field or just be a feature of the username field
 - take out of tab index

#### Added Phone Field
 - made it hidden
 - added it to the Cleaning method
 - exempted it when creating an Extra Ticket

##### Generate Call template
```
Caller = 
Callback = 
For = 
```
---

#### 5/20/2022

##### Fix Category
 - incident > issue

##### Skip KBID field & CI button in Tabbing
 - Knocked-down within the tabbing order compared to the other field

##### Add shortcut for unknown PC
 - PC field
 - `(unable to obtain)`
 - add instead of replace

##### Escalation option > blank
 - Escalation dropdown
 - ___ option
 - reset with changed ticket

---
