---
description: User Acceptance Test for tester
---

# UAT

### Definition

| Cpanel | Member Control Panel |
| :--- | :--- |
| XP | Experience Point |
| RP | Redeemable Point |
| EKYC | Electronic Know Your Customer |

### For Member

#### Membership, Cpanel

* [ ] As a Campus ID member, I understand there are 2 types of membership. One for individual and one for organization.
* [ ] As a registered Central Member, I can signup for Campus ID membership as an individual through Cpanel
* [ ] As a registered Central Member, I can auto EKYC my identity using MyKad for the account I am currently logged in to, through Cpanel. 
  * [ ] Using Blink, my application is instantly approved once auto identification is completed
  * [ ] If Blink fails to auto identify my Identity, the EKYC module is smart enough to fall back to manual method. User should be able to reach this manual method without asking other people for help.
  * [ ] For both process, I can proceed to enroll Campus ID once my EKYC is approved 
* [ ] As a registered Central Member, I can enroll to Campus ID and acquire a Campus ID Membership code \(e.g. 'P99999'\) for my individual profile upon successful enrollment. 
  * [ ] Approved Individual EKYC is part of the requirements.
  * [ ] Terms and conditions will be displayed and I need to click Accept to proceed
  * [ ] I should acquire the membership ID instantly
* [ ] As a registered Central Member, I can enroll to Campus ID and acquire a Campus ID Membership code \(e.g. 'C88888'\) for my organization profile upon successful enrollment.
  * [ ] I can submit an application by providing information like \(SSM Reg No, SSM Company Name, SSM Company Address, SSM copy of documentation\) and have it processed manually
* [ ] As a Campus ID member, I can go to Cpanel homepage and see my current XP and RP there
* [ ] As a Campus ID member, I also can get to Campus ID Member page through Cpanel
  * [ ] My latest XP and RP
  * [ ] My Campus ID membership code
  * [ ] My Campus ID associated EKYC info like full name, MyKad
  * [ ] List of campus ID membership I have access to and able to switch in between them
  * [ ] List of events I participated which has allocated points
  * [ ] I can claim points from the event list
  * [ ] Points claimed are immediately debited into my Campus ID membership account
  * [ ] List of transaction of points
* [ ] After EKYC myself, my profile in Cpanel is sync and locked from updating

#### Quests

* [ ] As a visitor, I can browse the quest page
* [ ] As a visitor, I can click each listed quest for more details

  * [ ] Is the title shown?
  * [ ] Is the oneliner shown below the title?
  * [ ] Is the description shown within the quest listing page?
  * [ ] Can you tell who posted the quest?
  * [ ] Can you tell who can take the quest? \(organization, individual or both\)
  * [ ] How many RP will be given?
  * [ ] How many XP are required?
  * [ ] Does the image within the quest listing shows up?
  * [ ] Does clicking the small image within the quest gives you a higher resolution image?
  * [ ] Quest should only be displayed within the start and end date. Not before or after.

* [ ] As a CampusID member, I can take a quest

  * [ ] I am redirected to a new page with confirmation window
  * [ ] The confirmation window tells me the number of RP I will earn from this quest
  * [ ] The confirmation window tells me my current RP count
  * [ ] I can click either "OK" or "Cancel" to exit the dialog
  * [ ] The transaction is recorded correctly in the CPanel \(RP and XP earned\)

* [ ] As a CampusID organization member, I can put up a quest \(becomes a quest provider\)

  * [ ] As a quest provider, I can click "Manage Quest" at CPanel to manage my quest
  * [ ] As a quest provider, I can click "Edit Quest" at CPanel to update my quest
  * [ ] As a quest provider, I can see all the quest I've provided along with the status of the quest

**Perks**

* [ ] As visitors, I can browse the perks home page
* [ ] As visitors, I can click into each of the perk listed here for more details
  * [ ] Shows title
  * [ ] From who?
  * [ ] Tells who can redeem it \(organization or individual or both\)
  * [ ] How many RP required to redeem this
  * [ ] Minimal qualified XP required to redeem this
  * [ ] Perk is only displayed within the set start and end date
* [ ] As Campus ID member, I can redeem a perk

  * [ ] I can include a note to perk provider along with my submission
  * [ ] My RP will be deducted and transferred to the perks provider i redeemed from
  * [ ] For perks that are limited to 1 usage per user, I should not be able to submit it twice unless the previous submission is marked 'cancel' or 'rejected'.

### For Admin

* [ ] As admin, I can see `Manage Campus` menu item in backend under `services`
* [ ] As admin, I can view a list of campus member
* [ ] As admin, I can allocate points to an event
  * [ ] I can choose to give to the individual or organization participants
  * [ ] For individual, I can give to those with attendance only using role code 'isAttended'
  * [ ] For organization, I can give to those selected participants by using role code 'selectedParticipant'
  * [ ] I can see a list of qualified individuals or organizations and they had made the claim or not
  * [ ] I understand I cant simply change the points when there already a claim being made out of the entire listAs admin, I can allocate points to an event
* [ ] As admin, I can manage transactions
  * [ ] I can add points to a member
  * [ ] I can reduct points from a member
  * [ ] I should not be able to edit allocated points. To adjust, i just need to add another new transaction.
  * [ ] I should not be able to delete a transaction
  * [ ] I can view the detail of a specific transaction
* [ ] As admin, I can manage perks
  * [ ] I can add perk
  * [ ] I can edit perk
  * [ ] I can deactivate a perk

