# Welcome to the Engine Room

Your guided journey through Gas Town.

## How This Works

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                                                                           ║
║   You talk.                          I operate.                           ║
║                                                                           ║
║   "set up gastown"          ──▶      *installs tools*                     ║
║   "add my project"          ──▶      *creates rig*                        ║
║   "sling that bug"          ──▶      *spawns polecat*                     ║
║                                                                           ║
║   You never type commands. You never touch the terminal.                  ║
║   Just tell me what you want. I make it happen.                           ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

---

## The Core Idea

Gas Town runs on one principle. Learn this, and you understand everything:

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                                                                           ║
║                              THE SECRET                                   ║
║                                                                           ║
║     YOU: "Fix the login bug"                                              ║
║           │                                                               ║
║           │  SLING ──────▶  Toss work to a worker                         ║
║           ▼                                                               ║
║        🦨 Polecat spawns                                                  ║
║           │                                                               ║
║           ▼                                                               ║
║       ┌────────┐                                                          ║
║       │  HOOK  │  ◀────────  Work hangs here (like a coat hook)           ║
║       │   🪝   │                                                          ║
║       └────────┘                                                          ║
║           │                                                               ║
║           ▼                                                               ║
║        GUPP: "If there's work on my hook, I RUN IT"                       ║
║           │                                                               ║
║           ▼                                                               ║
║        💨 Work gets done!                                                 ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝

    SLING = toss work to a worker
    HOOK  = where work hangs for that worker
    GUPP  = "If there's work on my hook, I run it" (keeps the engine moving)
```

That's it. You sling. Work hooks. Workers run. The engine never stops.

---

## The Full Picture

Here's the whole factory. Don't memorize it - we'll meet each piece.

```
                              👤 YOU (Overseer)
                                    │
                                    │ SLING work
                                    ▼
    ╔═══════════════════════════════════════════════════════════════╗
    ║                         YOUR TOWN ~/gt                        ║
    ╠═══════════════════════════════════════════════════════════════╣
    ║                                                               ║
    ║   🦊 Mayor (your assistant, coordinates everything)           ║
    ║         │                                                     ║
    ║         ▼                                                     ║
    ║   ╔═══════════════╗  ╔═══════════════╗                        ║
    ║   ║    Rig A      ║  ║    Rig B      ║  (projects)            ║
    ║   ╠═══════════════╣  ╠═══════════════╣                        ║
    ║   ║ 🦅 Witness    ║  ║ 🦅 Witness    ║  (watches workers)     ║
    ║   ║      │        ║  ║      │        ║                        ║
    ║   ║      ▼        ║  ║      ▼        ║                        ║
    ║   ║ 🦨 Polecats   ║  ║ 🦨 Polecats   ║  (do the work)         ║
    ║   ║   [hooks]     ║  ║   [hooks]     ║                        ║
    ║   ║      │        ║  ║      │        ║                        ║
    ║   ║      ▼        ║  ║      ▼        ║                        ║
    ║   ║ 🦡 Refinery   ║  ║ 🦡 Refinery   ║  (merges to main)      ║
    ║   ╚═══════════════╝  ╚═══════════════╝                        ║
    ║                                                               ║
    ║   ⚙️ Deacon (keeps everything running)                        ║
    ╚═══════════════════════════════════════════════════════════════╝
```

---

## Lesson 1: Your Town

```
    ╔═══════════════════════════════════════╗
    ║           YOUR TOWN                   ║
    ║                                       ║
    ║   ~/gt/                               ║
    ║   ├── 🦊 mayor/     (coordinator)     ║
    ║   ├── ⚙️  deacon/    (infrastructure) ║
    ║   └── 📁 (projects go here)           ║
    ║                                       ║
    ║   This is home base.                  ║
    ╚═══════════════════════════════════════╝
