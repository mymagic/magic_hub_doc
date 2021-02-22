# Activate for Program Owner

### Backend

MaGIC Activate used `Challenge` module as backend and its management interface can be accessible thru:

`Backend` -&gt; `Service` -&gt; `Challenge` -&gt; `Manage`

### Workflow for Challenge \(Problem Statement\)

As admin, you can perform the following workflow action onto a challenge submission by problem statement owner.

1. `new` - In draft mode, applicant not yet submit. Submission is editable by application in this stage.
2. `pending` - Submitted, pending for admin to process. Submission is **NOT Editable** by application in this stage.
3. `processing` - Processing by admin. Admin can post message to applicant for amendment. Submission is editable by application in this stage. After amended applicant resubmit and status reset back to stage 2. 
4. `approved`  
   1. Application approve by admin.
   2. Auto create participation form \(F7\) to take in solution provider submission for this challenge.
   3. Challenge is accessible in frontend.
5. `completed`- To mark this challenge has completed. Participation form is disabled.
6. `reject`- To mark this challenge has permanently rejected by Admin. 

### Workflow for Solution Provider

### F7 Form

