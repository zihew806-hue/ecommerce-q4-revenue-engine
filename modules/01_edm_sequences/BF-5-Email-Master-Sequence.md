# The Black Friday 5-Email Master Sequence

**Klaviyo-Certified Playbook · 2026 Edition · For Shopify & DTC Brands**
A five-touch revenue sequence built to protect margin, protect list health, and still sell out the shelf.

> ### How to use this file
> - **Everything inside a `text` code block is the finished, 100% US-English email.** Copy it straight into a Klaviyo / Mailchimp text block. No rewriting needed.
> - **Everything outside the code blocks is internal direction** (Chinese, for your team). Do **not** paste it into the email.
> - **`[ Bracketed Text ]` = a button block.** Build it as a real CTA button, not as plain text.
> - `{{ variables }}` are merge tags. Full dictionary + Klaviyo / Mailchimp syntax mapping is in **Appendix A**.
> - All bracketed inventory numbers, timestamps, reviews, and product names must be populated with **real data**. This sequence's conversion power comes from being checkably specific. Never fake a stock count.
> - Calendar below is set for **2026**: Thanksgiving Thu 11/26 · Black Friday Fri 11/27 · Cyber Monday Mon 11/30. All times ET unless noted.

---

## 00 · Sequence at a Glance

| # | Email | Send Window (2026) | Primary Audience | Suppress / Exclude | One Job |
|:--|:--|:--|:--|:--|:--|
| 1 | **VIP Early Access** | Wed 11/25, 7:00 AM **recipient local** (gate opens 12:01 AM ET) | Purchased in last 12 mo + 90-day engaged non-buyers | Unsubscribed, spam complaints, suppressed profiles | Lock in high-intent revenue *without* discounting deeper |
| 2 | **The Official Drop** | Fri 11/27, **12:01 AM ET** | Full engaged subscriber base | Email 1 purchasers → send the 3-line "you're already in" variant instead | Maximize hour-one velocity & AOV via bundles + GWP |
| 3 | **Mid-Sale Scarcity & Social Proof** | Sat 11/28, 10:00 AM ET | Opened/clicked E1–E2, non-purchasers + browse abandoners | Anyone who already bought (send "ignore the urgency" P.S. version) | Convert the deciders with real numbers and real reviews |
| 4 | **The Final 4 Hours** | Sun 11/29, 8:00 PM ET | All non-purchasers + open cart abandoners | Recent purchasers, low-engagement >120 days | Close the loss-aversion gap; no new information |
| 5 | **Cyber Monday Pivot** | Mon 11/30, 8:00 AM ET | Non-purchasers + Friday browserships + gift shoppers | Anyone who bought Fri–Sun gets the price-protection version | New category, new reason, zero "we extended it" damage |

**Cadence logic:** one email per 24h maximum for any single profile, except the Fri→Sat pair. Anyone who purchases is moved to a *post-purchase* flow immediately and stops receiving promo urgency. Frequency cap: **max 4 promo emails in any 7-day window per profile**.

---

## Email 1 · VIP Early Access
### `T-48H` · The secret door, not a deeper discount

#### 1. 触发时机与发送策略 · Send Time & Strategic Purpose

- **Send:** Wed, Nov 25. The access *window* technically opens at 12:01 AM ET, but the email goes out at **7:00 AM in the recipient's own timezone** (Klaviyo Smart Send Time or a timezone-based segment split). A midnight VIP email gets buried by Thursday morning.
- **Audience:** Customers with ≥1 purchase in the last 12 months, plus 90-day clickers who haven't bought yet. This is a **status segment**, not a discount segment.
- **Mechanic:** A hidden, non-indexed collection (Shopify password page / customer tag-gated collection) with the **exact same pricing as Black Friday**. No extra 5%, no stacked code. The privilege is *time and inventory*, not price.
- **Strategic purpose:** (a) pull high-intent revenue forward so Friday's warehouse and support load is predictable; (b) generate real demand data to reallocate stock before the public drop; (c) make your best customers feel seen *before* you ask the whole list for money; (d) protect price integrity — if VIPs get a better deal on Wednesday, every smart shopper learns to wait for the "real" discount next year.
- **Klaviyo setup:** Flow triggered by a segment-membership event or a scheduled campaign; add a `VIP_Early_Access` profile property so Email 2 can branch the copy.

#### 2. 主题行 A/B 测试 · Subject Line A & B

| | Subject Line | Emoji | Hook / Variable Being Tested |
|:--|:--|:--|:--|
| **A** | `Your 48-hour head start is open 🔑` | 🔑 | Explicit benefit + time privilege (clarity) |
| **B** | `We didn't send this to everyone 🤫` | 🤫 | Curiosity gap + in-group exclusivity (mystery) |

**Test design:** split 50/50 on a 20% sample, judge on **unique open rate** at +4 hours, roll the winner to the remaining 80%. A typically wins on cold segments; B typically wins on high-LTV repeat buyers. Keep subject lines under 45 characters where possible.

#### 3. 预览文本 · Preview Text
