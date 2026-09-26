# Build Your First Mobile App with AI 📱

A step-by-step guide for students. No coding experience needed — you will tell an AI what to build, and it will write all the code for you. Your job is to have ideas, test the app on your own phone, and make it better.

**What you'll need before starting:**

- A computer (Mac or Windows) with an **AI coding assistant** installed — either one works (ask a parent to help set it up; both require a paid plan):
  - **Claude Code** (the Claude desktop app, Code tab), or
  - **Codex** (OpenAI's coding agent, in the ChatGPT desktop app or the Codex CLI)
- A smartphone (iPhone or Android)
- Your phone and computer connected to the **same Wi-Fi network**
- About 1–2 hours

---

# Module 1 — Make a Mobile App and Run It on Your Phone

You are going to build a real mobile app using **React Native** (the same technology used by apps like Instagram and Discord) and preview it on your phone with a free app called **Expo Go**. You won't write a single line of code — your **AI coding assistant** (Claude Code or Codex) will do that part.

> 💡 **How this works:** you type instructions (called **prompts**) to your AI assistant, and it writes the code, fixes the errors, and runs the app. The prompts in this guide work the same in Claude Code and Codex — copy them exactly, or change them to fit your idea.

### Step 1 — Create a new folder and start a fresh session

1. On your computer, create a new **empty folder** — name it something like `my-mobile-app`.
2. Open your AI assistant **in that folder**:
   - **Claude Code:** open the Claude desktop app, go to the **Code** tab, start a **New Session**, and choose your new folder as the working folder.
   - **Codex:** open Codex (in the ChatGPT desktop app, or by running `codex` in a terminal) and pick your new folder as the project/working folder.

Then send this prompt to make sure everything is set up:

```
Please confirm we are in a brand-new session working in a new empty folder.
I'm going to build a new mobile app project here today.
```

### Step 2 — Set the permission mode to Auto

Your AI assistant will need to create files and run commands. Set its permission/approval mode to **Auto** so it can work without asking you to approve every small step:

- **Claude Code:** in the session's permission settings, choose **Auto** (not Ask).
- **Codex:** choose the **Auto** approval mode (the default in most setups; avoid "full access" — Auto is enough).

### Step 3 — Install Expo Go on your phone

- **iPhone:** App Store → search **"Expo Go"** → install (free)
- **Android:** Play Store → search **"Expo Go"** → install (free)

Expo Go is like a "previewer": it lets your phone run the app you're building right now, without publishing anything to the App Store.

More info: https://expo.dev/go

### Step 4 — Check that phone and computer are on the same Wi-Fi

Your phone talks to your computer through your Wi-Fi network. Open Wi-Fi settings on both devices and make sure they're connected to a network with the **same name**. (If your home Wi-Fi has two names, like one with "5G" and one without, connect both devices to the same one.)

### Step 5 — Find your Expo Go version number

1. Open Expo Go on your phone.
2. Go to **Settings** and scroll to the bottom.
3. Find the version number, for example `54.0.10` — you only need the first number: **54**.

Write it down. **This step matters:** if the versions don't match, your phone will show an error and refuse to open the app.

### Step 6 — Decide what app to build, and send the big prompt

Think of a simple app idea for your first build. Good first projects:

- A to-do list
- A daily water-drinking tracker
- Flashcards for studying vocabulary
- A homework planner
- A simple habit tracker

Copy the prompt below, replace the two 【placeholders】, and send it to your AI assistant:

```
Please build me a 【your app idea, e.g. "to-do list"】 mobile app using React Native (Expo).

I'm not a professional programmer, so please keep things simple — I don't need to
read the code or debug anything. The app doesn't need a backend server or a
database; saving data locally on the phone is fine.

Very important: the Expo Go app on my phone supports SDK version 【your number
from Step 5, e.g. 54】. Please make the project use exactly that Expo SDK version —
not a newer one — so I don't get a "requires a newer version of Expo Go" error.

When you're done, start the development server and show me a QR code so I can
scan it with Expo Go on my phone.
```

Now wait a few minutes while your AI assistant builds your app. It's okay if it asks you questions — if you're not sure, just reply: `You decide.`

### Step 7 — Scan the QR code and open your app 🎉

Your AI assistant will show you a QR code.

- **iPhone:** open the built-in Camera app, point it at the QR code, and tap the yellow **"Open in Expo Go"** banner.
- **Android:** open Expo Go and tap **"Scan QR code"**.

Wait a few seconds… and your app appears on your phone. You just built a mobile app!

### Step 8 — If your phone says "requires a newer version of Expo Go"

Don't panic — it's just a version mismatch. First double-check the number from Step 5, then send this:

```
My phone's Expo Go shows "The project you requested requires a newer version of
Expo Go". The SDK version my Expo Go actually supports is 【your number】. Please
change the project to exactly that Expo SDK version, restart the development
server, and give me a new QR code.
```

### Step 9 — Make it better: iterate!

Here is the most important secret of building things with AI:

> **It's all about the iteration.** Nobody gets it right on the first try. An OK product takes 50–100 rounds of changes. A great one takes 100+. Every round makes it better — so don't be afraid to ask for changes, big or small.

Pick a change and send a prompt like this:

```
Please improve this app: 【your change idea】.

After the change, make sure the app on my phone refreshes automatically so I can
see the new version right away.
```

Good change ideas to try:

- Make the design more beautiful
- Add a menu bar at the bottom
- Add a dark mode
- Change the main color to your favorite color
- Play a fun celebration animation when a task is completed
- Add a statistics page

Do at least **5 rounds** of changes. Test on your phone after each one.

### Step 10 — Confirm and celebrate

Send one last prompt:

```
Please confirm the app is running correctly on my phone, and summarize in simple
words what features this app has now.
```

Show it to your family and friends. You made this. 👏

---

# Module 2 — Ideate Your Personal Project: Find a Problem Worth Solving

You've proven you can build an app. Now comes the part that separates a *builder* from a *tutorial-follower*: building something **you** actually care about. Great apps don't start with code — they start with a **problem**.

### Step 1 — Hunt for problems (15 minutes)

Grab paper or a notes app. For each area below, write down anything that is annoying, boring, slow, easy to forget, or "I wish there was an app for this":

| Area | Ask yourself… |
|---|---|
| **School** | What do I keep forgetting? What's annoying about homework, tests, schedules? |
| **Home & family** | What do we argue about? Chores? Screen time? Who's cooking? |
| **Hobbies** | Sports, games, music, art, collections — what's hard to track or practice? |
| **Friends** | Planning hangouts, splitting things, remembering birthdays? |
| **Me** | Sleep, habits, saving money, learning something new? |

Rules for this step:

- Write down **at least 10 problems**. Quantity over quality.
- No idea is too small or too silly. "I always forget my PE uniform on Tuesdays" is a *great* problem.
- Write **problems**, not app ideas. ("I forget to water my plant" ✅ — "a plant app" ❌, that comes later.)

### Step 2 — Pick your top 3

Score each problem from 1–5 on these three questions, and add up the points:

1. **Do I really have this problem?** (Not someone imaginary — you, or someone you actually know.)
2. **How often does it happen?** (Daily beats once-a-year.)
3. **Could an app on a phone realistically help?**

Take the 3 highest scores. These are your candidates.

### Step 3 — The one-sentence test

For each of your top 3, fill in this sentence:

> **"________ (who)** has the problem of **________ (what)**, and my app will help by **________ (how)**."

Example: "**My little brother** has the problem of **forgetting to feed the fish**, and my app will help by **sending a fun reminder and tracking a feeding streak**."

If you can't fill in the sentence clearly, the idea isn't ready — pick another. If you can, you've found your project. Pick the **one** sentence that excites you most.

### Step 4 — Sketch the smallest version (MVP)

Big apps fail; small apps ship. List:

- **The ONE thing** your app must do (the core feature)
- **2–3 nice-to-haves** to add later — *after* the core works

Example for the fish app: core = "tap a button when you feed the fish, see the streak." Later: reminders, fun fish animations, a family leaderboard.

### Step 5 — Interview one real person

Tell your one-sentence pitch to someone who has this problem (a friend, parent, sibling, classmate). Ask:

1. "Would you actually use this?"
2. "What's the ONE thing it must do?"
3. "What would make you stop using it?"

Listen more than you talk. Update your sketch based on what you hear.

### Step 6 — Build it

Go back to Module 1, Step 6 — but this time, replace the app idea with **your** project. Describe the core feature clearly in the prompt, for example:

```
Please build me a mobile app using React Native (Expo) that helps 【who】 with
【problem】. The most important feature is: 【your ONE core feature】.

I'm not a professional programmer, so please keep things simple — no backend
server or database needed; saving data locally on the phone is fine.

Very important: my Expo Go supports SDK version 【your number】 — please use
exactly that Expo SDK version.

When you're done, start the development server and show me a QR code to scan
with Expo Go.
```

Then iterate, iterate, iterate — show it to the person you interviewed, collect feedback, and do another round. That loop (build → test → feedback → improve) is exactly how real products are made.

---

## Quick troubleshooting

| Problem | Fix |
|---|---|
| Phone can't load the app / QR does nothing | Check both devices are on the **same Wi-Fi** (Step 4) |
| "Requires a newer version of Expo Go" | Use the fix prompt in Module 1, Step 8 |
| Your AI assistant asks a question you don't understand | Reply: `You decide.` |
| Something broke after a change | Tell your AI assistant what you see on the screen, in plain words: "After the last change, the app shows a red error screen that says ___. Please fix it." |
| App disappeared from phone after closing everything | On the computer, ask your AI assistant: "Please start the development server again and give me a new QR code." |

Have fun — and remember: every app you admire started as version 1 that kind of stunk. Iterate. 🚀
