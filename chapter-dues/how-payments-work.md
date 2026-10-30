# How Dues Payments Work _(For Payment Managers)_

This page explains what happens behind the **Pay Dues** button. It covers how Kappa Loop and Fonteva (IHQ's membership system, which officers use through the **Brothers Only Portal**) work together, what your roster confirmation does, how life members are handled, what **Mark paid** and **Refund** actually change, and how a chapter passes collected province dues on to its province.

**Who this is for:** anyone with the **Payment Manager** or **Chapter Manager** role for a chapter, or the **Payment Manager** or **Regional Manager** role for a province. If you haven't set up dues yet, start with [Setting Up Chapter Dues](officer-setup.md).

{% hint style="info" %}
**The short version**

1. **Grand Chapter, province and chapter dues are three separate payments to three separate exchequers.** Paying one never pays another.
2. **Good standing with Grand Chapter comes first.** Fonteva only shows a brother as chapter- or province-financial once he's In Good Standing nationally.
3. **Confirming your roster in Fonteva tells Kappa Loop who has paid your chapter.** Before you confirm, drop brothers who haven't paid you this year, and confirm again after every change. Dropping anyone unconfirms your whole roster.
4. **Mark paid records a payment in Kappa Loop only.** It doesn't move money and it doesn't change Fonteva.
5. **A refund returns only your own exchequer's share,** and it doesn't change a brother's standing in Fonteva.
6. **Province dues your chapter collects are owed to your province.** Export the list, send the money, mark it submitted, and your province confirms receipt.
{% endhint %}

---

## Managing your chapter roster

### The one rule

Kappa Loop counts a brother's chapter dues as **paid** for the year if any one of these is true:

* he **paid in Kappa Loop**, or
* you **marked him paid** in Kappa Loop, or
* he's **confirmed on your Fonteva roster**, your chapter has **confirmed its roster since October 1**, **and** he's In Good Standing with Grand Chapter.

**Confirming your roster is your chapter saying "everyone on this roster has paid us this year."** Kappa Loop takes it at its word. So before you confirm, make sure the roster is right.

### When a brother pays your chapter

| How he paid | What you do |
|---|---|
| **In Kappa Loop** | **Nothing.** Kappa Loop records it and confirms him in Fonteva for you. |
| **Cash, check or Zelle**, and your chapter is his primary chapter | **Confirm him** in the Brothers Only Portal (Fonteva). He shows as **Paid (Fonteva)** in Kappa Loop within about an hour. |
| **Cash, check or Zelle**, but he hasn't renewed with Grand Chapter yet | **Mark him paid** in Kappa Loop now. Fonteva won't let you confirm him until he renews. When he renews, Fonteva usually checks him automatically. If it doesn't, confirm him yourself. |
| **Cash, check or Zelle**, and he's an **associate member** (your chapter isn't his primary) | **Mark him paid** in Kappa Loop. Fonteva only confirms brothers on their primary chapter's roster. |

### How to update and confirm your roster

Your Keeper of Exchequer or Keeper of Records does this in the Brothers Only Portal (Fonteva):

1. Go to **Chapter Administration → Chapter Management**, and select **View** next to your chapter.
2. Open the **Roster Report** tab. You'll see **Add a Member To Your Roster**, the **Confirm Roster** button, who confirmed it last and when, and your **Active Members**.
3. **Drop brothers who haven't paid your chapter.** Select **Drop** on his row, choose a **Drop Reason** (Graduated, Inactive, Moved, Non-paying or Deceased), and select **Confirm**.
4. **Add brothers who are missing.** Search for him under **Add a Member To Your Roster**.
5. **Select Confirm Roster.** It lists every brother on your roster who is In Good Standing and not yet confirmed, and **all of them are ticked to start with.** **Untick every brother who hasn't paid your chapter**, check the **Selected Rows** count, then select **Confirm**. You'll see "Your roster is confirmed" with the date and time.
6. After about an hour, check **Management Console → Dues → Members** in Kappa Loop. Brothers you confirmed show as **Paid (Fonteva)**. Everyone else shows as **Unfinancial** and can pay you in the app.

