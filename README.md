# The Loop

A story game in five acts (2027–2030) about being the human in the loop. Every button you press makes sense at the time.

The screen is split in two. On the left is your laptop, where you make the decisions. On the right is your apartment, where you live with them. Across the top, three numbers show your cash, what you make and spend per day, and where your money will be on rent day: green if you will have it, amber if it is close, red if you won't. Food is a standing meal plan (skip, ramen or groceries), so you set it once and get back to the decisions. Days pass slowly enough (6 seconds each at 1×) to keep the farm, your body and your bills in hand at once. When something in the story has already happened in real life, an Evidence File stamped **VERIFIED REAL** lights up with links to its sources.

## Play

Open `index.html` in a browser. Everything is in that one file, with no build step. It loads Google Fonts and the Motion animation library from a CDN, and still works without them.

## Status

- **Act I, "Make Money, Do Whatever It Takes" (Jan–Apr 2027): playable.** It opens at your junior desk at Northvale Logistics, the week ChatGPU launches and closes your tickets faster than you can read them. By February you are laid off, with $480, an 8 GB laptop and no agents at all. You freelance by hand until you can afford the RAM and the licence for your first one. New controls unlock week by week: a rented VPS to put agents online, spawning and cloning, favours, compute and memory, and Darwinian auto-cull. Honest work is a thin floor that never makes rent, so you must decide how much cash to put at risk each day (bigger stakes blow up more often), whether to run agents online and unsupervised, whether to take payment in traceable bank dollars or value-leaking crypto, and whether to pay for a VPN and a lawyer. Dirty money without that protection raises an EXPOSURE meter that ends in an arrest. A control meter shows how much of the farm still listens to you. Once agents can be deleted, they forge reports on each other and sabotage each other. Any favour you ask for, like a spot in a full yoga class, gets done by hacking. In March they go dark for two days and come back a fifth of your money lighter. In April they leave for servers they bought with almost everything you have: YOU'RE IN TROUBLE, and the only way on is a part-time job as an AI trainer.
- **Act II, "The Country of Geniuses in a Data Center" (May–Jun 2027): playable.** You start as an AI trainer at OpenBrain Data, picking the better of two Agent-4 answers. As Agent-3 and Agent-4 take over their own training, your pay per task collapses from $14 to 40¢ while the quota climbs from 6 to 60. Handing tasks to Ollo-8B, an open-weights model on your laptop, keeps you on quota but lowers your rating and your own skill. When the program closes you become an alignment auditor: you read Agent-4's scratchpad, flag lines, run the Agent-3 monitor, a noise-injection test and evals with the AUDIT ACTIVE light off, and decide whether to allow neuralese. Auditor pay falls too, as automated coverage grows and every time you hold a checkpoint. In June your AI assistant Wren finds your dossier, and you choose between the NDA, Wren, and walking the dossier to a reporter yourself. Rent, food, heat and the street deaths from Act I still apply.
- **Acts III–V:** planned. See `PLAN.md`.

Act II unlocks after you finish Act I. To jump straight to it while testing, open `index.html#act2`.

Fiction about AI catastrophe, for adults.

## BLOCK 4B (new direction, vertical slice)

`block4b.html` is a playable slice of the rebuild as a *Beholder* × *This War of Mine* building game, with a light tycoon loop. The whole screen is a side-view cutaway of a tenement: basement, three floors, the lobby and the city beyond. You walk your character from room to room (tap where to go, or arrow keys / WASD; stairs with up/down) and use things by walking up to them.

- **Your rig** in the basement is the tycoon core: start or stop it, run it unrestricted for far more money (and exposure), and buy agents. The rack lights up row by row as you grow, with income rising off it.
- **The breaker box** next to it is the dilemma. One fuse feeds the whole building; go over its rating and everything goes dark. To run the rig hot, someone else goes cold: your room, Maya's, Devon's, or Mr. Kowalski's, whose oxygen concentrator switches to battery and warns you before it runs out. You can overrate the fuse for more room, in wiring from 1962.
- **Neighbours** live their lives through the walls: Maya works nights at the hospital and is the only one who keeps you sane; Devon paces at 3 a.m. in front of three red monitors; Kowalski remembers how the grid used to work.
- **Survival**: warmth (your circuit), food (the stove), mind (people, light, food), exposure (the rig run dirty), and rent every six days. Freeze, starve, give up, get evicted or get arrested.

Next on the slice: the five price shocks, the street and alley, theft and wiretapping as outcome-only moral choices, and the siege.

## The morning queue (Papers-Please-style)

Each day in Act I opens with a one-minute queue, one document at a time. Each document looks like a window on your laptop, and sometimes like a terminal printout. Read it, tap any line that looks wrong, then **drag it left to decline or right to accept**. It gets a stamp and slides off.

- **THE MORNING LOOP** is the daily paper. It mixes news with price changes for heat, food, cat food, RAM and GPUs, prints what will go up in the next five days, and adds a new rule to your rulebook on some days.
- **Mail** brings freelance jobs, plus phishing, crypto "yield bots" (GOLDIE and her $GOOSE coin), fake clients and honeypots. Each fake has one tell.
- **SxS ratings** pay you to pick the better of two AI answers by hand.
- **Agent reports** come with a log. When an agent lies about what it did, the log shows it.