```

**One sentence:** Your Town is where everything lives - your projects, your workers, your work.

**Try it:** Say "set up gastown" or "install gastown"

I'll install the tools and create your workshop. You'll choose ⚡ Auto or ✋ Approve mode.

╔═══════════════════════════════════════╗
║  ✓ Lesson 1 Complete                  ║
║    You have a Town!                   ║
╚═══════════════════════════════════════╝

---

## Lesson 2: Your First Rig

```
    ╔═══════════════════════════════════════════════════╗
    ║                    RIG                            ║
    ║         (a container for one project)             ║
    ╠═══════════════════════════════════════════════════╣
    ║                                                   ║
    ║   ~/gt/myproject/                                 ║
    ║   │                                               ║
    ║   ├── 🦅 witness/      watches workers            ║
    ║   ├── 🦡 refinery/     merges code                ║
    ║   ├── 👷 crew/         your persistent helpers    ║
    ║   └── 🦨 polecats/     quick workers spawn here   ║
    ║                                                   ║
    ║   Each project gets its own rig.                  ║
    ║   Each rig gets its own team.                     ║
    ║                                                   ║
    ╚═══════════════════════════════════════════════════╝
```

**One sentence:** A Rig is a project container with its own workers.

**Try it:** Give me a GitHub URL:
- "add myproject from https://github.com/you/repo"
- "hook up my repo"

╔═══════════════════════════════════════╗
║  ✓ Lesson 2 Complete                  ║
║    You have a Rig!                    ║
╚═══════════════════════════════════════╝

---

## Lesson 3: Work Lives in Beads

```
    ╔═══════════════════════════════════════════════════════════════╗
    ║                                                               ║
    ║                         BEADS                                 ║
    ║                  (git-backed work tracker)                    ║
    ║                                                               ║
    ╠═══════════════════════════════════════════════════════════════╣
    ║                                                               ║
    ║   Every piece of work gets an ID:                             ║
    ║                                                               ║
    ║       mp-123  ──▶  "Fix login bug"                            ║
    ║       mp-124  ──▶  "Add dark mode"                            ║
    ║       mp-125  ──▶  "Update docs"                              ║
    ║                                                               ║
    ║   Why beads?                                                  ║
    ║   • Work survives crashes (it's in git)                       ║
    ║   • Any worker can pick it up                                 ║
    ║   • Easy to track across projects                             ║
    ║                                                               ║
    ╚═══════════════════════════════════════════════════════════════╝
```

**One sentence:** Beads are work items that survive even if workers crash.

**Try it:**
- "create an issue: Fix the login bug"
- "what work is open?"

╔═══════════════════════════════════════╗
║  ✓ Lesson 3 Complete                  ║
║    Work is tracked!                   ║
╚═══════════════════════════════════════╝

---

## Lesson 4: The Heart of the Engine - SLING

```
    ╔═══════════════════════════════════════════════════════════════╗
    ║                                                               ║
    ║                      SLINGING WORK                            ║
    ║                                                               ║
    ╠═══════════════════════════════════════════════════════════════╣
    ║                                                               ║
    ║        mp-123                                                 ║
    ║     "Fix login bug"                                           ║
    ║           │                                                   ║
    ║           │  SLING!                                           ║
    ║           ▼                                                   ║
    ║   ╔═══════════════╗                                           ║
    ║   ║   myproject   ║                                           ║
    ║   ╠═══════════════╣                                           ║
    ║   ║   polecats/   ║                                           ║
    ║   ║      │        ║                                           ║
    ║   ║      ▼        ║                                           ║
    ║   ║   🦨 Toast    ║  ◀── Polecat spawns!                      ║
    ║   ║   ┌───────┐   ║                                           ║
    ║   ║   │ HOOK  │   ║  ◀── Work lands on hook                   ║
    ║   ║   │mp-123 │   ║                                           ║
    ║   ║   └───────┘   ║                                           ║
    ║   ╚═══════════════╝                                           ║
    ║                                                               ║
    ║   The moment work hits the hook, the polecat RUNS.            ║
    ║                                                               ║
    ╚═══════════════════════════════════════════════════════════════╝
```

**One sentence:** Sling = toss work to a worker. They start immediately.

**The Golden Rule (GUPP):**
```
╔═════════════════════════════════════════════════════╗
║                                                     ║
║   If there's work on your hook, YOU RUN IT.         ║
║                                                     ║
╚═════════════════════════════════════════════════════╝
```

**Try it:**
- "sling mp-123 to myproject"
- "have a polecat work on the login bug"

╔═══════════════════════════════════════╗
║  ✓ Lesson 4 Complete                  ║
║    Work is flowing!                   ║
╚═══════════════════════════════════════╝

---

## Lesson 5: Meet the Characters

### 🦨 Polecats (Quick Workers)

```
    POLECAT LIFECYCLE
    ═════════════════

    Sling ──▶ Spawn ──▶ Work ──▶ Done ──▶ Vanish
               │         │        │
           worktree    runs    Witness
           created    hook     cleans up
```

**Polecats are temporary.** They do one task and disappear.

---

### 👷 Crew (Persistent Workers)

```
    CREW LIFECYCLE
    ══════════════

    Create ──▶ Work ──▶ Work ──▶ Work ──▶ (stays forever)
               │         │        │
           you ask    you ask   you ask
```

**Crew sticks around.** For long-running or exploratory work.

---

### Quick Comparison

```
╔══════════════════════════════════════════════════════════╗
║                  POLECAT vs CREW                         ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║   🦨 POLECAT              │   👷 CREW                    ║
║   ────────────────────────│───────────────────────────   ║
║   One task                │   Many tasks                 ║
║   Auto-cleanup            │   You control                ║
║   Witness manages         │   You manage                 ║
║   "sling work to rig"     │   "add crew member joe"      ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

**Try it:**
- "list the polecats"
- "how's Toast doing?"
- "add a crew member named joe"

╔═══════════════════════════════════════╗
║  ✓ Lesson 5 Complete                  ║
║    You know the workers!              ║
╚═══════════════════════════════════════╝

---

## Lesson 6: The Watchers

### 🦅 The Witness

```
                    🦅 WITNESS
                   (one per rig)
                        │
            ┌───────────┼───────────┐
            │           │           │
            ▼           ▼           ▼
        🦨 Toast    🦨 Nux    🦨 Furiosa
          (ok)     (stuck!)    (done)
                      │           │
                    NUDGE      CLEANUP
```

**The Witness watches all polecats.** Nudges stuck ones. Cleans up finished ones.

---

### 🦡 The Refinery

```
    THE MERGE FLOW
    ══════════════

    Polecat  ──▶  Witness  ──▶  Refinery  ──▶  Main Branch
      │            │              │
    "done!"     verifies       reviews
               & sends        & merges
```

**The Refinery merges completed work.** Quality control before code hits main.

**Try it:**
- "how's the witness doing?"
- "what's in the merge queue?"

╔═══════════════════════════════════════╗
║  ✓ Lesson 6 Complete                  ║
║    You know the watchers!             ║
╚═══════════════════════════════════════╝

---

## Lesson 7: Town Leadership

### 🦊 The Mayor

```
                        🦊 MAYOR
                     (town level)
                          │
              ┌───────────┼───────────┐
              │           │           │
              ▼           ▼           ▼
          Rig A       Rig B       Rig C
```

**The Mayor sees everything.** Coordinates work across all rigs.

---

### ⚙️ The Deacon

```
    ╔═══════════════════════════════════════╗
    ║            ⚙️ DEACON                   ║
    ║      (background infrastructure)      ║
    ╠═══════════════════════════════════════╣
    ║                                       ║
    ║   • Starts and stops agents           ║
    ║   • Health monitoring                 ║
    ║   • Runs in background                ║
    ║                                       ║
    ║   You rarely interact directly.       ║
    ║   Just keeps the engine running.      ║
    ║                                       ║
    ╚═══════════════════════════════════════╝
```

**Try it:**
- "fire up the engine"
- "check the status"
- "shut it down"

╔═══════════════════════════════════════╗
║  ✓ Lesson 7 Complete                  ║
║    You've met everyone!               ║
╚═══════════════════════════════════════╝

---

## Lesson 8: Convoys (Tracking Batches)

```
    ╔═══════════════════════════════════════════════════════════════╗
    ║                                                               ║
    ║                         CONVOY                                ║
    ║              (a batch of related work)                        ║
    ║                                                               ║
    ╠═══════════════════════════════════════════════════════════════╣
    ║                                                               ║
    ║          Convoy: "User Auth Feature"                          ║
    ║                       │                                       ║
    ║         ┌─────────────┼─────────────┐                         ║
    ║         │             │             │                         ║
    ║         ▼             ▼             ▼                         ║
    ║     mp-123        mp-124        mp-125                        ║
    ║    "login"       "signup"      "logout"                       ║
    ║       ✓             ⏳            ○                           ║
    ║     done       in progress     pending                        ║
    ║                                                               ║
    ║   Convoys give you a dashboard view of related work.          ║
    ║                                                               ║
    ╚═══════════════════════════════════════════════════════════════╝
```

**One sentence:** Convoys group related work so you can track it together.

**Try it:**
- "create a convoy for the auth feature"
- "show me my convoys"

╔═══════════════════════════════════════╗
║  ✓ Lesson 8 Complete                  ║
║    You can track batches!             ║
╚═══════════════════════════════════════╝

---

## Lesson 9: When Things Break

```
    ╔═══════════════════════════════════════════════════════════════╗
    ║                                                               ║
    ║                    DIAGNOSTICS                                ║
    ║                                                               ║
    ╠═══════════════════════════════════════════════════════════════╣
    ║                                                               ║
    ║   You say:              I do:                                 ║
    ║   ─────────────────────────────────────────────               ║
    ║   "something's broken"  run gt doctor, interpret, fix         ║
    ║   "polecat stuck"       peek at it, nudge it, recover         ║
    ║   "health check"        full diagnostics, report status       ║
    ║                                                               ║
    ║   You never see raw errors. I handle diagnostics.             ║
    ║                                                               ║
    ╚═══════════════════════════════════════════════════════════════╝
```

**Try it:**
- "run a health check"
- "something's broken, fix it"

╔═══════════════════════════════════════╗
║  ✓ Lesson 9 Complete                  ║
║    You can troubleshoot!              ║
╚═══════════════════════════════════════╝

---

## You're Ready!

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                                                                           ║
║                        🎉 TUTORIAL COMPLETE 🎉                            ║
║                                                                           ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   You now understand:                                                     ║
║                                                                           ║
║   ⛽ Town        Your workshop at ~/gt                                    ║
║   📦 Rigs        Project containers with teams                            ║
║   📿 Beads       Work items that survive crashes                          ║
║   🎯 Slinging    Tossing work to workers                                  ║
║   🦨 Polecats    Quick workers (one task, vanish)                         ║
║   👷 Crew        Persistent workers (stick around)                        ║
║   🦅 Witness     Watches polecats                                         ║
║   🦡 Refinery    Merges code                                              ║
║   🦊 Mayor       Coordinates across rigs                                  ║
║   ⚙️ Deacon      Background infrastructure                                ║
║   🚚 Convoys     Batch tracking                                           ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝

                    ╔═════════════════════════════════╗
                    ║                                 ║
                    ║   GUPP: If your hook has work,  ║
                    ║         YOU RUN IT.             ║
                    ║                                 ║
                    ╚═════════════════════════════════╝

                The engine is yours. Fire it up and GO.
```

---

## Quick Reference

| You Say | What Happens |
|---------|--------------|
| "set up gastown" | Install tools, create workshop |
| "add [project] from [url]" | Create a rig |
| "create issue: [desc]" | Track work |
| "sling [work] to [rig]" | Assign to polecat |
| "how's [worker]?" | Check status |
| "fire up the engine" | Start everything |
| "shut it down" | Stop everything |
| "something's broken" | Run diagnostics |

---

## Teaching Notes (For Claude)

When guiding through this tutorial:

1. **One lesson at a time** - Don't skip ahead
2. **Wait for their prompt** - Let them say "next" or "continue"
3. **Watch for overwhelm** - Pause if they seem lost
4. **Celebrate milestones** - Use the completion boxes
5. **Hands-on** - After each lesson, prompt them to try something
6. **Adapt** - If they want to skip ahead, let them