The **Financial Status** tab (under **More**) shows each brother's National, Province and Chapter checkmarks.

{% hint style="danger" %}
**Dropping one brother unconfirms your whole roster.** When you drop a brother, Fonteva:

* moves him off your chapter to the **Grand Chapter** account, with the reason and date,
* removes any officer role he held in your chapter, and
* **unconfirms every brother on your roster and clears your chapter's confirmation.**

So **always confirm your roster again right after you drop someone.** Until you do, Kappa Loop shows every brother in your chapter as owing chapter dues, including those who already paid you outside the app, and some may pay twice.
{% endhint %}

{% hint style="warning" %}
**If you confirm without dropping anyone, last year's confirmations still count.** Fonteva carries your roster over from last year, and brothers stay confirmed until a drop clears them. The first time you confirm after October 1, every brother still confirmed counts as paid for the new year in Kappa Loop, once he's In Good Standing with Grand Chapter. That can include brothers who haven't paid you anything this year. So start each year by dropping the brothers who haven't paid, which clears everyone, and then confirm the ones who have.
{% endhint %}

{% hint style="info" %}
**Brothers left on your roster get confirmed when they renew.** Confirm Roster only lists brothers who are In Good Standing. So a brother who hasn't renewed with Grand Chapter can stay on your roster unconfirmed. When he renews, Fonteva confirms him automatically if your roster is confirmed, and Kappa Loop then counts his chapter dues as paid. If he hasn't paid your chapter, drop him rather than leaving him on the roster. See [Fonteva also confirms some brothers for you](#what-confirming-your-roster-does).
{% endhint %}

**Dropped a brother who later pays?** He can still pay your chapter in Kappa Loop. Once he's In Good Standing with Grand Chapter, that puts him back on your roster in Fonteva automatically. If he pays you another way, add him back and confirm your roster.

**Affiliated brothers** (members whose home chapter is elsewhere) have their own list with a **Drop** button. It removes the affiliation only.

### Your routine

1. **Right after October 1:** drop brothers who haven't paid you for the new year, then confirm your roster with everyone who has.
2. **Every week during dues season:** open **Management Console → Dues → Members**. It opens on **Unfinancial**. For anyone on that list who has paid you, use the table above.
3. **As brothers renew with Grand Chapter:** check whether each one paid your chapter. Fonteva confirms brothers on your roster automatically when they renew, and emails your Polemarch if he has an email on file. If a brother hasn't paid you, drop him, then confirm your roster again.
4. **When a brother joins or transfers in:** add him to your roster and confirm it once he has paid.
5. **When you refund a brother:** drop him in Fonteva, then confirm your roster again. Otherwise Kappa Loop keeps showing him as paid.
6. **Before December 31:** make sure whoever confirms your roster has renewed his own Grand Chapter dues. On January 1, Fonteva removes officer roles from officers who aren't In Good Standing.
7. **If you collect province dues:** send them to your province and record it under [Reconcile with Province](#sending-province-dues-to-your-province).

{% hint style="danger" %}
**Never confirm a roster with unpaid brothers on it,** whether they're new this year or carried over from last year. Kappa Loop will treat them as paid, and they won't be able to pay you in the app until they're dropped from your roster.
{% endhint %}

The rest of this page explains why each step works the way it does.

---

## The three tiers

Every brother can owe dues at three levels. Each one is a separate organization with its own money.

| Tier | Paid to | Who manages it in Kappa Loop |
|---|---|---|
| **Grand Chapter** (national) | IHQ | IHQ's Payment Managers |
| **Province** | Your province | Province Payment Manager or Regional Manager |
| **Chapter** | Your chapter | Chapter Payment Manager or Chapter Manager |

* A brother pays all three in one checkout, but the money is split at the moment he pays. Each share goes straight to that tier's own Stripe account. Nobody holds anyone else's money.
* **If your chapter collects province dues with chapter dues,** the province share is part of your chapter's line. It lands in your chapter's account and your chapter sends it to the province.
* **Your access stops at your own tier.** A chapter Payment Manager sees and manages chapter dues only. He can't mark Grand Chapter dues paid or refund them, and the same holds the other way round.

## The dues year

* The fraternal year runs **October 1 to September 30.**
* Brothers can pay **next year's** dues starting **August 1**.
* Dues are always for one year. A payment for last year never counts for this year.

### What changes in Fonteva at the year change

These dates come from IHQ's Office of the Grand Keeper of Records, which sends an advisory before each year change. If an advisory gives different dates, follow the advisory.

| Date | What happens in Fonteva | What it means in Kappa Loop |
|---|---|---|
| **October 1, 4:00 AM ET** | Every brother whose dues expired September 30 becomes **Not In Good Standing**. There's no grace period. The confirmed-member count on your chapter page drops, because it counts only brothers In Good Standing. | Brothers who haven't renewed with Grand Chapter show **Unfinancial** for chapter dues, even if they're still confirmed on your roster. |
| **November 1** | Brothers unfinancial for **more than two years** are moved off your chapter to the Grand Chapter Not In Good Standing account. | Within about an hour, they drop off your **Dues → Members** list. If one later pays your chapter's dues in Kappa Loop, he's put back on your roster in Fonteva. |
| **January 1** | Chapter officer roles are removed from any officer still **Not In Good Standing**. Officers have through **December 31** to pay. | An officer who loses his Fonteva role can no longer confirm your roster in Fonteva. His Kappa Loop **Payment Manager** or **Chapter Manager** role is **not** removed automatically. |

**What does not change on October 1:**

* **Rosters aren't cleared.** Brothers checked as confirmed stay checked. Only chapter officers (Keeper of Records or Keeper of Exchequer) can change the roster, so dropping brothers who haven't paid is up to you. See [How to update and confirm your roster](#how-to-update-and-confirm-your-roster).
* **Province financial status isn't cleared.** Province checkmarks from last year stay green.
* **Brothers aren't removed from their chapters** on October 1.
* **Officers keep their officer access** through December 31. An officer who isn't In Good Standing can still confirm the roster, run officer reports and handle delegates. Like any brother, he loses member-side items such as his membership card, the directory, event registration and member pricing until he pays. These come back within about an hour of payment.

{% hint style="warning" %}
**Green checkmarks carried over from last year are not this year's payments, but Kappa Loop can count them as if they were.** Until your chapter confirms its roster after October 1, Kappa Loop ignores them. After that, every brother still on your roster counts as paid. Drop brothers who haven't paid before you confirm. See [How to update and confirm your roster](#how-to-update-and-confirm-your-roster).
{% endhint %}

---

## Where "paid" comes from

On **Management Console → Dues → Members**, every brother shows one of these:

| Status | What it means |
|---|---|
| **Paid (online)** | He paid this tier in Kappa Loop. |
| **Paid (recorded)** | A Payment Manager used **Mark paid** for a payment made outside Kappa Loop (cash, check, Zelle). |
| **Paid (Fonteva)** | Fonteva shows him financial at this tier, and he has no Kappa Loop payment. See [How Kappa Loop reads Fonteva](#how-kappa-loop-reads-fonteva). |
| **Life member** | He owes nothing at this tier. See [Life members](#life-members). |
| **Unfinancial** | Nothing shows him as paid at this tier for this year. |

For **chapter dues**, whatever status the list shows also decides what the brother sees. **If he shows as paid, his Pay Dues screen won't ask him for chapter dues.** If he shows as Unfinancial, it will.

For **province dues**, the list and the Pay Dues screen can disagree. The province list shows **Paid (Fonteva)** for any brother whose Province checkmark is green, including checkmarks carried over from last year. His Pay Dues screen only treats a green Province checkmark as paid if his Grand Chapter dues are paid through the current year. So a brother can show **Paid (Fonteva)** on your list and still be asked for province dues.

---

## Good standing comes first

**In Good Standing** is IHQ's national status, kept in Fonteva. It means a brother's Grand Chapter dues are paid for the current year. Only IHQ decides it.

It matters at your tier too:

* **Fonteva only lists brothers who are In Good Standing** in its Confirm Roster tool. You can't confirm a brother who hasn't paid Grand Chapter.
* **When a brother pays your chapter in Kappa Loop before he's In Good Standing,** your chapter still gets the money right away, and Kappa Loop records him as paid. His Fonteva chapter checkmark waits, and it turns on automatically once he pays Grand Chapter.
* A brother who hasn't renewed by **October 1 at 4:00 AM ET** drops out of good standing. Payments he makes to your chapter after that are still yours. They show in Fonteva only after he's back in good standing.
* **When he pays Grand Chapter,** he's back In Good Standing within about an hour.

---

## Your Fonteva roster and roster confirmation

### What the roster is

In Fonteva, each brother has **one primary chapter**. Your chapter's **roster** is the brothers whose primary chapter is yours. Brothers can also be **affiliated** with other chapters. Kappa Loop calls these **associate members**.

Fonteva shows three checkmarks for each brother on your roster:

| Checkmark | Turns green when |
|---|---|
| **National** | He is In Good Standing with Grand Chapter. |
| **Province** | He's marked province-financial, or he's a province life member (shown as **PLM**). |
| **Chapter** | His chapter has **confirmed** him on its roster. |

### What confirming your roster does

When you run **Confirm Roster** in Fonteva for a brother, Fonteva:

* turns his **Chapter** checkmark green, **and**
* turns his **Province** checkmark green at the same time. Fonteva doesn't check whether he actually paid the province.

It also records the date your chapter last confirmed its roster.

**Fonteva also confirms some brothers for you.** When a brother becomes In Good Standing (he renews with Grand Chapter, in Fonteva or in Kappa Loop), Fonteva checks him on your roster automatically, if:

* your chapter's roster is marked confirmed. It stays marked from year to year, so most chapters' rosters are, and
* he isn't already checked.

If your Polemarch has an email on file, Fonteva emails him about it. Your Keeper of Records doesn't need to re-add the brother.

{% hint style="warning" %}
**An automatic re-confirmation counts as chapter dues paid in Kappa Loop.** Once Fonteva re-confirms a brother this year, Kappa Loop treats his chapter dues as paid, even if he only paid Grand Chapter. Watch for these re-confirmations as brothers renew. If one hasn't paid your chapter, drop him and confirm your roster again, or he won't be able to pay you in Kappa Loop.
{% endhint %}

{% hint style="danger" %}
**Only confirm brothers who have paid your chapter, and your province if you collect province dues.**
Kappa Loop treats a confirmed brother as **paid** for chapter dues, and usually for province dues as well. Once you confirm him, his Pay Dues screen stops asking him for those dues. If you confirm a brother who hasn't paid, he can no longer pay those dues in Kappa Loop until he's dropped from your roster.
{% endhint %}

### How Kappa Loop reads Fonteva

Kappa Loop counts a brother's **chapter dues as paid through Fonteva** only when **all three** of these are true:

1. **Your chapter confirmed its roster in Fonteva during this fraternal year,** on or after October 1.
2. He is **confirmed** on that roster.
3. He is **In Good Standing** nationally.

If any one is missing, his chapter dues show as owed, unless he paid you in Kappa Loop or you recorded his payment with **Mark paid**.

Province dues work a little differently. On his Pay Dues screen, Kappa Loop counts province dues as paid through Fonteva when his Province checkmark is green **and** his Grand Chapter dues are paid through the year being collected. The province's **Dues → Members** list checks only the green checkmark. See [Where "paid" comes from](#where-paid-comes-from).

Fonteva and Kappa Loop sync about once an hour. A roster confirmation you make in Fonteva usually shows in Kappa Loop within the hour.

### Why you should confirm often

* **Until you confirm after October 1, everyone owes.** Fonteva keeps only your chapter's *latest* confirmation date, and Kappa Loop counts it only if it falls in this fraternal year. Until then, Kappa Loop treats every brother on your roster as owing chapter dues, including the ones who already paid you in cash or by Zelle. Those brothers will be asked to pay again.
* **Once you confirm, everyone on your roster is paid.** Fonteva carries your roster over at the year change. Your first confirmation after October 1 makes every confirmed brother on it count as paid once he's In Good Standing with Grand Chapter, whether or not he paid you. [Drop the ones who haven't before you confirm](#how-to-update-and-confirm-your-roster).
* **New brothers start out unconfirmed.** When a brother is added to your chapter in Fonteva, he isn't confirmed, and Fonteva flags your chapter's roster as needing confirmation again. Until you confirm him, Kappa Loop shows him as owing.
* **Brothers move off your roster.** On November 1, Fonteva moves brothers unfinancial for more than two years to the Grand Chapter Not In Good Standing account.
* **Brothers who pay off-platform only show as paid once you act.** Either confirm them in Fonteva or use **Mark paid**.
* **Your officers need to be In Good Standing by December 31.** After January 1, an officer who isn't In Good Standing loses his Fonteva officer role and can't confirm your roster.

For when to confirm, see [Your routine](#your-routine).

{% hint style="info" %}
Brothers who pay your chapter **in Kappa Loop** don't need you to do anything. Kappa Loop turns on their Fonteva chapter checkmark for you. See the next section.
{% endhint %}

---

## What changes in Fonteva when a brother pays in Kappa Loop

When a brother pays online, Kappa Loop updates Fonteva for him, usually within an hour.

| He pays | What changes in Fonteva |
|---|---|
| **Grand Chapter dues** | IHQ's payment record is created, his membership is extended to **September 30**, and he becomes **In Good Standing**. Any chapter or province updates that were waiting on him go through. |
| **Chapter dues, primary chapter** | His **Chapter** checkmark turns green. If he had no home chapter in Fonteva (for example, he was moved to Grand Chapter after lapsing), he's placed back on your roster first. |
| **Chapter dues, associate chapter** | He's added to that chapter as an **affiliate** in Fonteva. No checkmark changes. Fonteva only tracks checkmarks for a brother's primary chapter. |
| **Province dues, paid directly** | His **Province** checkmark turns green, if it's the province his primary chapter belongs to. |
| **Province dues collected by your chapter** | His **Province** checkmark turns green once your province confirms in Kappa Loop that it received the money from your chapter. See [Sending province dues to your province](#sending-province-dues-to-your-province). |

Things to know:

* **Chapter and province checkmarks wait for good standing.** If he isn't In Good Standing nationally, the update is held and goes through when he is.
* **Kappa Loop only turns checkmarks on.** It never turns them off. Dropping a brother from your roster stays a Fonteva task.
* **Paying a chapter doesn't change a brother's primary chapter** unless he chooses that chapter as his primary at checkout.
* **Your 2.5% service fee never appears in Fonteva.** Fonteva records the dues amount only.

---

## Marking a payment as paid

Use **Mark paid** when a brother paid **outside Kappa Loop**: cash, check, Zelle, or directly in Fonteva.

### How

1. In the **Management Console**, go to **Dues → Members**, and check that the right **fiscal year** is selected.
2. Find the brother and select **Mark paid**.
3. Enter the **amount** and a **reason** (for example, "Zelle 10/14").
4. For chapter dues, choose whether he paid your **full rate** or the **associate rate**.
5. Leave **email a receipt** ticked, or untick it if he already has a receipt (for example, he paid in Fonteva).
6. Select **Mark paid**.

### What it does

* He shows as **Paid (recorded)** for that tier and year, and his Pay Dues screen stops asking him for that tier.
* He gets a receipt email, if you left it ticked, and an in-app notice if he allows them.
* The action is logged with your name, the time and your reason.

### What it does not do

* **It doesn't move any money.** No card is charged, and nothing is deposited.
* **It doesn't change Fonteva.** His Fonteva checkmarks stay as they are. To turn his **Chapter** checkmark green, confirm him on your roster in Fonteva.

### When Kappa Loop won't let you

* **He's a life member at that tier.** He owes nothing there.
* **He's already paid** that tier for that year.
* **He has an online checkout in progress.** Wait for it to finish. This stops him from being charged and recorded at the same time.
* **He isn't an active member of your chapter** (or of a chapter in your province, for province dues).

### Undoing a mistake

If you marked the wrong brother or the wrong amount, open the payment and **undo** it. Undo works only for recorded payments. It moves no money, and the record keeps a trail of both actions. To return money a brother paid **online**, use a refund instead.

---

## Refunds: what leaves your account

Refunds are only for payments made **in Kappa Loop**. For how to issue one, see [Issuing a refund](officer-setup.md#issuing-a-refund).

* **You refund only your own tier's share.** A chapter refund returns your chapter's line, including any province dues collected with it. Grand Chapter dues from the same checkout aren't touched.
* **The money comes out of your exchequer's Stripe account.** If you've already withdrawn it to your bank, your Stripe balance can go negative. It's covered by your next dues payments.
* **The brother also gets back his share of the service fee.** Your exchequer doesn't pay that part.
* **Refunds can't be undone,** and they're the full tier share. There are no partial refunds.
* **A recorded payment (Mark paid) can't be refunded,** because no money moved through Kappa Loop. Undo it instead.

### What a refund changes in Fonteva

* **Chapter and province refunds don't change Fonteva.** If the brother is confirmed on your roster, he stays confirmed. And if your chapter has confirmed its roster this year, **Kappa Loop will keep showing him as paid through Fonteva** until he's dropped from your roster in Fonteva.
* **Grand Chapter refunds** (done by IHQ) record the refund in Fonteva, but **they don't change his good standing.** Whether a refunded brother keeps his standing is IHQ's decision.
* If you refund a payment before Kappa Loop has updated Fonteva, his checkmark is never turned on.

---

## Sending province dues to your province

If your chapter turned on **Collect province dues with chapter dues**, the province's share of each payment lands in **your chapter's** Stripe account. Your chapter owes that money to the province. Kappa Loop keeps one shared record of it, so your chapter and your province see the same list instead of trading spreadsheets.

{% hint style="info" %}
**Kappa Loop doesn't send the money for you.** You send it to your province however your province takes it: check, bank transfer, or an upload to its own system. Kappa Loop records who you sent and when, and your province confirms when it arrives.
{% endhint %}

### For the chapter: export, send, mark submitted

1. In the **Management Console**, go to **Dues** and open **Reconcile with Province** (next to **Payments** and **Declined**).
2. Pick the **fiscal year**. The **Not submitted** tab lists every brother whose province share you haven't sent yet, with the date he paid and the total you owe.
3. **Export the list.** Select **Export all**, or tick some brothers and select **Export selected**. You'll get a spreadsheet with each brother's paid date, name, chapter, national and chapter standing, chapter life member status, email, phone and membership ID.
4. **Send the file and the money to your province,** the way your province asks for it.
5. **Mark them submitted.** After the download, Kappa Loop asks whether you've sent it:
   * Select **I've sent it — mark them submitted** if the money has gone out.
   * Select **Not yet** if it hasn't. Later, tick the brothers you've paid for and select **Mark submitted**.

{% hint style="warning" %}
**Only mark brothers submitted once the money has actually gone out.** Your province will look for funds from every brother you mark.
{% endhint %}

Brothers you've marked move to the **Submitted** tab:

| Status | What it means |
|---|---|
| **Awaiting confirmation** | You sent it. Your province hasn't confirmed it arrived yet. Use this filter as your follow-up list. |
| **Received** | Your province confirmed it arrived. This is what clears the amount your chapter owes. |

* **Marking submitted doesn't change what you owe.** The amount owed only goes down when your province confirms receipt.
* **Marked someone by mistake?** On **Submitted**, tick him and select **Move back to Not submitted**. You can't do this once your province has marked him **Received**. Ask your province to correct it.
* **Refunds are handled for you.** If you refund a brother's chapter payment, his province share comes off what you owe.

### For the province: confirm what arrived

1. In the **Management Console**, with your **province** selected, go to **Dues → Reconcile with Province**.
2. You'll see each chapter that collected your dues, with the amount collected, received and still outstanding. Open a chapter to see its brothers.
3. When a chapter's money arrives, tick the brothers it covers (or **Select all outstanding**), then select **Mark as received**.

When you mark a brother **Received**:

* that amount comes off the chapter's balance on both screens, and
* Kappa Loop turns his **Province** checkmark green in Fonteva, as long as he's In Good Standing nationally.

{% hint style="danger" %}
**Known limitation: "Received via Fonteva" doesn't mean the money arrived.**
Kappa Loop shows a brother as **Received via Fonteva**, and takes his share off the chapter's balance, whenever his Province checkmark turns green in Fonteva after you started using this screen. It doesn't check whether any money moved.

The most common cause is the chapter confirming its roster. Fonteva's **Confirm Roster** tool turns on the Province checkmark for every brother it confirms. So a chapter can confirm its roster without sending you anything, and those brothers will show as received.

**Before you count a "via Fonteva" brother as paid, check that the chapter actually sent his share.** Treat only brothers you marked **Received** yourself as money in hand.
{% endhint %}

* Only the province can mark money **Received**. A chapter sees the same list but can't change it.
* There's no undo for **Mark as received**. If you mark the wrong brother, [contact support](https://kappaloop.com/support).

---

## Life members

A life member at a tier owes **no dues at that tier, ever**. Kappa Loop doesn't show him a dues line there, and you can't mark him paid there. Life membership is separate at each tier. **A Grand Chapter life member still owes chapter and province dues** unless he's also a life member there.

| | Grand Chapter life member | Province life member | Chapter life member |
|---|---|---|---|
| **Where it's recorded** | Fonteva (IHQ) | Fonteva (IHQ) | **Kappa Loop only.** Fonteva has no chapter life membership. |
| **Owes dues at this tier** | Never | Never, **for that province only.** If his primary chapter moves to another province, he owes the new province. | Never, **at that chapter only** |
| **Still owes** | Province and chapter dues | Grand Chapter and chapter dues | Grand Chapter dues, and **the province share if your chapter collects province dues** (unless he's also a province life member) |
| **Good standing** | Counts as In Good Standing, so his chapter and province updates go through right away. | Normal rules | Normal rules |
| **Fonteva checkmark** | National stays green | Province shows **PLM** | Each October 1, Kappa Loop treats him as paid for the year and turns his Chapter checkmark green, once he's In Good Standing nationally. |
| **Who can change it** | IHQ | IHQ | Your chapter, in Kappa Loop |

* A chapter life membership stays with the brother even if he later leaves the chapter.
* If a brother tells you he's a life member and Kappa Loop asks him for dues, check with IHQ (for Grand Chapter or province) or your chapter's records (for chapter). Don't mark him paid as a workaround. That records a payment that never happened.

---

## Common situations

**A brother paid me by Zelle. What do I do?**
See [When a brother pays your chapter](#when-a-brother-pays-your-chapter).

**My whole roster shows Unfinancial, but most brothers paid us.**
Your chapter probably hasn't confirmed its roster since October 1. Confirm in Fonteva, and check back in about an hour. Brothers who haven't renewed Grand Chapter dues also show Unfinancial, because they've been Not In Good Standing since October 1 at 4:00 AM ET.

**A brother paid in Kappa Loop, but his Fonteva chapter checkmark is still red.**
Either he isn't In Good Standing nationally yet, and the checkmark turns on once he is, or it's been less than an hour. If he's In Good Standing and it's been a day, [contact support](https://kappaloop.com/support).

**I confirmed a brother by mistake and now he can't pay.**
Drop him in Fonteva, then confirm your roster again with the brothers who have paid. Once it syncs, about an hour, his Pay Dues screen will ask for chapter dues again.

**A brother paid IHQ by eCheck, but Kappa Loop still asks him for Grand Chapter dues.**
Kappa Loop can't see an eCheck until it clears in Fonteva, which can take several days. Ask him to wait for it to clear rather than paying again.

**I refunded a brother, but he still shows as paid.**
He's still confirmed on your Fonteva roster. Drop him and confirm your roster again if he's no longer financial.

**A brother paid two chapters. Which one is his?**
His **primary** chapter in Fonteva is his home chapter, and it's the only one Fonteva shows checkmarks for. The other chapter is an associate chapter: it gets his money and shows him as paid in Kappa Loop, and Fonteva records him as an affiliate.
