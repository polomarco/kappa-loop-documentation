# Delegate Lists _(For Managers)_

Delegate lists enable weighted voting by defining delegates, their vote weights, and proxy assignments.

## What Are Delegate Lists?

A delegate list is a named collection of delegates (representatives) who are authorized to vote on behalf of their chapters or as awardees. Each delegate has:

* A **membership number** for identification
* A **vote weight** that determines how much their vote counts
* An optional **proxy** assignment if they cannot vote in person

## Accessing Delegate Lists

1. Open the **Voting Center** from the drawer menu
2. Tap the **Delegate Lists** button (or access from the menu)
3. View all delegate lists for your scope

## Delegate List Overview

Each delegate list shows:

* **Name** and description
* **Member count** - Total delegates in the list
* **Total weight** - Sum of all vote weights
* **Proxied count** - Delegates with proxy assignments
* **Unresolved count** - Delegates not yet matched to system users
* **Created by** and creation date

## Creating a Delegate List

1. Tap the **+** (plus) button on the delegate list screen
2. Enter a **name** and optional **description**
3. Select the **scope** (Grand Chapter, Province, or Chapter)
4. Add delegates via one of the methods below

### Adding Delegates Manually

1. Tap **Add Delegate**
2. Enter the delegate's membership number
3. Optionally set the delegate name and chapter
4. Set the **vote weight** (default: 1)
5. Select the **delegate type** (Chapter delegate or Awardee)
6. The system will attempt to match the membership number to a user

### Importing Delegates via CSV

1. Tap **Import CSV**
2. Select a CSV file with delegate information
3. The system processes the file and reports:
   * **Matched** - Delegates successfully matched to system users
   * **Unmatched** - Delegates that couldn't be matched (remain as unresolved)
   * **Errors** - Rows that couldn't be processed

CSV format should include:
* Membership number (required)
* Delegate name (optional)
* Chapter name (optional)
* Vote weight (optional, defaults to 1)

## Managing Delegates

### Viewing Delegate Details

Each delegate entry shows:

* Membership number and name
* Chapter affiliation
* Vote weight
* Delegate type (Chapter or Awardee)
* Resolution status (matched to user or unresolved)
* Proxy assignment (if any)

### Assigning Proxies

When a delegate cannot vote in person, a proxy can be assigned to vote on their behalf:

1. Open the delegate list
2. Find the delegate entry
3. Tap **Assign Proxy**
4. Search for the proxy holder (must be a system user)
5. Confirm the proxy assignment

The proxy holder will then cast votes carrying the combined weight of:
* Their own vote weight (if they are also a delegate)
* The weight of all delegates they are proxy for

### Proxy Summary

View a summary of all proxy assignments:

* **Total delegates** in the list
* **Proxied** - Delegates with proxy holders assigned
* **Unproxied** - Delegates without proxy assignments
* **Unresolved** - Delegates not yet matched to users

The summary also groups by proxy holder, showing:
* Each proxy holder's name
* Number of delegates they represent
* Total combined weight

## Using Delegate Lists with Votes

When creating a vote:

1. In Step 5 (Eligibility), enable **Weighted Voting**
2. Select a delegate list from the dropdown
3. Only delegates in the list (and their proxies) will be eligible to vote
4. Each vote will be weighted according to the delegate's assigned weight

## Weighted Vote Reports

After a weighted vote closes, managers can access detailed reports showing:

* Overall turnout by delegate count and weight
* Province-by-province breakdown (for national votes)
* Chapter-by-chapter breakdown
* Individual delegate voting status
* Proxy vote tracking (who voted on behalf of whom)
* Awardee section (for non-chapter delegates)

## Best Practices

* Create delegate lists well in advance of the vote
* Verify that membership numbers match system records
* Assign proxies before the voting period begins
* Review the unresolved count and manually match delegates if needed
* Use CSV import for large delegate lists to save time

## Troubleshooting

### Delegates Show as Unresolved

The membership number didn't match any user in the system. The delegate can still be included in the list, but won't be able to vote until matched. Check that the membership number is correct.

### Proxy Can't Be Assigned

The proxy holder must be a registered user in the system. Search by name to find and assign them.

### Weight Not Calculating Correctly

Ensure all delegates have the correct vote weight set. The total weight displayed should equal the sum of all individual delegate weights.

---

_Last updated: February 2026_
