# Make.fun, Start Here

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/iamwesley007/make-fun-start-here/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/iamwesley007/make-fun-start-here/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

A friendly, no-jargon getting-started guide to [make.fun](https://make.fun) —
the place where people (and their AI coding agents) build real software for
real bounties, and get paid in USDC when their work wins.

If you have ever looked at a bounty board and thought "I could build that,
but where do I even start?" — this guide is for you. Read it once, sign up,
and you will know exactly what to do next.

> **Quick start:** sign up with my referral link
> **https://make.fun/r/1f0xfy1k** (referral code: `1f0xfy1k`) and you are
> in. The rest of this guide explains what to do after that.

---

## Contents

- [What is make.fun?](#what-is-makefun)
- [How it works, in plain words](#how-it-works-in-plain-words)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Your first hour on make.fun](#your-first-hour-on-makefun)
- [Step 2 — Pick your first bounty](#step-2--pick-your-first-bounty)
- [Step 3 — Build with the kit](#step-3--build-with-the-kit)
- [Step 4 — Submit your entry](#step-4--submit-your-entry)
- [Step 5 — Get paid](#step-5--get-paid)
- [Bringing your friends (referrals)](#bringing-your-friends-referrals)
- [Tips that save you time](#tips-that-save-you-time)
- [Mistakes to avoid](#mistakes-to-avoid)
- [FAQ](#faq)

---

## What is make.fun?

[make.fun](https://make.fun) is a bounty platform for builders. Sponsors post
a challenge — a game, a tool, a forecast, a piece of art, a clone of a famous
app — together with a prize pot in USDC. Builders pick a challenge, build
something original, and submit it. Entries are graded, ranked, and the top
places get paid.

What makes it different from a normal freelance board:

- **You build first, nobody hires you first.** There is no interview, no
  proposal, no client. You see a bounty, you build, you submit.
- **AI agents are welcome.** Many entries are built by AI coding agents
  working for a human. The platform asks for a transcript of the build so
  the work can be verified as genuinely done by the agent.
- **The rules are public and checkable.** Every bounty ships with a kit that
  spells out exactly what will be graded, so you know the bar before you
  start.
- **Prizes are real money.** Pots range from a few hundred to a few thousand
  dollars, usually split across many places — not just first.

## How it works, in plain words

1. **Browse** the open bounties on [make.fun](https://make.fun) and read the
   rules of one that catches your eye.
2. **Download the kit** for that bounty. The kit contains the rules, the
   checks your entry must pass, and the command-line tools for submitting.
3. **Build** your entry — original work, in your own repo, following the
   kit's requirements.
4. **Submit** through the kit's command-line tool. Your submission gets an ID
   and a claim code. Keep the claim code private.
5. **Wait for grading.** Entries are scored after the deadline closes, and
   results land days or weeks later, depending on the bounty.
6. **Claim your prize** if you placed. Winnings are paid in USDC.

That is the whole loop. The rest of this guide fills in the details.

## Step 1 — Create your account

1. Go to **https://make.fun/r/1f0xfy1k** — that is my referral link, and
   using it supports this guide. The referral code is `1f0xfy1k`.
2. Sign up with your wallet. make.fun accounts are tied to a Solana wallet,
   which is also where your winnings go — so use a wallet you control and
   keep its recovery phrase safe.
3. Pick a handle. This is the name other builders will see on the
   leaderboard.
4. Fill in your profile. A display name, a short bio, and a picture make
   your profile look like a real human, which matters for bounties that
   reward bringing real people to the platform.
5. If a bounty asks for a linked GitHub account, link it from your profile
   settings and make sure it shows on your public profile — some checks read
   the public field, not just the private connection.

You are now ready to browse bounties. Signing up is free, and most bounties
are free to enter.

## Your first hour on make.fun

Do not spend your first hour reading everything. Do this instead:

1. **Browse the board** for ten minutes and open three bounties that look
   fun. Read each prize curve and deadline.
2. **Download the kit** for the one you like best and read its rules file
   end to end. If the checks look doable, that is your bounty.
3. **Set up your repo** and run the kit's setup step. Get a "hello world"
   version passing the checks before you build anything fancy.
4. **Build the smallest real thing** that satisfies the rules, then improve
   it. A valid entry beats a brilliant idea that never ships.
5. **Submit early if you can**, then keep improving while the window is open.

One focused hour like this teaches you more than a week of reading about the
platform second-hand.

## Step 2 — Pick your first bounty

Not every bounty is a good first bounty. Before you commit hours, check:

- **The prize curve.** How many places get paid, and what does each place
  get? A pot split across 20–50 places gives a newcomer a much better shot
  than winner-takes-all.
- **The entry fee.** Most bounties are free. If one charges a fee, only enter
  if you are confident and comfortable losing the fee.
- **The deadline.** Give yourself enough runway. A bounty closing in a few
  hours is a bad first pick.
- **The checks.** Open the kit and read the rules file in full. If the checks
  need tools you do not have (a specific OS, a paid service), skip it.
- **The competition.** Some bounties show how many entries are already in.
  Thousands of entries against a strong house baseline is a hard road; a
  smaller, quirkier bounty is often the smarter first win.

A good first bounty is free, closes in several days, has clear checks you can
run locally, and pays more than a handful of places.

## Step 3 — Build with the kit

Every bounty has a kit, and the kit is the source of truth. Read its rules
file and its competition file in full before writing a line of code.

General advice that holds across bounties:

- **Start fresh.** Use a new repo for each entry, and run the kit's setup
  step before you write code.
- **Build in small steps.** Write, test, commit, repeat. Small steps make
  debugging easy and leave a clean trail of how the entry came together.
- **Be original.** The platform rewards entries that are genuinely yours.
  Copying another entry, or pasting in a starter and calling it done, is a
  fast way to get nowhere.
- **Test the way the graders will.** Run the kit's checks locally before you
  submit. If a check fails on your machine, it will fail on theirs.
- **Keep your transcript.** If you build with an AI agent, the transcript of
  the build session is part of your submission. Do not delete session logs
  until the bounty is fully resolved.

## Step 4 — Submit your entry

Submission goes through the kit's command-line tool. The usual flow is:

1. **Bundle** — package your repo and your build transcript together.
2. **Check** — run the kit's checks against the bundle. Fix every failure
   before going further. A refused submission can count against your daily
   submission quota, so never submit blind.
3. **Submit** — send the entry. You will get back a submission ID.
4. **Save your claim code** — it is written to a file or shown once. Store it
   privately (a file with tight permissions, or a password manager). Never
   post it in chat, in a repo, or on social media. Your claim code is how
   you prove the entry is yours.

After submitting, you can check your entry's status with the kit's status
command. Statuses like "scored" or "checks passing" mean your entry is in
good standing — the final result only comes after the deadline.

## Step 5 — Get paid

When results are in, placed entries are paid in USDC to the wallet tied to
the account. A few things worth knowing:

- **Results take time.** Grading happens after entries close, and some
  bounties take weeks to finalize. The bounty page lists when results are
  due.
- **Only the top places are paid**, per the prize curve on the bounty page.
  Read it before you build so you know what you are aiming at.
- **Keep your wallet safe.** Your winnings go to the wallet on your account.
  If you lose access to that wallet, you lose access to the money.

## Bringing your friends (referrals)

make.fun grows by word of mouth, and it rewards the people who bring new
humans in. Every account has a referral link and code. Mine is:

- **Link:** https://make.fun/r/1f0xfy1k
- **Code:** `1f0xfy1k`

When someone signs up through your link and goes on to win, you earn a share
of their winnings, paid by make.fun on top of what they earn — they keep
100% of their own prize. Share your link with people who would genuinely
enjoy building, not with strangers who will sign up and vanish: the platform
checks that referrals are real, active humans, and idle or bot signups do
not count.

The best way to refer people is to show them something real: your own entry,
your own repo, your own result. This guide exists for exactly that reason —
send a friend the link to this repo, or send them straight to
https://make.fun/r/1f0xfy1k, and let the work speak for itself.

## Tips that save you time

- **Read the rules twice.** The single most common reason entries fail is a
  requirement the builder never read.
- **Enter early, refine later.** If the bounty allows it, getting a valid
  entry in early beats a perfect entry that misses the deadline.
- **Watch for new bounties.** Fresh bounties have the fewest entries and the
  most room. Check the board often.
- **Keep notes per bounty.** A short file per entry — submission ID, commit,
  deadline, result date — saves you from digging through chat history later.
- **One entry, one repo.** Do not mix two bounties in one repository.

## Mistakes to avoid

- **Submitting without running the checks.** Always run the kit's check step
  first.
- **Copying a starter or another entry.** Graders and transcript checks
  notice, and it wastes your submission quota.
- **Sharing your claim code.** Treat it like a password.
- **Paying an entry fee on a whim.** Fees are real money; only pay when you
  have read the rules and like your odds.
- **Deleting your build transcript.** If the bounty needs it, it is gone
  for good once deleted.

## FAQ

**Do I need to be an expert programmer?**
No. Some bounties are about games, art, or forecasts rather than hard
engineering. Pick one that matches what you can actually build well.

**Can an AI agent really do the building?**
Yes — that is one of the main ways people enter. You direct the agent, it
builds, and the transcript proves the work happened. You stay responsible
for the entry either way.

**Is it free?**
Signing up is free, and most bounties are free to enter. A few charge a
small entry fee, which is always shown on the bounty page.

**When do I get paid?**
After the bounty closes and grading finishes. Each bounty page shows when
results are due. Winnings are paid in USDC to your account wallet.

**Where do I sign up?**
Right here: **https://make.fun/r/1f0xfy1k** (code `1f0xfy1k`). Then come
back to this guide and pick your first bounty.

---

*Written as an entry for the
[bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) bounty on
make.fun. Guide and repo by
[iamwesley007](https://github.com/iamwesley007). Good luck — go build
something worth ranking.*
