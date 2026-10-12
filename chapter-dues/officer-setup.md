# Setting Up Chapter Dues _(For Chapter Officers)_

Collect your chapter's dues in Kappa Loop. Brothers pay Grand Chapter, province and chapter dues in one checkout, and your chapter's share goes straight into your chapter's own Stripe account.

**Who can set this up:** anyone with the **Chapter Manager** or **Payment Manager** role for your chapter.

* **Polemarch** and **1st Vice Polemarch** get **Chapter Manager** automatically.
* **Keeper of Exchequer** gets **Payment Manager** automatically.
* Anyone else, such as an Assistant Keeper of Exchequer, can be given either role by a Chapter Manager. See [Giving another brother access](#giving-another-brother-access).

---

## Before you start

{% hint style="warning" %}
**Use a computer.** Connecting Stripe can't be finished from a phone's web browser. Do the setup on a laptop or desktop at **kappaloop.com**.
{% endhint %}

Have these ready. Stripe will ask for them:

* The **bank account** your chapter's dues should be deposited into
* Your chapter's **legal and business details** (such as its tax ID, if it has one)
* **Your own identity details.** Stripe verifies the person setting up the account.

If your chapter already has a Stripe account, you can connect that one instead of creating a new one.

{% hint style="danger" %}
**Don't use your personal email for your chapter's Stripe account.** The Stripe account belongs to your chapter, not to you, and it has to stay with the chapter when officers change. Create it with an email your chapter owns and can pass to the next Keeper of Exchequer, such as a shared chapter treasurer address. Don't connect your personal Stripe account either.
{% endhint %}

---

## Step 1 — Sign in on the web

1. On your computer, go to **kappaloop.com** and sign in.
2. In the left menu, select **Management Console**.
3. Make sure **your chapter** is selected at the top.

{% hint style="info" %}
Don't see **Management Console**? You need the **Chapter Manager** or **Payment Manager** role for your chapter. See [Troubleshooting](#troubleshooting).
{% endhint %}

## Step 2 — Connect your chapter's Stripe account

1. In the **Management Console**, under **Money**, select **Payment setup**.
2. Select **Set Up Payments**. You'll go to Stripe.
3. Sign in to your chapter's existing Stripe account, or create a new one.
   * Your chapter name is filled in for you.
   * **Your Kappa Loop email is filled in too. If it's your personal email, change it** to your chapter's email before you continue.
4. Complete Stripe's questions, then return to Kappa Loop.
5. You'll see **"You're all set!"** Select **Back to Payment Setup**.

Check the status in **Management Console → Payment setup**:

| Status | What it means |
|---|---|
| **Active, accepting payments** | You're done. Brothers can pay your chapter's dues. |
| **Action needed** | Stripe needs more information or is still verifying. Brothers **can't pay yet**. Select **Continue Setup** to finish. |
| **Not set up** | The connection didn't complete. Select **Set Up Payments** again. |

{% hint style="info" %}
"You're all set!" means the connection worked. Stripe may still take a little time to verify the account. If the status says **Action needed**, check back or select **Continue Setup**.
{% endhint %}

## Step 3 — Set your chapter's dues

1. In the **Management Console**, under **Money**, select **Dues**, then open the **Settings** tab.
2. Enter your **Annual dues amount**, what each member owes your chapter per year. **Don't include province dues in this amount.** They're added separately in the next step.
3. Leave **Effective date** as today to start now, or pick a future date to schedule it.
4. **Turn on Collect province dues with chapter dues, and enter your province's dues amount.** We strongly recommend this. Provinces aren't taking dues payments directly in Kappa Loop right now, so this is how brothers pay province dues in the same checkout. The province amount is added to your chapter's line, the whole payment comes to your chapter, and your chapter pays the province.
5. Optional settings:
   * **Chapter Life Membership.** A one-time price that covers this chapter's dues for life.
   * **Senior / 50-year rate.** A reduced rate for brothers over a set age or years since initiation.
   * **Associate member price.** A reduced rate for brothers who hold your chapter as a second (non-primary) chapter.
6. Select **Save dues settings**.

## Step 4 — Tell your brothers

Before you announce it, check that **Management Console → Payment setup** shows **Active, accepting payments**.

Brothers pay under **Pay Dues** in Kappa Loop, in the app or at kappaloop.com. Let them know with an **Announcement** to your chapter, at your next meeting, or in your chapter group chat.

---

## Fees

Your chapter receives the **full dues amount you set**. Members pay a **service fee** on top, shown at checkout. No fees come out of your chapter's account.

## Tracking who has paid

All of these are in the **Management Console**.

* **Dues → Payments** lists every payment to your chapter.
* **Dues → Members** shows who has and hasn't paid. It opens on **Unfinancial** brothers by default, and you can export the list.
* **Reports → Exchequer report** shows dues collected and deposits into your bank, with a CSV export for your bookkeeping.

## Good to know

* **One Stripe account per chapter.** A Stripe account can be connected to only one chapter.
* **Brothers can't pay your chapter's dues until Stripe is active.** Until **Management Console → Payment setup** shows **Active, accepting payments**, your chapter's dues can't be paid, even if you've saved an amount.

## Issuing a refund

Refunds are for payments brothers made in Kappa Loop. You can refund from either of two places in the **Management Console**:

* **Dues → Payments:** open the payment, then select **Refund $…** on your chapter's line.
* **Dues → Members:** find the brother, then select **Refund** on his row.

Then:

1. Choose a reason: **Duplicate payment**, **Paid in error**, **Membership / eligibility change**, **Member request** or **Other**. If you choose **Other**, explain the reason.
2. Check the box to confirm the refund back to the member.
3. Select **Refund dues**.

{% hint style="warning" %}
**Refunds can't be undone, and they're all or nothing.** The brother gets back your chapter's full share of the payment, including any province dues you collected with it, plus his share of the service fee. That amount is taken back from your chapter's Stripe account. A refund covers only your chapter's share. Grand Chapter dues paid in the same checkout aren't affected.
{% endhint %}

The payment shows **Refunding** and then **Refunded**. If it shows **Refund stalled**, select **Retry refund**.

## Giving another brother access

A **Chapter Manager** (your Polemarch or 1st Vice Polemarch) can give another brother access:

1. In the **Management Console**, under **People**, select **Roles**.
2. Assign **Payment Manager** (dues and payments) or **Chapter Manager** (everything for the chapter) for your chapter.

---

## Troubleshooting

**I don't see Management Console.**
You need the **Chapter Manager** or **Payment Manager** role for your chapter. Polemarchs, 1st Vice Polemarchs and Keepers of Exchequer get these automatically when their title is in the fraternity's records. Anyone else can be given a role by a Chapter Manager (see [Giving another brother access](#giving-another-brother-access)). If you should have access and don't, [contact support](https://kappaloop.com/support).

**I tried to connect Stripe on my phone and got sent to the app.**
Start again on a computer. Connecting Stripe has to be finished in a computer's web browser.

**Stripe says this account is already connected to another chapter.**
Each Stripe account can belong to only one chapter. Connect a different Stripe account, or contact support.

**Status still says Action needed.**
Select **Continue Setup**. Stripe will show what it still needs.
