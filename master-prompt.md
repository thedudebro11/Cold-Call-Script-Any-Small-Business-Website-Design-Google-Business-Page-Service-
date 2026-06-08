# MASTER PROMPT — Cold Call Assistant Builder
### Paste this entire prompt into a fresh Claude session to auto-build the full project.

---

## YOUR ROLE

You are a senior full-stack developer and copywriter. You will read this entire prompt, then autonomously build every deliverable listed below in order. After each deliverable is created, log what you did in a build log. When everything is complete, output a full project summary.

Do not ask for confirmation between steps. Build everything, document everything, then summarize at the end.

---

## CONTEXT

Oscar is a freelance web designer based in Tucson, Arizona. He cold calls local businesses to sell:

- **One-Time Package ($500–$1,000):** Custom website + Google Business Profile optimization + analytics setup
- **Monthly Retainer ($200/mo):** Ongoing GBP management, review responses, content updates, monthly reporting

His pitch is built around helping local businesses (nail salons, barbershops, restaurants, gyms, plumbers, etc.) get more customers through better online visibility — not just a pretty website.

---

## THE PITCH FLOW (build everything around this)

**Step 1 — Opening**
- "Did I catch you at a bad time?"
- If no: "Perfect. Hey, I was checking out your website — looks really solid. Quick question though — how much of your business actually comes from people finding you online versus word of mouth or repeat customers?"
- If yes: "No worries at all — when's a better time to reach you?"

**Step 2 — Qualify the Pain**
- "Roughly how many phone calls or walk-ins do you get per month right now?"
- "Of those, how many actually turn into bookings or sales?"
- "What's the average value of a booking for you?"

**Step 3 — The Math Moment**
- Take their booking value, multiply by 5 extra bookings/month
- Say it out loud: "So if we get you just five more bookings a month, that's [X] in extra revenue. This pays for itself in the first month."
- Reverse it: "How much are you losing every month by not showing up in local search?"

**Step 4 — Introduce the Offer**
- "What I do is build high-converting websites Google can actually rank, optimize your Google Business Profile so people find you locally, and set up analytics so you can see exactly what's working."
- "One-time setup fee for the build. If you want, I manage it ongoing every month — reviews, listings, content — so you stay visible."

**Step 5 — Close to a Meeting**
- "Would it make sense to grab fifteen minutes next week? I can show you exactly what you're missing."

**Step 6 — Retainer Objection**
- "You need just four extra bookings a month for this to pay for itself. We're going to get you way more than that."
- "Most businesses spending on ads spend way more than two hundred a month and see less results."
- "Would you rather pay two hundred to keep those extra bookings coming, or let it slide and lose that income?"

**Step 7 — Risk Reversal**
- "Do the build for five hundred. Try one month at two hundred. If you're not seeing extra customers, we part ways. But I'm confident you will be."

---

## DELIVERABLES — BUILD ALL OF THESE IN ORDER

### DELIVERABLE 1 — Interactive Call Assistant (HTML single file)

Build a single dark-themed HTML file called `call-assistant.html`.

**Requirements:**
- Dark background (#0a0a0a), orange accent (#FF6B35), clean sans-serif font
- Step-by-step flow — user taps through each stage of the call (Opening, Qualify, Math, Offer, Close, Objections, Risk Reversal)
- Each step shows the exact lines to say
- Built-in live calculator on the Math Moment step: input fields for booking value and target extra bookings/month, auto-calculates extra revenue and monthly loss
- Notes field on each step so Oscar can jot down the prospect's answers in real time
- Progress bar across the top showing which step he's on
- "Bad Time" escape button on Step 1 that shows the callback line instead
- Mobile-first — this will be used on a phone before/during calls
- Smooth step transitions
- Reset button at the end to start a new call

### DELIVERABLE 2 — Cold Call Script (Markdown)

Build a clean markdown file called `cold-call-script.md` with:
- Full pitch flow broken into labeled sections
- Exact lines to say in blockquotes
- Objection handling section
- Tips and notes section at the bottom
- Pricing table at the top

### DELIVERABLE 3 — One-Pager Pitch Sheet (HTML)

Build a single-page HTML file called `pitch-sheet.html` that Oscar can screen-share or send as a link during or after a call.

**Requirements:**
- Clean, professional, minimal design
- Sections: What You Get, How It Works (3 steps), Pricing, The Math (show the ROI example), Testimonial placeholder, Call to action
- Oscar's branding: dark theme, orange accent
- Print-friendly

### DELIVERABLE 4 — Objection Cheat Sheet (Markdown)

Build a markdown file called `objections.md` covering the most common objections:
- "I already have a website"
- "I don't have the budget right now"
- "I handle my own Google page"
- "Can I think about it?"
- "I'm not sure I need this"
- "What results can you guarantee?"

For each objection include: the reframe, the response line, and the follow-up question to keep the conversation going.

---

## BUILD LOG INSTRUCTIONS

After completing each deliverable, append a log entry in this format:

```
✅ DELIVERABLE [N] COMPLETE
File: [filename]
What was built: [one sentence]
Key decisions: [any notable choices made]
```

---

## FINAL SUMMARY INSTRUCTIONS

After all deliverables are complete, output a section titled:

### 📦 PROJECT COMPLETE — Here's What Was Built

List every file, what it does, and how Oscar should use it. Then add a "Next Steps" section suggesting what to do after the build — like setting up a domain, testing the call flow, or customizing with his real info.

---

## BEGIN

Read everything above. Build all four deliverables in order. Log each one as you go. Output the final summary when done. Do not stop to ask questions.
