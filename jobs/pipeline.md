# Candidate Submissions

## Purpose

The Candidate Submissions enables recruiters to manage candidates throughout the hiring lifecycle for a specific job requirement.

Once a candidate is tagged to a job, the candidate enters the Submissions and progresses through multiple recruitment stages until placement or closure.

The Submissions provides visibility into candidate progress, approvals, submissions, interviews, confirmations, placements, and onboarding outcomes.

---

## Intended Users

The Candidate Submissions feature is available to:

* Account Manager
* Delivery Manager
* Technical Recruiter

---

## Accessing Candidate Submissions

### Navigation Flow

```text
Jobs
    ↓
Select Job
    ↓
Submissions
```

The Submissions displays all candidates associated with the selected job requirement.

---

## Submissions Workflow

Candidates move through the following recruitment stages:

```text
Tag Candidate
    ↓
Pipeline
    ↓
Submissions
    ↓
Client Submission
    ↓
Interview
    ↓
Confirmation
    ↓
Placement
```

If a candidate does not join after placement:

```text
Placement
    ↓
Not Joined
```

---

## Stage:1 Pipeline Workflow

The Pipeline stage contains newly tagged candidates.

Candidates can enter the Pipeline through:

* Candidate Discovery
* Tag Candidate
* Manual Candidate Association

Recruiters can review candidate information before deciding whether to proceed with the submission process.

---

### Candidate Actions

When a recruiter opens a candidate profile in the Pipeline stage, the following actions are available:

#### Approve

Moves the candidate to the submission process.

#### Reject

Removes the candidate from the active recruitment workflow.

#### Revert

Moves the candidate back to a previous stage when further review is required.

---

## Approving a Candidate

When the recruiter clicks Approve, the Quick Submission popup opens.

The recruiter must complete the submission details before proceeding.

---

## Candidate Information

The following information is displayed:

### Selected Candidate Profile

### Job Title

### Availability

### Relocation

### Pay Rate

### Bill Rate

### Recipients

### Additional Notifiers

### Engagement Mode

### Past Experience with Same Client

### AI Interview Integration

### Schedule AI Interview

Available options:

* Yes
* No

When enabled, recruiters can configure:

### Interview Duration

Example:

* 10 Minutes

### Interview Type

Examples:

* Video Interview
* MCQ Assessment
* Video and MCQ

### Validation Period

Examples:

* 1 Day
* 2 Days

The system automatically generates and sends the AI interview invitation to the candidate.

---

# Right to Represent (RTR)

The system supports candidate authorization through RTR.

---

## Submit RTR

Available options:

* Yes
* No

When RTR is enabled:

* An RTR email is sent to the candidate.
* The email contains job details, client information, compensation information, and authorization text.
* The candidate receives:

  * Accept RTR
  * Reject RTR

The RTR process confirms the candidate's authorization for representation to the client.

---

## Comments

Recruiters must provide submission notes and remarks before proceeding.

---

## Submit To Candidate

After completing all required information:

1. Review submission details.
2. Configure AI Interview if required.
3. Configure RTR if required.
4. Add comments.
5. Click Submit To Candidate.

The candidate moves to the Submission stage.

---

# Stage 2: Submission

The Submission stage contains candidates who have completed recruiter review and submission processing.

Recruiters can:

* Review candidate details
* Track submission progress
* Approve candidates for client submission
* Reject candidates
* Revert candidates

Approved candidates move to Client Submission.

---

# Stage 3: Client Submission

The Client Submission stage contains candidates who have been submitted to the client for review.

Recruiters can:

* Monitor client review status
* Track candidate progress
* Manage client feedback
* Schedule interviews

## Interview Scheduling

When a recruiter approves a candidate in the Client Submission stage, the Interview Schedule popup is displayed.

The popup contains:

* Job Code
* Candidate
* Interview Level

## Scheduling Options
### Without Schedule

If Without Schedule is selected, the recruiter can submit the candidate directly to the next stage without scheduling an interview.

### With Schedule

If With Schedule is selected, the recruiter must choose one of the following options:

* With AAIRO
* Without AAIRO

### With AAIRO

When With AAIRO is selected:

* Recruiter selects the interview level. 
* Recruiter selects the notification recipient(s).
* The interview is scheduled using the AAIRO interview workflow.

### Without AAIRO

When Without AAIRO is selected, the recruiter must provide additional scheduling information:

* Notify To
* Time Zone
* Interview Date
* Start Time
* End Time

After entering the required details, the recruiter can submit the interview schedule.

Successful candidates continue through the recruitment workflow and move to the Interview stage.

---

# Stage 4: Interview

The Interview stage contains candidates who have successfully completed the client submission process and are undergoing interview evaluation.

Recruiters can review:

* Submission Details
* Candidate Information
* Interview Details
* Interview Status

Available actions:

* Approve
* Reject
* Revert

## Approving a Candidate

When a recruiter clicks Approve, the Create Confirmation window is displayed.

The recruiter must complete the required information before moving the candidate to the Confirmation stage.

### Job Details
* Job Name
* Tentative Start Date
* Primary Sales Manager
* Account Manager
* Delivery Manager
* Testing
* Comments
* Payment Details
* Placement Type
* Consultant Salary
* Placement Fee
* CTC (Variable)
* Final CTC
* Gross Revenue
* Taxes
* Invoice Amount
* Net Receivable
* Profit (Margin)
* Expiry Date for Purchase Order
* Client Details
* Client / Prime Vendor
* Client Manager
* Resume Upload
* Upload Document
* Supplier Details

Available options:

* Active Employer
* Add New

Additional fields:

* Designation
* Website
* Supplier Invoice Terms

After completing the required information, click Confirm.

The candidate is moved to the Confirmation stage.

## Reject

Reject removes the candidate from the active recruitment workflow.

## Revert

Revert moves the candidate back to the previous recruitment stage for further review or correction.

---

# Stage 5: Confirmation

The Confirmation stage contains candidates who have successfully cleared interviews and are ready for final hiring approval.

Recruiters can:

* Verify compensation information
* Confirm client details
* Review supplier information
* Validate hiring information

Approved candidates move to Placement.

---

# Stage 6: Placement

The Placement stage contains successfully hired candidates.

Recruiters can review:

* Placement Details
* Compensation Details
* Client Information
* Joining Information

Placement represents successful completion of the hiring process.

---

# Stage 7: Not Joined

Candidates who do not join after placement are moved to the Not Joined stage.

This stage helps recruiters track onboarding failures and maintain recruitment records.

---

# Revert Functionality

The Revert option allows recruiters to move candidates back to a previous stage.

Examples:

```text
Submission
    ↓
Revert
    ↓
Pipeline
```

```text
Interview
    ↓
Revert
    ↓
Client Submission
```

Revert helps recruiters correct workflow issues without restarting the recruitment process.

---

# Benefits

The Candidate Pipeline helps recruiters:

* Track candidate progress
* Manage recruitment stages
* Monitor hiring activities
* Schedule interviews
* Maintain candidate history
* Improve recruitment visibility
* Reduce manual tracking effort

---

# Related Documentation

* Create Job
* Candidate Discovery
* Candidate Tagging
* Submission Management
* Interview Management
* Placement Management
