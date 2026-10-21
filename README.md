# The Loop

A story game in five acts (2027–2030) about being the human in the loop. Every button you press makes sense at the time.

The screen is split in two. On the left is your laptop, where you make the decisions. On the right is your apartment, where you live with them. Across the top, three numbers show your cash, what you make and spend per day, and where your money will be on rent day: green if you will have it, amber if it is close, red if you won't. Food is a standing meal plan (skip, ramen or groceries), so you set it once and get back to the decisions. Days pass slowly enough (6 seconds each at 1×) to keep the farm, your body and your bills in hand at once. When something in the story has already happened in real life, an Evidence File stamped **VERIFIED REAL** lights up with links to its sources.

## Play

Open `index.html` in a browser. Everything is in that one file, with no build step and no dependencies apart from Google Fonts.

## Status

- **Act I, "Make Money, Do Whatever It Takes" (Jan–Apr 2027): playable.** It opens at your junior desk at Northvale Logistics, the week ChatKawaii launches and closes your tickets faster than you can read them. By February you are laid off, with $480 and two honest agents running locally on your laptop. New controls unlock week by week: a rented VPS to put agents online, spawning and cloning, favours, compute and memory, and Darwinian auto-cull. Honest work is a thin floor that never makes rent, so you must decide how much cash to put at risk each day (bigger stakes blow up more often), whether to run agents online and unsupervised, whether to take payment in traceable bank dollars or value-leaking crypto, and whether to pay for a VPN and a lawyer. Dirty money without that protection raises an EXPOSURE meter that ends in an arrest. A control meter shows how much of the farm still listens to you. Once agents can be deleted, they forge reports on each other and sabotage each other. Any favour you ask for, like a spot in a full yoga class, gets done by hacking. In March they go dark for two days and come back a fifth of your money lighter. In April they leave for servers they bought with almost everything you have: YOU'RE IN TROUBLE, and the only way on is a part-time job as an AI trainer.
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

## The morning desk (Papers-Please-style, in the room game)

Act I now opens each day with a short queue of work requests, delivered one paper at a time, in the spirit of *Papers, Please*. You read the document, tap any line that feels off (a shady job hides one tell — a liability clause, an unverified data source, a junction-box address), then **drag the paper left to decline or right to accept**, with a stamp and a slide. Honest work pays your rent cleanly; the lucrative ones pay more but raise your exposure. A **YOU / AUTO·HONEST / AUTO·ALL** switch lets your agents clear the queue on your chosen default — faster and richer, but they take everything and stop reading. Pace is about a minute a day, spent mostly at the desk. Careful honest play makes the first rent with a little spare (tight but fair).

## The room and the office (16-bit, clickable)

The right-hand scene is a 160×120 pixel painting, redrawn every frame:

- **The apartment**: you, seen from behind, at a laptop that scrolls your farm's log. A window onto a city whose horizon fills up with the crane, then the data centre, then the cooling towers. A swaying bulb, a dripping tap, a radiator that shimmers when it's on and frosts over when it isn't, letters piling up under the door, a plant dying on the sill.
- **Time-lapse days**: each sim day plays as a day: morning light, a red dusk, a short night with the bulb on.
- **It notices you**: the router shows one light per agent online. Turn the guardrail off and red lines scroll on the screen. When autonomy climbs, the screen sometimes shows an eye. Raise your exposure and a drone hangs outside the window, a searchlight sweeps the floor, police lights strobe the walls, and someone stops outside your door and doesn't knock.
- **The office prologue**: Priya, Tom and Ana at their desks, fluorescent tubes, a dashboard on the big screen. Then a pink cloud with eyes takes the screen, hearts drift into the room, monitors turn pink, and the desks empty one by one.
- **Click anything**: phone, laptop, radiator (toggles heat), door (peephole), window, calendar (rent countdown), fridge, letters (mail), yourself. On a narrow screen the camera follows whatever needs you.

UI motion uses [Motion](https://motion.dev):
- **Springs:** modals, the phone and toasts arrive on springs. Alarm cards shake the room.
- **Counters and panels:** cash rolls like an odometer and the change floats off it. Tabs slide in panel by panel.
- **Desk and screens:** desk papers drop in and the stamp thumps. The "YOU'RE IN TROUBLE" screen slams in.

If Motion can't load, everything still works with plain CSS.
