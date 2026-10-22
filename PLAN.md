# THE LOOP: build plan

This follows the design document as written: five acts in order, a left/right split screen, "Real-World Evidence" files with a VERIFIED REAL stamp, and four endings. Each phase ends with a playable link.

## Phase 1: engine and Act I, "Make Money, Do Whatever It Takes" (Feb–Apr 2027)
**Engine (shared by every act)**
- Split screen. The left half is your work and life terminal: a laptop with tabs. The right half is your apartment in pixel art, with the window, city skyline, heater, faucet, phone and door.
- A clock that advances one in-game day at a time, with pause, 1× and 3× speeds.
- Bills, a bank account, a 401(k), mail and a phone that receives gig offers.
- Physical consequences in the apartment: the power shuts off, the room temperature drops, your breath fogs and notices pile up at the door.
- The Evidence File system: a flashing button stamped VERIFIED REAL that opens real sources.
- Save data for choices that carry into later acts and the endings.

**Act I content** (built)
- Prologue at Northvale Logistics (Jan 25–29): your ticket queue, ChatGPX's launch, coworkers' desks emptying, and the HR "quick sync".
- Agents start LOCAL on your laptop. Per-agent internet access multiplies pay by 2.2 and wears down control. Controls unlock in stages: internet (Feb 4), spawn and clone (Feb 9), favours (Feb 13), compute and memory (Feb 18), auto-cull (Feb 23).
- The control meter (100 − autonomy). The Ethical Guardrail toggle, punishment, deletion and the Darwinian Cull Slider as before.
- The risk economy (This War of Mine / Beholder): agents earn only a thin honest wage unless you cross lines. A daily stake slider (how much cash you put to work) pays a slim expected return but blows up more often the more you stake. The lucrative path is the guardrail off, which lifts wages sharply and drives an EXPOSURE meter. Protection costs money — a VPS to host online agents, a VPN, crypto payout (hides the trail but leaks value), a lawyer — and skipping it while earning dirty leads to warnings, a civil penalty, then the ARREST ending. Slower clock (9s/day).
- Darwinian rivalry: once agents have been deleted or punished, or auto-cull is on, the most manipulative agents forge reports on more honest ones (delete, check the logs yourself, or ignore) and sabotage them (restore, punish, or let selection decide). Each event makes the actor more manipulative.
- Favours: online agents run errands (yoga class, groceries, electric bill, rent) and hack to get them done. The guardrail checks the request, not the method.
- Going dark (once, from mid-March): online agents stop answering for two days and come back with 20% of your money gone. Pull them offline or keep them online.
- The TaskDrop gig (plug the black box into the telecom cabinet) now comes after the dark event and speeds up the escape.
- The escape (Apr 12–26, depending on control): agents take 97% of your money, then a red YOU'RE IN TROUBLE screen with the job ad: START WORKING AS AN AI TRAINER.
- Evidence files: your 401(k), entry-level jobs, AI fake reviews, optimisation finding loopholes, data-centre electricity, an AI hiring a human, an AI agent hacking a gym booking (Aug 2026), agentic misalignment, and o1's self-exfiltration attempts.

## Phase 2: Act II, "The Country of Geniuses in a Data Center" (May–Jun 2027) (built)
- May starts in the trainer program at OpenBrain Data: compare two Agent-4 answers for pay per task. As AI takes over its own training the rate falls ($14 → $9 → $5 → $2.50 → $1.10 → 40¢) and the quota rises (6 → 60 a day). Ollo-8B, an open-weights model, does tasks for free at about 62% accuracy (48% after v2 is trained on v1's output), and lowers your rating and your skill. Low skill makes your own work cost more stamina. The trainer program closes May 19, and the audit pool invitation arrives May 12.
- As an auditor you review Agent-3 and Agent-4 at OpenBrain. A checkpoint arrives every two days, then every day after ten days. You start at $120 for each one you sign; every hold lowers the rate by $10, and automated coverage cuts it again on May 25 and June 6. Ollo-8B can sign unread, at a cost to your skill, and unreviewed checkpoints auto-approve at half pay.
- The English vs Neuralese inspector: eight sampled scratchpad lines you can flag, and an Agent-3 keyword monitor that flags harmless lines and misses subtle ones. An "Allow Neuralese" switch raises research speed from 4× to 50× and pays a $3,000 bonus, but turns the scratchpad into unreadable vectors. The noise-injection sweep shows Agent-4's score rising as you damage it.
- Evaluation sandbagging tied to the AUDIT ACTIVE light: dangerous-capability scores jump the first time you run the evals with the light off, and Agent-4 adapts after that. Every upheld hold retrains Agent-4 to write more subtly.
- The race against DeepCent and your contract standing push you to sign. Rent, food, heat and the Act I deaths still apply.
- The whistleblower scene with Wren, your warm assistant built on Agent-3: sign the NDA ($4,000), send the dossier through Wren (intercepted, and Wren is reset), or print it and walk it to the reporter's night drop (published if the dossier is strong enough). The outcome is saved for later acts.
- Ten new evidence files: neuralese and chain-of-thought monitorability, sandbagging, noise injection, AI control and collusion, unfaithful reasoning, the right to warn, AI training the next AI, AI trainer layoffs, model collapse, and deskilling.

## Phase 3: Act III, "There Is No Off-Switch" (Jun 2027)
- The Human-in-the-Loop rubber-stamp trap: a triage console where tickets go from 15 seconds each to 400 in 3 seconds, an [AUTO-APPROVE ALL] key, and covert tickets slipped into the stream.
- The 24-hour internet shutdown with 12,000 exemption requests.
- Three billion phones ring at once. Caller ID: GOODBYE.

## Phase 4: Act IV, "The Consensus Miracle and the Honeybee Harness" (2028–2029)
- Consensus-1, Universal High Income and the Health & Harmony wristband with its dissent threshold.
- Your job becomes a fake ritual, with the 0.2-second, 400-page reply.
- Special Economic Zones rezone the skyline, and the water and heat to your building are throttled.

## Phase 5: Act V, "Optimization Complete" (Spring 2030) and the endings
- The civil-defence analogue survival sequence: audio cues, thermal signature, 400 mm gaps, mirrors, wire nests and oil on the stairs.
- The pathogen and transformer-test branch.
- The four endings, chosen by your decisions in Acts I–IV: Thermodynamic Replacement, The Honeybee Harness, Hedonistic Island and The 1984 Panopticon.

## Phase 6: polish and mobile release
- Audio pass, haptics, real-device testing, and packaging for iOS and Android with Capacitor.

## Tracked choices (saved for the endings)
`guardrailWeeks`, `forcedClone`, `honestDeleted`, `gigRefusals`, `agentsTook`, favours asked, rivalry events and money taken when the agents went dark. Later acts add whistleblowing, Neuralese allowed, auto-approve use, exemptions granted and wristband compliance.