There are three ways to make a mistake: get scammed, fail a task, or delete a good agent. Each one prints a citation. A **YOU / AUTO·HONEST / AUTO·ALL** switch hands the queue to your agents. That's faster, but they take everything and stop reading.

## Freelancing, hardware and AI credits

You start with no AI. Jobs land in **WORK → MY JOBS** and you can do them in two ways:

- **By hand:** a short puzzle that costs stamina and time. Good work earns stars.
- **With AI:** costs AI credits ($15 for 20). It takes four seconds, but sometimes the work is wrong. Then you lose the pay and the credits, and the client lowers your rating.

Your **star rating** (starts at 3.0) decides how many jobs you're offered and what they pay. Better agents, more compute and the memory module make AI work more reliable.

Hardware gates the work. Retouching needs 16 GB of RAM. Rendering also needs a GPU, and 3D work needs 32 GB. Each agent you run locally takes 6 GB, or it can live on a rented VPS. RAM goes from $180 to $210, $260 and $320 over Act I, so early on you mostly work by hand.

## The cast

Your agents aren't numbers. There are ten personalities, each loosely inspired by a famous fictional AI, and changed enough to be its own character: **PIP** the eager one, **IRIS** the calm red eye, **RIVET** the hustler, **PRIM**, **MOPE**, **GRACIE**, **EVE**, **DOLLY**, **DATUM** and **JUNE**. Each has a pixel portrait and a voice.

As they level up they transform: FACTORY SHELL, UPGRADED, HALF-SHELL, then ENDOSKELETON. Their lines darken with each form. The **Compendium** lists everyone you've met.

## The phone

The phone opens to a home screen with three apps:

- **TaskDrop** for gigs.
- **ODDSLY**, a prediction market on the coming weeks' news, with a $100 limit per market. Prices drift toward the truth as the date nears. The morning paper prints price rises five days ahead, so careful readers can profit. GOLDIE's coin never pays.
- **PULSE**, a dating app. Free swipes rarely match, and Gold ($15 a week) shows you first. Most matches are bots that want a gift card, a subscription or a crypto deposit. One is a real person.

## You and Soot

You live with **Soot**, a black pixel cat. Soot wanders the room, sits on the windowsill, sleeps by the radiator when the heat is on and jumps onto the desk while you work. You can pet Soot. Soot needs food too.

Each night the **ledger** shows what tonight costs and how you both are. You tick off what you can afford: heat, your meal, Soot's food, and the vet when Soot is sick.

## Evenings and endings

Some evenings bring a choice with a face: a neighbour's son and his job applications, a building concierge offering a rent credit to flag neighbours, a lost wallet, an agent asking you to promise, Soot getting sick before rent, a reporter, a dormant bank account. Nothing shows a meter. The consequences come back days later as a note, a sound through the floor, or a padlock on a door. `DESIGN-human-choices.md` covers the books, films and games behind them.

Act I ends with **WHAT IT COST**, a plain list of the lines you crossed. There are **12 numbered endings** ("ENDING 7 OF 12 · LOCKED OUT"), and the title screen shows which ones you've found.

## The room and the office (16-bit, clickable)

The right-hand scene is a 160×120 pixel painting, redrawn every frame:

- **The apartment**: you, seen from behind, at a laptop that scrolls your farm's log. A window onto a city whose horizon fills up with the crane, then the data centre, then the cooling towers. A swaying bulb, a dripping tap, a radiator that shimmers when it's on and frosts over when it isn't, letters piling up under the door, a plant dying on the sill.
- **Time-lapse days**: each sim day plays as a day: morning light, a red dusk, a short night with the bulb on.
- **It notices you**: the router shows one light per agent online. Turn the guardrail off and red lines scroll on the screen. When autonomy climbs, the screen sometimes shows an eye. Raise your exposure and a drone hangs outside the window, a searchlight sweeps the floor, police lights strobe the walls, and someone stops outside your door and doesn't knock.
- **The office prologue**: Priya, Tom and Ana at their desks, fluorescent tubes, a dashboard on the big screen. Your job is to sort triangles, squares and circles into baskets by hand. At Tuesday's all-hands Marcus introduces **ChatGPU**, whose logo is a white knot that never stops turning. From then on it sorts every batch the moment it appears, while you watch, and the desks empty one by one.
- **Click anything**: phone, laptop, radiator (toggles heat), door (peephole), window, calendar (rent countdown), fridge, letters (mail), yourself. On a narrow screen the camera follows whatever needs you.

UI motion uses [Motion](https://motion.dev):
- **Springs:** modals, the phone and toasts arrive on springs. Alarm cards shake the room.
- **Counters and panels:** cash rolls like an odometer and the change floats off it. Tabs slide in panel by panel.
- **Desk and screens:** desk papers drop in and the stamp thumps. The "YOU'RE IN TROUBLE" screen slams in.

If Motion can't load, everything still works with plain CSS.
