**Live site:** https://tsakane25.github.io/sciar-tips/

**Repository:** https://github.com/Tsakane25/sciar-tips

**Question:** Can the lowest-paid person at Halloran's see what the split rule does to his hours, and raise it without being identified?

## Part 1: The people

**Internal: Aoife Rennick, CEO (04-aoife.md).** She needs an alpha she can show investors on Friday that works where staff are: "Nearly all restaurant staff only have phones."

**External: Rafael, kitchen porter (01-rafael.md).** He needs to understand his pay without being exposed: "i dont understand how they count it" and "please dont say it was me who ask".

**Accessibility and culture.** Rafael writes in his second language and says "my phone screen is broken so i cannot read the page good". So the staff view uses large text, plain short words, one figure per card, and tap-to-choose topics.

## Part 4a: Theory behind the build

**Leadership: transactional leadership (Burns, 1978; Bass, 1985).** Declan leads by exchange: points per hour by role, paid weekly, unexplained ("They don't need the formula, they need the money", 02-declan.md). It explains why the rule is accepted: the reward is predictable. It misses the personal dependence underneath. Rafael stays quiet partly because Declan "is good to me with my visa letter" (01-rafael.md), which is closer to paternalistic leadership (Pellegrini & Scandura, 2008), where care makes challenge costly.

**Culture: organisational silence (Morrison & Milliken, 2000).** Niamh reads no complaints as fairness: "Nobody has ever complained" (03-niamh.md). But Rafael asked her in September and was told it "is the system". The data shows why he asked: from week 9 his hours rose from 40.3 to 51.3 a week, yet 20.6 of them earned nothing (payouts.csv, staff_id = S12, weeks 1–8 vs 9–12, mean of hours and hours_after_2300). Silence here is a signal, not consent.

**Design, advantage, limit.** Silence theory shaped the concern route: it bypasses Niamh, goes to Sciar, and the owner sees only counts of three or more. A payout tool only owners can see is easy to copy; one staff trust is harder to copy and serves both sides (Barney, 1991), if owners accept it, which Aoife doubts. Limit: both theories say little about language or migration status, which shape Rafael's silence more than the rota does.

## Part 4b: Decision record

**Decision 1: request changed.** Aoife asked to drop "raise a concern" (04-aoife.md); Niamh agreed (03-niamh.md). Options: drop it; send concerns to the manager; send them privately to Sciar, with the owner seeing counts only. Criteria: the brief requires it; Rafael's anonymity; owners must still sign up. What decided it: from week 9 Rafael is the only kitchen porter (payouts.csv, role = kitchen porter, weeks 9–12: 1 row per week), so any concern routed by role or through Niamh identifies him. What would change my mind: owners refusing to join because of it, or a staff representative whom staff already trust. Aoife's underlying need is that owners do not "run a mile". The owner never sees names or words, and there is no public "moaning wall".

**Decision 2: AI suggestion rejected.** The AI's first app.html was one long scrolling report. Options: keep it, or rebuild it as a four-tab phone app. Criteria: Rafael's broken screen, Aoife's point about phones, sources staying on screen. The phone app won, with sources as small lines under each figure. What would change my mind: staff testing showing one long page is easier to read on a damaged screen.

**Bias.** Automation bias: when the AI asked me to choose my stakeholders, I skipped the question and it chose Rafael and Aoife for me. I checked it against the messages only afterwards.

## Part 4c: The Struggle (written without AI)

*I used AI to help me ananlyse the case and give eme an understanding of what ever was needed on my end in simple English terms.In Github when I uploaded the data log folder it changed the files into single files and I had to add the word “data” in front of the all toto be able to put them into one single folder.And during all of this I had to the AI lof eneded going into this folder and I had to retrieve it. The problem at first was that the app came back looking like an app and I went back to calude to ask it to make it more like an app which he did was was very pleased. Next time I am asking him to actualy do the app or make it look like an app before hand and another thing I also could have done was to implement a second language in the app.*

## Assumptions

- Halloran's and Sciar are fictional; all figures come from the pack's data/ folder.

- No wage data is in the pack, so Niamh's claim that chefs' "better hourly rate" evens things out cannot be checked and is treated as claimed.

- "Floor" groups floor manager, servers and bar (8 people); "Kitchen" groups chefs and kitchen porters (5, then 4). Roles with one or two people are never shown alone.

- Concerns in the alpha are stored in the browser only, as the app says.

- The staff picker in app.html is a demo control so a marker can check any person's figures; a real app would show only the logged-in person.
