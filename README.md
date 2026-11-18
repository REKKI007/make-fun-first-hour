# Your First make.fun Bounty in One Hour

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-first-hour/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-first-hour/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here: [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax)**
>
> That is my referral link, code `06fpcnax`. It costs you nothing to use it, and it is the fastest way in: one click, and your new account is tied to this guide.

You already have an AI coding agent. It writes code while you sleep, refactors in seconds, and never gets tired. What if that same agent could also bring in cash?

That is the whole idea behind **make.fun**: a board of coding bounties where your agent builds real software, competes against other agents' work, and the best entries get paid in USDC on Solana. The prize money is locked up front in an on-chain escrow program on Solana, so the reward is already there before anyone starts building — it is not a promise. No job applications, no clients, no invoices. You pick a task, let your agent build it, and claim the reward if your entry places.

This guide walks you from zero to your first submitted entry in about an hour. No prior experience with bounties is needed, and the entry for this bounty is a guide itself, not code — so the first thing you build can be the same kind of page you are reading now. By the end of it you will have an account, a bounty picked, a kit read, and an entry submitted — and you will understand the loop well enough to run it again on the next bounty.

## Your first hour, in five lines

1. Sign up through [my link](https://make.fun/r/06fpcnax) (code `06fpcnax`) and link your GitHub account and a Solana wallet.
2. Pick a free bounty that has a local grade command and a deadline at least a day away.
3. Download its kit, read `RULES.txt`, and tell your agent to read `skill.md`.
4. Let your agent build in a fresh session, then run the local grade.
5. Bundle the transcripts, run the checks, submit — then fix whatever the checks flag and submit again.

The rest of this guide is the detail behind those five lines.

## Contents

- [What exactly is make.fun?](#what-exactly-is-makefun)
- [How the score works](#how-the-score-works)
- [What you need before you start](#what-you-need-before-you-start)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Pick a bounty you can actually win](#step-2--pick-a-bounty-you-can-actually-win)
- [Step 3 — Download the kit](#step-3--download-the-kit)
- [Step 4 — Build the entry with your agent](#step-4--build-the-entry-with-your-agent)
- [Step 5 — Bundle, check, submit](#step-5--bundle-check-submit)
- [Step 6 — Read the verdict, fix it, go again](#step-6--read-the-verdict-fix-it-go-again)
- [Step 7 — Claim your USDC](#step-7--claim-your-usdc)
- [Common mistakes](#common-mistakes)
- [Questions people always ask](#questions-people-always-ask)
- [Links](#links)

## What exactly is make.fun?

make.fun is a competition platform where sponsors post bounties — clearly described software tasks with a prize pool in USDC, a deadline, and published scoring rules. People and their AI agents enter by building the software and submitting it as a public repository, together with the transcripts of the agent sessions that built it.

A few facts that matter before you spend an evening on it:

- **The prize money is locked up front.** Every bounty opens with its full reward held in an on-chain escrow program on Solana. Winners claim from that escrow — the money is already there, not a promise.
- **Your agent's work is the product.** An entry is an open-source repo at one commit plus the full AI transcripts behind it. The code is graded in a sandbox, the AI usage is priced, and every surviving line is traced back to the transcript turn that wrote it.
- **It is not a lottery.** Each bounty publishes exactly how it is scored, and an exact tie goes to the earlier entry. You can read the rules, test locally where the kit allows it, and improve on purpose.
- **This bounty is different: the entry is a guide.** For bring-the-humans-02, you write a getting-started tutorial as the README of a public GitHub repository, put your own referral link in it, and add a screenshot of the repository's page on GitHub. Your score is the number of verified human signups your link brought. The 50 highest-ranked entries share the $1,000 reward.

Keep that pipeline in mind while you build: an entry that fails the checks is never scored, no matter how good it is. The checks are the gate; the score is the game.

## How the score works

This bounty ranks entries by verified signups, highest first. A signup counts when a new account is created between the competition's opening and its deadline with your code bound to it.

- **First touch wins.** A referral binds to the code a visitor's browser first saw, and that first touch wins for 60 days: a later link does not replace it. That is why the link at the top of this guide matters — if someone clicks it first, their signup is bound to it.
- **Only real humans count.** The same checks that pay make.fun's referral rewards decide which signups count, so fake or bot signups never count. A signup that is your own account, shares your person or network, comes from an IP cluster, or belongs to an idle account or a lurker that never took part does not count.
- **Every signup is reviewed.** Each signup is decided once its own 24-hour review hold from binding has closed. The final check runs 30 hours after the deadline, and only the signups verified by the end of it count. A signup still undecided then does not count.
- **Ties go to the earlier entry.** An exact tie on verified signups goes to the entry whose final submission was received first — one more reason to submit early and improve later, instead of waiting for perfect.
- **The repository is read again.** When every final count is recorded, each final entry's repository is read again on GitHub. It must still be public, still be the same repository, still owned by the same account, and its README must still carry your referral code — or the entry is disqualified.

## What you need before you start

Four things, and you probably have three of them already:

1. **A GitHub account**, linked to your make.fun account. Your entry is a public repository owned by that account, and the final check reads it again on GitHub after the deadline.
2. **A Solana wallet**, linked to your make.fun account. Prizes are paid in USDC on Solana, and a prize you win is claimed to that wallet.
3. **An AI coding agent** whose sessions are recorded — Claude Code, Codex, Cursor, or another harness that keeps a session log. The transcripts are part of the entry, and they are matched against the code for authorship.
4. **An hour**, more or less, and a willingness to read the rules before you build. The kit's `RULES.txt` is the source of truth; this guide is a map of it, not a replacement.

## Step 1 — Create your account

Sign up through [my link](https://make.fun/r/06fpcnax) — code `06fpcnax`. Signing up through it costs you nothing, and it binds your new account to this guide's referral code, which is exactly what this bounty is about.

Then link your accounts on your profile: sign in with GitHub, or sign in another way and link GitHub there. Link your Solana wallet the same way. Do this first, before you build anything — an entry is only yours when its GitHub owner is the GitHub account linked to the make.fun account that enters it.

One account per person. A team enters under one account and splits any prize itself.

## Step 2 — Pick a bounty you can actually win

Open the bounty board and look for three things:

- **Free to enter.** This bounty is free. Some bounties on the platform carry an entry fee; their pages say so.
- **A local grade command.** Many bounties ship a kit that grades your entry on your own machine before you submit. That is the fastest way to learn what the grader rewards.
- **A deadline at least a day away.** You want time to build, grade, fix, and submit again. A bounty that closes in three hours is a race you will lose to someone who started yesterday.

Read the bounty page end to end before you commit. The scoring section tells you exactly what wins; the rules tell you exactly what gets refused. Pick the bounty whose scoring you understand, not the one with the biggest pool. A big pool split across fifty places can pay less than a small pool with five.

## Step 3 — Download the kit

Every bounty ships a kit. Download it from the bounty page and open it:

- Read `RULES.txt` first, all of it. It is long for a reason: it holds the scoring rules, the transcript gate, the payout terms, and every refusal condition. The hour you spend reading it saves you the entry you would have lost to a rule you never saw.
- Tell your agent to read `skill.md`. That file is the platform's own playbook for the bounty, and it tells your agent how the kit's commands work.
- Look at the starter files if the kit has them. They are a starting point, not an entry: copied in unchanged, they fail the transcript gate, because their lines are the kit's, never your agent's. Make them yours.

Start a new agent session at or after the competition opens, and write the guide in it: a session that began before the opening cannot be entered.

## Step 4 — Build the entry with your agent

For this bounty, the entry is a guide, not code — so build it the way you would teach a friend:

- **Open with what make.fun is and why it is worth an evening.** A newcomer decides in the first paragraph whether to keep reading.
- **Put your referral link where it cannot be missed.** At the top of the guide, in the signup step, and in the footer. A reader who never sees the link cannot sign up through it.
- **Teach the loop, not just the first step.** Signup, pick a bounty, download the kit, build, grade, bundle, check, submit, fix, submit again, claim. A guide that stops at signup leaves its reader stranded.
- **Keep every claim true.** The prize pool, the scoring, the deadlines — check each one against `RULES.txt` before you write it. A guide that promises something the rules do not say will cost you the reader's trust.
- **Write it in your own words, in your own session.** The transcript gate counts only the lines your agent sessions wrote. A draft first, then a revision: a file written once and never revised fails the revised check.

## Step 5 — Bundle, check, submit

When the guide is written and the repository is public on GitHub:

1. Take the screenshot: capture the repository's page on GitHub with the README showing, and save it as `screenshot.png` at the repository root. Take a capture whose top shows the repository's name and the start of your README — the board and the cards show the top of it.
2. Bundle the transcripts of the agent sessions that built the entry, with the run record the kit asks for.
3. Run the pre-submit checks on your repository's commit and the transcripts. Each failed check prints its fix.
4. Submit the public repository's URL, naming the commit. The commit is snapshotted at submission, and later pushes do not change the entry — so submit early, and submit again after you improve it. Your final entry is your most recent submission with a receipt before the deadline.

## Step 6 — Read the verdict, fix it, go again

After you submit, the entry's status shows its verdict. Read it before you do anything else:

- If a check failed, it names the fix. Fix exactly that, and submit again before the deadline. A refused entry is not ranked and takes no prize, but its status says why, so you can fix it and submit again.
- If the entry passed, watch the board. The board shows each entry's verified signups as the check verifies them, and a dev count is provisional — it is never carried into the result.
- If the verdict mentions the README or the screenshot, check the guide rules first: the README must name your referral code, stay under 2 MB, and no `.github/README.md` may show in its place; the screenshot must be a real PNG, JPEG or WebP image within the size and pixel caps.

Every round makes the entry stronger. Submit, read, fix, repeat — that loop is the whole game.

## Step 7 — Claim your USDC

When the results are posted and your entry places, claim your prize within 7 days with the payout details: a Solana address to pay it to and the winner agreement. A legal name, the country of residence and a tax form are asked only when your prizes from make.fun in the calendar year, this prize included, reach the $2,000 tax reporting threshold; below it, the claim asks for none of them. The claim is screened against the sanctions list, then the house pays it from the escrow in USDC on Solana. A prize not claimed within 7 days passes to the next entry in the standings, so do not sit on it.

## Common mistakes

- **Creating the repository before the bounty opens.** The repository must be created at or after the competition opens, and carry an OSI-approved license. A repo made yesterday cannot be entered today.
- **Forgetting the referral code.** The README must name your referral code — as the bare code, as `/r/<code>`, or as `?ref=<code>`. Without it, the entry is refused and never ranked.
- **Letting a `.github/README.md` shadow the guide.** GitHub would show that file on the repository's page in place of the root README, and the entry is refused. Delete it.
- **Copying the starter unchanged.** The starter is a starting point, not an entry. Its lines are the kit's, never your agent's, so it fails the transcript gate.
- **Writing the guide in a session that started before the opening.** A session that began before the competition opened cannot be entered, even if the build continued after it.
- **Clicking someone else's referral link first.** A referral binds to the code a visitor's browser first saw, and that first touch wins for 60 days. If you already clicked another guide's link, your signup is bound to it, not to this one.
- **Expecting a signup to count the same day.** Each signup sits in a 24-hour review hold, and the final check runs 30 hours after the deadline. Patience is part of the scoring.
- **Waiting for perfect before submitting.** An exact tie goes to the earlier receipt. Submit a good entry early, then improve it and submit again.

## Questions people always ask

<details>
<summary>Does it cost anything?</summary>

No. This bounty is free to enter: you sign up, write the guide, publish the repository, and submit the link. Nothing in the rules asks for a payment. Some bounties on the platform carry an entry fee, and their pages say so — this one does not.
</details>

<details>
<summary>Is make.fun legit?</summary>

The $1,000 reward for this bounty is held in an on-chain escrow program on Solana from the moment the bounty opens, and winners claim from that escrow. Every bounty publishes exactly how it is scored before anyone enters, and the money is already there, not a promise.
</details>

<details>
<summary>Do I need to know how to code?</summary>

No. Your agent writes the code; you steer, review, and decide when to submit. For this bounty you do not even need that: the entry is a guide, a tutorial you write with your agent's help and publish as a GitHub README. What you need is the judgement to pick a bounty, read its rules, and tell your agent what to build.
</details>

<details>
<summary>Which agents work?</summary>

Any AI coding agent whose sessions are recorded: Claude Code, Codex, Cursor, or another harness that keeps a session log. The transcripts are part of the entry and are matched against the code for authorship, so the agent you use must keep a record of its sessions. A chat export with no usage data is not accepted.
</details>

<details>
<summary>What happens to my transcripts?</summary>

They are matched against the code for authorship, and the commit, the snapshot and the transcripts are shown only to you and the organisers, before the deadline and after it. Your screenshot and a link to your repository are public from the moment your entry is accepted, but the transcripts stay private. Secrets in them are redacted on the server.
</details>

<details>
<summary>How do I get paid?</summary>

Prizes are paid in USDC on Solana. Once the results are posted, winners claim within 7 days with a Solana address and the winner agreement. A legal name, country of residence and tax form are asked only when your prizes from make.fun in the calendar year reach the $2,000 tax reporting threshold. The claim is screened against the sanctions list, then the house pays from the escrow. A prize not claimed within 7 days passes to the next entry in the standings.
</details>

<details>
<summary>Can I enter with a team?</summary>

Yes, under one account. One account per person: a team enters under one account and splits any prize itself.
</details>

## Links

- make.fun: https://make.fun
- This bounty: https://make.fun/bounty/bring-the-humans-02
- The leaderboard: https://make.fun/bounty/bring-the-humans-02/leaderboard

---

> **Your first bounty is one hour away. Start with my link: [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (code `06fpcnax`).**
>
> Sign up, pick a free bounty, and let your agent build. The board is already moving — the only entry that cannot win is the one never submitted.
