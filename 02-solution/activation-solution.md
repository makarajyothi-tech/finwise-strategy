# The Solution · FinWise

> Module 2 · Acquisition & Activation. The onboarding solution and the Aha moment that makes value land.

## Aha moment

1. The Aha moment (most plausible)
"I can see where my money is actually going — and it took 30 seconds."

For SMB financial software, the emotional payoff isn't a feature, it's clarity: the moment a user sees their real transactions auto-categorized into a cash-flow view they didn't have to build. Everything before that is friction; everything after is retention work. If FinWise can't connect a bank feed, the fallback Aha is: importing a CSV of transactions and seeing the same categorized dashboard instantly.

Why this one: it's the moment the product does work for the user instead of asking work of them — which is exactly what separates the 2% who convert.

2. Minimum screens: 4
#	Screen	Single job	One action asked
1	Sign-up	Create account, nothing else	Email + password (or Google SSO). No company size, no role, no phone.
2	Connect data	Get real financial data in	Connect bank feed or upload CSV or "explore with sample data" (three doors, one job).
3	Processing → reveal	Bridge the wait with momentum	Nothing — auto-advance. Show live progress ("Categorizing 1,240 transactions…"), then land on the dashboard.
4	Aha dashboard	Deliver the payoff	One guided action only: "See your top 3 spending categories" or "Your cash runway is 4.2 months." No settings tour, no feature checklist.
3. What got cut (and why)
Team invites, profile setup, company details → move to post-Aha, triggered when a feature needs them.
Product tour / tooltip parade → the dashboard is the tour if you anchor one insight.
Goal-setting wizard → fold into the quiz on screen 2 only if it changes what data gets connected (see below).
4. Where personalization / pre-fill shortens the path
Screen 2, one-question quiz (max 2 questions): "What do you want to see first?" (Cash flow / Expenses / Invoicing). This isn't decoration — it decides which insight card leads the dashboard on screen 4, making the Aha feel personal. More than 2 questions and you've added a screen, not removed one.
Pre-fill everywhere possible: company name from email domain, currency from locale, industry from domain lookup. Never ask for data you can infer.
Sample-data escape hatch: users who won't connect a bank on day one still hit Aha with realistic demo data — then you re-prompt bank connection from inside the dashboard, when trust is higher. This alone often lifts activation more than any copy change.
The one metric to watch
Time-to-Aha (sign-up → first categorized insight viewed). If screen 2's bank connection is the drop-off cliff, the sample-data path is your lever; if it's screen 1, cut sign-up to SSO-only.

_____

## Onboarding prototype

[Prototype link](https://trial-aha-path.lovable.app/)

_____

## Why this activates

Why the 4-screen flow works
1. It's built backwards from one moment, not forwards from features. The whole design serves a single payoff: "I can see where my money is going — in 30 seconds." Every screen either moves the user toward that moment or gets cut. Most onboarding fails because it's a checklist (profile, team, integrations, preferences) — each step feels like setup before value. Here, even the sign-up screen is already pulling toward the insight.

2. Each screen has exactly one job, so there's no decision fatigue. Sign-up asks one thing. Connect asks one question with two buttons. The dashboard does one reveal. When a screen asks two things, users do neither; when it asks one, the button-click rate roughly doubles. That's why "the one action it asks of the user" was a hard rule, not a style preference.

3. The bank-connection deferral is the riskiest bet — and the highest-value one. Bank connection is the single biggest drop-off in fintech onboarding (credential anxiety, trust not yet earned). Placing it at screen 2 before trust exists would kill activation. Instead, the user sees the cash-flow view first — with realistic sample data — and the connection prompt appears from inside the product, after they've already felt the value. You're asking for the commitment after the first dose, not before it.

4. The sample-data path makes Aha unconditional. The original design only worked if the user connected a bank. Now the Aha moment is reachable by everyone, including people who came to "just look around" — which is most trial users in a product-led motion. The 28-second framing also sets a pace expectation that makes skipping steps feel like falling behind.

5. Personalization (business type) doubles as data collection. The one question on screen 2 isn't a quiz — it's what makes the demo feel like their business ("Brightleaf Bakery" for a bakery, different categories for a consultant). Users read a tailored demo as proof the product gets them, and you collect a segmentation field without ever asking for "company size" on a form.

The underlying principle: in a reverse trial, activation is the conversion funnel. A user who reaches the categorized cash-flow view in 30 seconds has already imagined their real business in the product — and that's the moment a purchase decision actually starts

_____
