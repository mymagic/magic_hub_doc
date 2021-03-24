# UAT

### Definition

| Cpanel | Member Control Panel |
| :--- | :--- |
| XP | Experience Point |
| RP | Redeemable Point |
| EKYC | Electronic Know Your Customer |

### For Member

* [ ] As a registered Central Member, I can signup for Campus ID membership for individual thru Cpanel
* [ ] As a registered Central Member, I can auto EKYC my identity using MyKad for the account I am currently login to, thru Cpanel. 
  * [ ] Using Blink, my application is instant approve once auto identification completed
  * [ ] If Blink failed to auto identify my Identity, the EKYC module is smart enough to fall back to manual method
* [ ] As a registered Central Member, I get a Campus ID Membership code \(e.g. 'P99999'\) upon successful enrollment. Approved Individual EKYC is part of the requirements.
* [ ] As a registered Central Member, I can acquire a Campus ID Membership code \(e.g. 'C88888'\) for my organization profile
  * [ ] I can submit application by providing information like \(SSM Reg No, SSM Company Name, SSM Company Address, SSM copy of documentation\) and have it process manually
* [ ] As a Campus ID member, I understand there are 2 type of membership. One for individual and one for organization.
* [ ] As a Campus ID member, I can go to Cpanel homepage and see my current XP and RP there
* [ ] As a Campus ID member, I also can get to Campus ID Member page thru Cpanel
  * [ ] My latest XP and RP
  * [ ] My Campus ID membership code
  * [ ] My Campus ID associated EKYC info like full name, mykad
  * [ ] List of campus ID membership I have access to and able to switch in between them
  * [ ] List of events I participated
  * [ ] I can claim points from the event list
  * [ ] Points claimed are immediately debit into my Campus ID membership account
  * [ ] List of transaction of points

### For Admin

* [ ] As admin, I can see `Manage Campus` menu item in backend under services
* [ ] As admin, I can view a list of campus member
* [ ] As admin, I can allocate points to an event
  * [ ] I can choose to give to the individual or organization participants
  * [ ] For individual, I can give to those with attendance only using role code 'isAttended'
  * [ ] For organization, I can give to those selected participants by using role code 'selectedParticipant'
  * [ ] I can see a list of qualified individuals or organizations and they had made the claim or not
  * [ ] I understand I cant simply change the points when there already a claim being made out of the entire list

