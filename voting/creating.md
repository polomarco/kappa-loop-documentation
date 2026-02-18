# Creating Votes _(For Managers)_

This guide explains how to create and manage ballots and polls. Only users with vote management permissions can create votes.

## Who Can Create Votes

* **National Managers** - Can create Grand Chapter (national) scope votes
* **Province Managers** - Can create province-level votes
* **Chapter Managers** - Can create chapter-level votes

## Accessing the Create Vote Screen

1. Open the **Voting Center** from the drawer menu
2. Tap the **+** (plus) button
3. The 6-step creation wizard opens

## Step-by-Step Creation Wizard

### Step 1: Vote Type

Choose the type of vote:

* **Ballot** - Anonymous voting for formal decisions. Individual votes cannot be traced to voters.
* **Poll** - Non-anonymous feedback collection. Managers can see who voted for what.

### Step 2: Scope & Basic Info

**Scope Selection:**
* **Grand Chapter** - Organization-wide vote (National managers)
* **Province** - Province-level vote (Province managers)
* **Chapter** - Chapter-level vote (Chapter managers)

**Basic Information:**
* **Title** _(required)_ - A clear, descriptive title for the vote
* **Description** _(optional)_ - Additional context or instructions for voters

### Step 3: Questions

Add one or more questions to the vote. For each question:

**Question Details:**
* **Question Title** _(required)_ - The question being asked
* **Description** _(optional)_ - Additional context for the question

**Option Type:**
* **Single Choice** - Voters select exactly one option
* **Multiple Choice** - Voters select one or more options
  * Set **minimum selections** (default: 1)
  * Set **maximum selections** (optional, unlimited by default)
* **Yes/No/Abstain** - Simple approval voting with three fixed options

**Custom Options** (for Single/Multiple Choice):
* Add at least 2 options
* Each option has a label and optional description
* Reorder options by dragging
* Remove options with the delete button
* Add more options with the "Add Option" button

**Adding Multiple Questions:**
* Tap **Add Question** to add another question
* Each question can have a different option type
* Questions are numbered and can be reordered

### Step 4: Schedule & Settings

**Start Mode:**
* **Immediate** - Voting starts as soon as the vote is published
* **Scheduled** - Set a specific date and time for voting to begin
* **Manual** - Publish now, start voting later by manually activating

**End Time:**
* Set a date and time for voting to automatically close
* Or leave open for manual closing (no end time)

**Results Settings:**
* **Show results in real-time** - Voters can see running results while voting is active
* **Results visibility** - Choose "Everyone" or "Managers Only"

### Step 5: Eligibility

Configure who is eligible to vote:

**Financial Requirements:**
* Require financial standing at Grand Chapter level
* Require financial standing at Province level
* Require financial standing at Chapter level

**Meeting Check-in:**
* Require check-in to a specific meeting
* Select the meeting from a list of chapter meetings

**Additional Options:**
* Exclude visiting brothers from eligibility

**Weighted Voting:**
* Enable weighted voting by selecting a **Delegate List**
* Each delegate's vote will carry their assigned weight
* Proxy assignments from the delegate list apply automatically

### Step 6: Review & Publish

Review all settings before publishing:

* Vote type and scope
* All questions with their options
* Schedule and start mode
* Eligibility requirements
* Results visibility settings

**Publishing Options:**
* **Save as Draft** - Save without publishing (can edit and publish later)
* **Publish** - Make the vote live (starts based on configured start mode)

## Editing Draft Votes

1. Go to the **Drafts** tab in the Voting Center
2. Tap the draft vote
3. Tap **Edit** to open the creation wizard with pre-filled data
4. Make your changes
5. Save as draft or publish

## Managing Active Votes

After publishing, managers can:

* **View participation** - See who has and hasn't voted
* **Manage eligible voters** - Manually add or remove eligible participants
* **Start voting** (for manual start mode) - Activate the voting period
* **Close voting early** - End the voting period before the scheduled end time
* **Cancel the vote** - Cancel the vote entirely

## Managing Eligible Voters

1. Open the active vote
2. Tap **Manage Eligible Voters**
3. View the current eligible voter list
4. **Add voters** - Search for members by name and add them manually
5. **Remove voters** - Remove manually added voters

## Best Practices

* Write clear, unambiguous question titles
* Provide descriptions when questions need additional context
* For formal decisions, use **Ballots** (anonymous) to encourage honest voting
* For informal feedback, use **Polls** to gather attributed responses
* Set appropriate eligibility requirements to ensure only qualified members vote
* Test with a draft before publishing important votes
* Allow adequate voting time for all eligible members to participate

## Troubleshooting

### Can't See Create Button

You may not have vote management permissions for the current scope. Contact your administrator to request permissions.

### Eligibility Requirements Not Working

Ensure that member financial status data is up to date in the system. Financial requirements are checked against the system of record.

### Delegate List Not Showing

Delegate lists must be created before they can be attached to a vote. See [Delegate Lists](delegate-lists.md) for instructions.

---

_Last updated: February 2026_
