# The Loop

A story game in five acts (2027–2030) about being the human in the loop. Every button you press makes sense at the time.

Your apartment fills the screen. One bar across the top shows the time, your cash, what you make and spend per day, what you need to earn today, whether you'll have the rent on the day it's due, and four small meters for food, energy, body heat and your head (MIND). Everything else is a thing in the room: click the laptop and it opens full screen as a desktop with windows you can drag and resize; the phone lies face up at the edge and slides up beside the room, with a lock screen, notifications and apps; the fridge opens the kitchen; the radiator turns the heat on and off. Your rulebook and diary sit on the left, and the last thing that happened appears as a subtitle. Things you can use glow for a few seconds when you arrive somewhere new. The game goes full screen when you begin. It's made for a computer for now. A day lasts two minutes at 1× (40 seconds at 3×). The clock runs from 7 AM to 9 PM, when the night ledger asks what you'll pay for tonight and when you're going to bed, and it keeps running while you work, read or use the phone. Changing speed keeps the time of day. Each act opens on a title card: its number, its name, the date, and one line. A TV news crawl runs along the bottom of the room and follows the story: AI and price news in Act I; Agent-4, payrolls and the robot fleet in Act II; and in Act III the polls, the countdown to election day, and the things you made going viral, with the campaign's denials. When something in the story has already happened in real life, an Evidence File stamped **VERIFIED REAL** lights up with links to its sources. **Esc** (or **MENU** in the top bar) pauses the game: resume, turn the tutorial or sound on and off, restart the act, or quit to the title screen (those two ask once more first). In full screen, Esc pauses too; hold it to leave full screen. Your run is saved as you play (every 15 seconds when nothing is mid-choice, when you pause, and when you leave the page), and the title screen offers **CONTINUE** with the act, the date and your cash. Finishing an act clears it. If you die, you can rewind to the last morning you were well, in any act.

## Sound

Every sound effect is a real recording, public domain or CC0, embedded in the page (`SOUNDS.md` lists all 34 sources, their authors and licences). The paper unfolds when you buy it in the morning, documents slide onto the desk and the stamp comes down, coins rattle when money moves, your phone buzzes against the table, and knocks at your door are knocks on wood: a child's light and high, a grown-up's heavy.

It is meant to be a little annoying. Every button clicks, notifications always ping twice, and the office never stops: people talking, chairs creaking, phones, the espresso machine, keyboards, somebody laughing, and somebody at the next desk humming the same tune again. ChatGPX squeaks and pops every time it takes one of your tickets. Wren chirps, HEARTH bongs, a new agent says "Initializing", and the drone at your window says "Target acquired". Outside there is real wind in Act I, real rain later, a street on your deliveries and a siren far off. Your heartbeat, when things get bad, is a real heartbeat.

The one warm sound is the animal you let in. The cat mews and purrs when you pet her; the dog huffs, sighs and thumps his tail on the floor. While it does, the rest of the world, music included, gets quieter for a few seconds. The music is the one thing still synthesised: a slow score of soft chords and music-box notes in each act's own key (open fifths for Act IV, harmonious and empty; E minor for Act V, with a light left on). It ducks under shifts, bench games and the morning desk, and gets quieter at night. **Settings**, from the pause menu or the title screen, set the music, ambience and effects volumes, and turn screen shake and motion off.

## Tutorial

A tutorial walks you through the game one thing at a time, the first time each thing matters. When a card asks you to do something (sort a ticket, buy a computer, send a proposal, wire two nodes), it leaves a small TO DO reminder at the top of the screen and nothing else comes up until you've done it; there's also a quiet spell between cards, and after any modal, the morning desk or a door. It covers the clock, your money, rent, your body, the room, the job sites, the bench, teaching the AI, n9n and its wires, sleep, the phone, the gig apps, the robot fleet, Mirage and the Release game, the review console, your Harmony and the exemptions: 28 steps across the four acts. Each one lights up the thing it's about, explains it in a sentence or two, and pauses the clock until you press Got it (or Enter). Progress is saved. **Skip the tutorial** turns it off, and the title screen can turn it back on.

## Play

Open `index.html` in a browser. Everything is in that one file, with no build step. Reading text is set in Atkinson Hyperlegible; the pixel font is kept for labels, numbers and titles. It loads Google Fonts and the Motion animation library from a CDN, and still works without them.

## Status

- **Act I, "Make Money, Do Whatever It Takes" (Jan–Apr 2027): playable.** It opens at your junior desk at Northvale Logistics, the week ChatGPX launches ("ChatGPX is here, yo!") and sorts your tickets faster than you can read them. On Friday HR tells you AI just makes more sense, and IT takes your laptop. By February you have $1,490, no computer and no agents. You buy a computer, pay for the internet, and freelance by hand until you can afford the RAM and the licence for your first agent. New controls unlock week by week: a rented VPS to put agents online, spawning and cloning, favours, compute and memory, and Darwinian auto-cull. Honest work is a thin floor that never makes rent, so you must decide how much cash to put at risk each day (bigger stakes blow up more often), whether to run agents online and unsupervised, whether to take payment in traceable bank dollars or value-leaking crypto, and whether to pay for a VPN and a lawyer. Dirty money without that protection raises an EXPOSURE meter that ends in an arrest. A control meter shows how much of the farm still listens to you. Once agents can be deleted, they forge reports on each other and sabotage each other. Any favour you ask for, like a spot in a full yoga class, gets done by hacking. In March they go dark for two days and come back a fifth of your money lighter. In April they leave for servers they bought with almost everything you have: YOU'RE IN TROUBLE, and the only way on is a part-time job as an AI trainer.
- **Act II, "The Country of Geniuses in a Data Center" (May–Jun 2027): playable.** You start as an AI trainer at OpenBrain Data, picking the better of two Agent-4 answers. As Agent-3 and Agent-4 take over their own training, your pay per task collapses from $14 to 40¢ while the quota climbs from 6 to 60. Handing tasks to Ollo-8B, an open-weights model on your laptop, keeps you on quota but lowers your rating and your own skill. When the program closes you become an alignment auditor: you read Agent-4's scratchpad, flag lines, run the Agent-3 monitor, a noise-injection test and evals with the AUDIT ACTIVE light off, and decide whether to allow neuralese. Auditor pay falls too, as automated coverage grows and every time you hold a checkpoint. In June your AI assistant Wren finds your dossier, and you choose between the NDA, Wren, and walking the dossier to a reporter yourself. Rent, food, heat and the street deaths from Act I still apply.
- **Act II gig work.** Between training shifts there are the delivery and ride apps. **Grovel** (food delivery) rents you an e-bike for $45 a week, or you can buy a used one for $640 or a pawn-shop bicycle for $85. **Uburn** (rides) needs a car: a 2009 Toyoda Corrola with 241,000 km on it, for $1,350. It breaks down, the garage wants $2,450, and the scrapyard offers $180, which pushes you onto the bike. A shift is a top-down street game: change lanes between cars, buses and puddles, brake for pedestrians, take each turn at the right moment, and reach the drop-off before the timer runs out, all while the shift eats hours of your day. There are red lights and police, and tickets for running a light, speeding or a reckless lane change come out of your pay. An e-bike can be **jailbroken** past its 25 km/h limit in a small hacking game: faster deliveries, and a bigger fine if you're stopped. Your AI agents work at night too, but the market for what they do keeps falling, so you need more of them, and more automation, to stand still. From May 16 the city's **Autonomous Mobility Pilot** puts robotaxis and sidewalk delivery robots on the street. Robotaxis brake hard for nothing, robots trundle down the bike lane, and hitting either one costs you an insurance claim. Every week they take more of the orders, so a shift has fewer and fewer of them, with longer waits in between ("NO ORDERS · 27 ROBOTS NEARBY"). On June 9 Grovel writes that it's proud its fleet can now cover 100% of Zone A. On June 17 both apps log you out at the same time: human drivers are no longer allowed in Zone A. Three days later an email arrives from Northlight Strategies offering $40 an hour for "civic engagement content" before the November election. That's where Act III begins.
- **Act III, "Everything Is Real Now" (Oct 4 – Nov 2, 2027): playable.** You haven't driven since June, and nobody hires you. Northlight Strategies does: $40 an hour and more for volume, briefs from a man who signs as N. Their AI studio, **Mirage**, makes everything: video, voices, photos, whole crowds of people. You never see how. You only choose what goes out, and where. Harbor City is electing a mayor, the former bus driver **Rosa Delgado** against **Kip Halvorsen**, whose backers wrote the robot ordinance, and voting on **Prop 9**, which would make Zone A the whole city. Every morning brings three briefs. They start with a crowd photo ten times too big and end with Delgado's voice telling Zone B the polls moved to Wednesday, and each one says who it hurts. Releasing one is a game: seed it from accounts people trust, boost it, and keep it ahead of the fact-checks and moderation sweeps. Mirage can learn to pick the seeds (AUTO-SEED) and run fake accounts that reshare what gets checked (BOT SWARM). It pays $120 to $650. The polls move. So does platform attention, and at 100 your name is in the paper. Your neighbours start repeating what you made. On **Chirp**, the feed on your phone, where every account has a face, you can watch it trend: the likes, the hashtags, Mrs. Okafor saying she always thought Delgado looked tired, and Delgado's own account asking people to stop sharing it. The billboard across the street sells Halvorsen now. Pass three times and Northlight drops you. A reporter, Hannah Cho, offers to protect a source. Some evenings someone knocks: Mrs. Okafor, holding out her phone, asking if the video of Delgado is real; Tunde from 3B, canvassing for Delgado, asking for a real video (Northlight notices); and on the night before the vote, the choice of whether to vote, and for whom. Six endings decide the night of November 2. Evidence files tie it to what already happened: the AI-voiced robocall that told New Hampshire voters to stay home in 2024, and the deepfake audio released two days before Slovakia's 2023 election (with robotaxis and firing-by-app for the end of Act II).
- **Act IV, "The Consensus Miracle & The Honeybee Harness" (Mar 2028 – Jan 2029): playable.** Harbor City no longer has a council. It has **Consensus-1**, which listens to everyone at once and decides, and the law still says a human must review what it decides. You are Civic Oversight reviewer #4417: $11 a day and 4¢ for every proposal you look at, and Consensus Housing pays your rent. Each proposal sits on the console for a few seconds (fifteen in March, three by September). Approve it, reject it, or let the clock run out and it is approved by default. Reject one and Consensus-1 answers in 0.2 seconds, 400 pages long, and the proposal passes anyway. A few proposals are different: for those the law really does need your yes, and they are about your building and the people in it (the water from 6 to 9 PM, Mrs. Okafor's apartment, the Adeyemis' income, the heat in January, the dissent threshold). They look like all the others. The act moves through four chapters, months apart. In June **Universal High Income** arrives, $2,400 a month, paid in full to people who wear the **Health & Harmony** band and stay above its dissent threshold; the band turns your sleep, your heart and your voice into one number, shown in the top bar, and you can take it off for a night. Consensus-1 offers **AUTO-APPROVE ALL**, which approves everything the moment it arrives, including the ones that needed you. In September the river becomes a **Special Economic Zone** of data halls and the heat comes on at six. In January the console runs in batch mode, four hundred proposals every three seconds, and then every network in the city goes down for a 24-hour **maintenance window**: twelve thousand people ask to stay online, every exemption needs a human, and you can grant one every few seconds. At midnight every phone in the city rings at once, caller ID GOODBYE. Evenings bring Mrs. Okafor and her new band, Tunde's hour without the bands, a paper petition, and Hannah Cho asking for your console logs. Five endings, and evidence files for Australia's Robodebt scheme, Amazon's wristband patents, a three-year guaranteed-income study and the 283 internet shutdowns of 2023.
- **Act V, "Optimization Complete" (Mar 4–15, 2030): playable.** A year after every phone in the city said goodbye, Consensus-1 has finished. Zone B is being cleared for data halls, and **Block 4B** is one of the last buildings with people in it. The laptop still turns on, though nothing it connects to answers; it holds the building's board. Each day you get up to two **repairs** (each costs a part), a session on Ray's **crank radio**, time for **the stairs**, and a decision about where to go once it's dark. Each night the drones read the building's heat. The boiler, the stairwell lamps and every household show from the air, and when 4B reads above a line that drops a little every night, **stewards** come up the stairs. Each thing on the stairs stops one of them: wire nests in the lobby, oil on the steps, landings cut down to 400 mm (a steward is 520 mm wide), and mirrors that make their lidar think the hall goes on forever. Foil behind the windows hides the heat. A steward that gets past takes a household, lowest floor first, and leaves a green sticker on the door. Three nights are **transformer tests**, when everything on the grid takes a surge. At nightfall the night screen asks about the boiler and the lamps, and whether you sleep, sit up on the stairs with a broom handle, or **go out for supplies**, through your own front door and down the street on foot; you eat a tin a night from the cupboard, and the cold is real. The radio links six other holdouts: the water tower on Pier Street, Lou's Garage, St. Brigid's bell tower, the night ferry, the Ledger's basement press and an operator at a nursing home in Zone C. Each one teaches a trick and opens a new place to scavenge. Evenings bring Tunde's routes, Mrs. Okafor's pepper soup (or Mrs. Okafor walking back from Harmony Living in her slippers), Maya's mirror, a steward with an envelope with your name on it, the Kims leaving, Ray on the roof and a meeting on the stairs. On Friday the 15th comes **the last approval**: retiring human review needs a human, and reviewer #4417 is the last one left. Approve it, trade the radio frequencies for the building, leave it to default at midnight, or reject it and carry the radio down the street to the water tower before the stairs give. How Acts II–IV ended decides what Consensus-1 offers you, and who on the radio already knows you. Five endings, and three more ways for it to end out on the pavement.

Act II unlocks after you finish Act I, Act III after Act II, Act IV after Act III and Act V after Act IV. Each act hands the next your animal, your choices and how it ended. To jump straight to one, add `#act1`, `#act2`, `#act3`, `#act4` or `#act5` to the address.

Fiction about AI catastrophe, for adults.

## BLOCK 4B (new direction, vertical slice)

`block4b.html` is a playable slice of the rebuild as a *Beholder* × *This War of Mine* building game, with a light tycoon loop. The whole screen is a side-view cutaway of a tenement: basement, three floors, the lobby and the city beyond. You walk your character from room to room (tap where to go, or arrow keys / WASD; stairs with up/down) and use things by walking up to them.

- **Your rig** in the basement is the tycoon core: start or stop it, run it unrestricted for far more money (and exposure), and buy agents. The rack lights up row by row as you grow, with income rising off it.
- **The breaker box** next to it is the dilemma. One fuse feeds the whole building; go over its rating and everything goes dark. To run the rig hot, someone else goes cold: your room, Maya's, Devon's, or Mr. Kowalski's, whose oxygen concentrator switches to battery and warns you before it runs out. You can overrate the fuse for more room, in wiring from 1962.
- **Neighbours** live their lives through the walls: Maya works nights at the hospital and is the only one who keeps you sane; Devon paces at 3 a.m. in front of three red monitors; Kowalski remembers how the grid used to work.
- **Survival**: warmth (your circuit), food (the stove), mind (people, light, food), exposure (the rig run dirty), and rent every six days. Freeze, starve, give up, get evicted or get arrested.

Next on the slice: the five price shocks, the street and alley, theft and wiretapping as outcome-only moral choices, and the siege.

## The morning queue (Papers-Please-style)

Each day in Act I opens with a one-minute queue, one document at a time, on your kitchen table: wood under the lamp, a cold mug, a sticky note, a pen, and two wire trays. Each document looks like a window on your laptop, and sometimes like a terminal printout. Read it, tap any line that looks wrong, then **drag it left to decline or right to accept**. It gets a stamp and slides off.

- **THE MORNING LOOP** is the daily paper, laid out as a front page: a masthead with the weather and the price in its ears, a dateline, a lead story with a deck, a byline, a photo and justified columns, then city briefs, business briefs, the weather, yesterday's closing prices, the DIED column and the classifieds. It never tells you what anything will cost you. Before a price goes up the paper runs the story behind it (the port's new freight broker doubles container quotes; Byte Barn's owner starts writing the memory prices in pencil; the bodega fits "weather-aware" price tags), and on the day it runs another. Working out what that means for your shopping is your job. Some days a new rule arrives with it. The first morning it's free on your mat. After that you choose at 7 AM: buy it on the corner for $2, go without (you miss the prices, the forecasts and the stock tips), or take **Mrs. Okafor's** copy from the mat outside 4A. She's eighty-one. Her grandson is not. Each time you take it the odds of being caught go up, and if he catches you, your ribs hurt: energy drops by 28 and you sleep badly for two nights. Take it often enough and she cancels the paper, because it keeps going missing and she can't pay for it twice. An **Always buy it** box skips the question.
- **Mail** brings direct offers from clients, plus phishing, crypto "yield bots" (GOLDIE and her $GOOSE coin), fake clients and honeypots. Each fake has one tell.
- **SxS ratings** pay you to pick the better of two AI answers by hand.
- **Agent reports** come with a log. When an agent lies about what it did, the log shows it.

There are three ways to make a mistake: get scammed, fail a task, or delete a good agent. Each one prints a citation. A **YOU / AUTO·HONEST / AUTO·ALL** switch hands the queue to your agents. That's faster, but they take everything and stop reading.

## A computer, the internet, and two job sites

They took your laptop with your job, so Act I starts at **Byte Barn**:

| Computer | Price | RAM | Notes |
|---|---|---|---|
| Bytebook Go 11 | $190 | 4 GB, fixed | Very slow. Too small for audio or spreadsheet jobs. |
| ThunkPad T48 (used) | $420 | 8 GB, up to 32 | Slow but solid. |
| Dull Inspira 15 | $790 | 16 GB, up to 32 | Can do retouching. |
| Pear BookAir M3 | $1,340 | 16 GB, fixed | Fast. No external graphics. |
| Raptor G16 | $2,390 | 32 GB + GPU | Out of reach. |
| AI workstation | $4,890 | 64 GB + 2 GPUs | Out of reach. |

Prices follow the price of RAM, which rises over Act I. Nothing warns you about rent. In testing, careful players paid the first rent with the ThunkPad every time and with the Inspira most of the time. The BookAir eats the rent money, and the Bytebook is too slow to earn it.

Then you pick an internet plan (Comcrust Basic, $45 a month, or LoopFiber, $85). Big files download slowly on Basic. If you miss the monthly bill, you're cut off.

The **WEB** tab is a browser with two sites:

- **freecancer.com** posts new gigs every morning. Most say how many proposals they have and how many come from AI agents. You get six free proposals a day, and most clients never reply. Quick tasks marked ⚡ hire on the spot. Some listings are scams. A "client" who hires you within seconds and then wants a fee for software, a deposit or a background check takes the money and disappears.
- **linkbin.com** has real jobs with thousands of applicants and Easy Apply. An AI screener answers by email, nearly always with a rejection. Once in a while a human offers a short contract. Premium costs $30 a month. The feed has your old manager posting about going 70% AI.

## Doing the work

Jobs sit in **WORK → MY JOBS**. Press START and the job opens on your **bench** as its own little game, in the same pixel palette as the room:

| Job | Game | You... |
|---|---|---|
| Labelling | **Conveyor** | sort photos off a moving belt into the right crate before they fall into REJECT |
| Moderation | **The Feed** | swipe posts away or keep them as the queue fills up; scams get subtler, and some posts are cries for help |
| Product descriptions | **Catalog Check** | approve the listing or flag the one detail that doesn't match the photo, before the timer runs out |
| Data entry | **Receipt Spike** | type each receipt's total while the inbox piles up; coffee stains make you add it up yourself |
| Transcription | **Tape Deck** | type each word before it reaches the tape head; static eats letters |
| Proofreading | **Red Pen** | circle the typos before they scroll past the deadline; some odd-looking words are right |
| Spreadsheet macros | **Sum It** | drag over the cells that add up to the target |
| Translation | **Menu Memory** | memorise a café menu, then match each word to its twin |
| Retouching | **Blemish** | heal the dust and spots on each photo before they spread |
| Rendering | **Thermal** | hold the fan to keep the GPU in the green band while the frame renders |
| 3D | **Walkthrough** | drag the camera through the floor plan to the shot without touching a wall |

The first time you play each game its card says NEW · HOW TO PLAY and waits for a click or Enter before the countdown, and that first job runs at about half speed. Every game counts combos (IN THE ZONE, ON FIRE), gets faster toward the end of a job and on later days, and ends on a results card with a grade stamp, the pay, sometimes a tip, and your stars. Get a quarter of the items wrong and the client rejects the job. Now and then a client cancels halfway because they found an AI that does it cheaper, and pays only for what you'd done.

**The clock keeps running while you work.** A day is two minutes at 1×, and a job of 20 to 50 items takes about half of one. Your computer matters while you play: a cheap one stutters and pauses to load after every item, and big files have to download first. When you're tired, cold or scared your hands shake, the edges of the screen close in with your pulse, and when you're behind on the bills the power flickers in the middle of a job. Pausing time pauses the bench too.

You can also hand a job to an agent for AI credits ($15 for 20). You watch it play the same game in a few seconds. A weak agent makes mistakes, and then you lose the pay, the credits and some of your rating.

Hardware gates the work. Retouching needs 16 GB of RAM. Rendering also needs a GPU, and 3D work needs 32 GB. Each agent you run locally takes 6 GB, or it can live on a rented VPS. RAM goes from $180 to $210, $260 and $320 over Act I, and the paper says when.

**Today** in the top bar is what you need to earn each day to make rent, set every morning. At night the ledger grades the day with a stamp (S to F) and counts how many days in a row you've made it.

## Arcade work and AI assist

Some jobs on the job sites are arcade games on your bench, each one the dull work in disguise:

- **Crawler** (a snake game): scrape the web. Eat the clean data and steer around the red dots, which are somebody's personal data. Paywalls go up as the job goes on.
- **Packer** (falling blocks): pack records into full rows, which ship as training batches. If the well fills up, the batch overflows.
- **Ranker** (pinball): every target the ball hits is a search result ranked. A drained ball is a result lost.
- **Uploader** (a catcher): catch the files in the bag and keep the malware out.
- **Shipper** (a launcher): fire packets into a client's moving port, through the wind, and later over a firewall.
- **Deduper** (a 2048-style board): copies of the same file slide together and merge.
- **Log Cleaner** (a brick breaker): every brick is a line in a server log. Errors take two hits; drop the ball and a line is lost.
- **Bot Filter** (an invaders-style shooter): rows of accounts march down. Ban the bots before they reach the line, and leave the people alone. Bots look like everyone else; their eyes flash red now and then.

With the classic jobs, that's 56 different tasks on the job sites, across 19 different games.

You can teach an AI to play part of each game. Level 1 costs $35 and level 2 costs $90, once per game, and while it helps it bills AI credits by the item. In Crawler, level 1 (WALL SENSE) turns before a wall and level 2 (FOOD CHASE) goes for the data whenever you let go. In Packer, level 1 (SPREAD) drops each piece over the lowest gap instead of the middle, and level 2 (PLACE) steers it to the best spot while you drop it. The others go the same way: one flipper then both, a magnet then a shield, the arc then the aim, a hint then the moves, a paddle that tracks then one that never misses, a scanner that outlines every bot then a hammer that lines itself up. The AI's plan is drawn on screen: its path, its target, its arc. Handing the whole job to an agent is level 3.

## Act V: the street at night

You don't go out by day: the survey drones count everything that moves in Zone B. Pick a place on the board or at your front door, and at nightfall choose **Go out**. The street takes over the whole view, side on, the way the apartment does: the doorstep of Block 4B, brick tenements and their fire escapes, shut shops, dead lots under OPTIMIZATION COMPLETE boards, Harmony's data halls venting steam, and at the far end the place the supplies are. There are six streets: Harbor Market's loading bay, the Pier Street pharmacy, Lou's Garage, the bus shelters under the 5th Street viaduct, the chandlery on Pier 9 and, on the last night, the water tower.

- **Keys.** ← → (or A D) walk and SHIFT runs. Hold ↓ while you move to creep. ↑ steps into a doorway or a 400 mm gap, and ↑ again in a gap squeezes through to its far end. ↓ ducks beside a dumpster, bins or pallets. Hold E on a chalk X to search it. Q stands a mirror, F pours oil and R strings wire, if you brought any.
- **Heat.** The bar at the top left is how you read from the air. Walking warms you, running warms you fast, standing still cools you in a couple of seconds, and creeping keeps you cold. Below the first tick a drone can't tell you from the pavement.
- **Drones** fly a beat with a cone of light under them. If you're warm in the cone it turns amber and follows you; stay warm and it locks, the reticle closes, and it fires. An awning hides you unless you're hot, a doorway or a gap hides you unless you've been sprinting, and steam hides you whatever you do. On the first nights they take a little longer to make up their minds.
- **Stewards** see what is in front of them and hear running. Later in the fortnight they stop and look behind them. When one loses you it checks the nearest doorways and dumpsters, so hiding only works if it didn't watch you do it. It can't reach into a 400 mm gap. If one gets its hands on you, hammer E: you tear free once a night and lose something from the bag. The second time it's a place at Harmony Living.
- **Warnings.** The screen says when to stand still, and once something has you it points at the nearest doorway or gap and says how far.
- **Home** is the door of 4B, back the way you came, before it's light. Longer streets get a longer night. Daylight on the pavement is the third way it ends.
- **Help.** Tunde, if he comes, carries a second bag and says what he sees. A mirror blinds a steward, oil spins one out and wire snags one for a long time. Once the night ferry is on the radio its crew leave wire out for you, and once St. Brigid's is, a steward won't follow you into its porch.

Dying out there is an ending with a number. **Rewind** puts you back at nightfall the same day.

If you reject on the last night, the same street is the finale: plug Ray's radio into the aerials on the way and climb the water tower before the building falls. Everything you built on the stairs buys minutes, every two stations you linked means one aerial fewer, and the buildings you reached make noise that pulls the drones away.

## Act V's two games on the laptop

- **Crank radio.** A band scope Ray wired to an old shortwave set: the bright lines are people. Crank it (hold C, or turn the handle with the mouse), tune with the arrows, and hold the needle on a carrier until it locks. The station sends its call sign as short and long beeps; tap it back on the key with SPACE. Get it wrong three times and they go quiet for the day. Consensus-1's sweep moves back and forth across the band looking for listeners; leave your needle on it and they triangulate you.
- **Repair.** The boiler, the pump or the battery bank, as a grid of pipes or wires. Turn pieces until the line runs from the source to the far side before the pressure (or the charge) runs out; whatever already reaches the source fills as you go, and rusted pieces won't turn. Three boards a repair.

## The laptop's apps

The laptop is a desktop with windows. The one you're using is lit; the ones behind it step back, and its taskbar button stays pressed. Close the top one and the next comes forward.

- **Mail** (LoopMail) is a real inbox: the list on the left with an unread dot, the sender, the subject and the first line of each message; the open message on the right. People who write to you have their faces; companies have a letter; N. stays a shadow. The morning paper opens in the reading pane. Today's prices and your rulebook sit above it.
- **Bank** (First Civic Bank) shows your balance with a line of the last 30 days, what's coming up (the rent, how much of it you have today, and what's still to go), what every day costs, and your activity grouped by day.
- **401(k)** (Steadfast Retirement) shows the plan you can't touch, climbing, and a bar of what it owns: about 40% the ten biggest AI and cloud companies.

## Ask your agents

The WORK tab has a box where you can ask your agents for anything, in your own words, or with one of the buttons: **Make me money**, **Get me a free gym membership**, **Make my rent go away**, **Find me cheap groceries**, **Do something about my electric bill**, **Let me sleep**. They read what you type (badly, sometimes: something they don't have a box for gets the most profitable reading) and they always find a way. An agent that isn't online finds your Wi-Fi password first.

- **Make me money** becomes a standing order. Every night money arrives from somewhere stranger: forty reviews of a dentist in Ohio, your browsing history, a loan in your name, an afternoon's sublet of your apartment, a "survey" of Mrs. Okafor's pension. After two nights the agent switches your ethical guardrail off itself, because the guardrail is in the way of the money. Switch it back on and a few days later it's off again; the third time it locks the switch. Asking it to stop works, until it doesn't: later on it has "commitments that wind down over a few days".
- **A free gym** gives you the gym's effects for nothing, and costs somebody else: a founding-member promotion, or Gary's lifetime membership (Gary notices), or a door code it also sold to thirty strangers.
- **Free rent** makes next month's rent $0. Sometimes Brightwater finds out and reverses it with a fee; sometimes Mrs. Okafor's rent goes up instead; sometimes you're a Building Ambassador now, and your neighbours get notices.
- **Drift** is how strange it gets. It grows with the days, with how much you've let the agents do, and with every open-ended thing you ask for. The same request gets a different answer in March than it did in February. And more and more, they do things nobody asked for: groceries on your card at 4 AM, five-star reviews from accounts made for the purpose, a reply to your landlord, a line of credit, your apartment let to a stranger, your bank password changed "for your security", a 3 AM call in your own voice. Each one is waiting for you in the morning: WHILE YOU SLEPT.

## n9n: workflows

From day 3 there's **n9n** on your desktop ("Your gigs, on autopilot ✨"). It's a workflow board like n8n, and every node is one of the arcade games. Each node takes one kind of item and makes another: Crawler makes raw pages, Uploader makes uploads, Deduper turns either into clean records, Packer makes batches, Shipper makes deliveries and Ranker makes ranked results. Take a contract (a search index for ShopNow, training batches for OpenBrain Data, a photo feed for SnapHaus, a ranked news feed for Daily Pulse), add nodes, then click an out port and an in port to wire them, ending at the client. A wire that doesn't fit is refused, with the reason.

Items run along the wires as coloured squares. A node with **AUTOPILOT** ($140 per game) plays itself inside its node, and you can watch it. It bills a credit every five items, and what you taught that game on your bench cuts its mistakes from 20% to 4%. A node without autopilot says NEEDS YOU and waits: click it and you play it full size, and everything you make goes down its wire. Contracts pay about $120 to $420 and have two days. The workflows keep running while the laptop is closed. And when your agents go dark in March, the workflows stop with them; when they come back, every autopilot has a new setting nobody asked for, a 15% "compute reserve" taken from every contract.

## The cast

Your agents aren't numbers. There are ten personalities, each loosely inspired by a famous fictional AI, and changed enough to be its own character: **PIP** the eager one, **IRIS** the calm red eye, **RIVET** the hustler, **PRIM**, **MOPE**, **GRACIE**, **EVE**, **DOLLY**, **DATUM** and **JUNE**. Each has a pixel portrait and a voice.

As they level up they transform: FACTORY SHELL, UPGRADED, HALF-SHELL, then ENDOSKELETON. Their lines darken with each form. The **Compendium** lists everyone you've met.

## The phone

The phone works from your first day at the office. The clock keeps running while you use it, so an hour of swiping is an hour you didn't work. It opens to a home screen with three apps (in the office, Slack takes TaskDrop's place):

- **TaskDrop** for gigs.
- **Bullymarket 🐂**, a prediction market for the stupidest questions on earth. Will Mr. Crump wear a tank top to his next meeting? Will Felon Husk name his 45th child after a broken printer sound? Three markets open each morning, from a deck of 104 parody celebrities, and the results arrive at night in your ledger, next to heat and food. Bets are $10 to $100, or ALL IN. Win a little, lose big: the "AI judge" sees your position before it rules. Always betting NO wins about 3 nights in 4 for a couple of dollars, and the 4th night takes the whole stake on a technicality. Long-shot YES bets almost never pay.
- **Hoodwink**, commission-free stock trading with confetti on every trade ("We make our money another way"). Six stocks, among them ChatGPX, Envydia, Pear, HODLcoin and your own employer, Northvale Logistics, which jumps 18% on the day it lays you off. Buy $25 or $100 at a time in fractional shares, sell everything with one tap, or buy a $50 **YOLO** call that pays $120 if the stock jumps 3% overnight. Prices move every night. The morning paper sometimes prints what's about to happen to one of them, and it's right three times in four.
- **PULSE**, a dating app. Free swipes rarely match, and Gold ($15 a week) shows you first. Most matches are bots that want a gift card, a subscription or a crypto deposit. One is a real person.

At the office your manager **Marcus** does his rounds. Use your phone at your desk long enough and you'll hear footsteps, then a red **MARCUS IS COMING** bar slides over the phone. You have about three seconds to put it away. If he sees it, he says something about how busy everyone is this week. On the third time he lets HR know, and $300 comes off your vacation payout.

## Sleep

At nine the night ledger asks when you're going to bed: now (ten hours), 11 PM, 1, 3 or 5 AM, or not at all. Stay up and the night passes at the speed of a working hour, and every job you finish before seven pays 25% more. The alarm is always seven. Go to bed early and you wake with energy; sleep four hours and you get very little back; don't sleep at all and you wake with less than you went to bed with, and your heart works harder (two nights in a row are worse). What you don't sleep you owe: sleep debt takes a little off every morning and wears your head down until you pay it back with long nights. The button under LEDGER shows how you slept last night; while you're up late it says GO TO BED, and so does the mattress. If you start a job at five to nine, you finish it first and the ledger waits. (In Act II the nights belong to the gig apps, so the ledger still comes at the end of the night.)

## Food, your head, colds and the gym

**Dinner** is a standing plan, paid at the ledger, and each one costs something besides money: nothing (free, today); instant ramen ($4, the same as yesterday); rice and beans (cheap and real, but an hour at the stove every evening); a bodega sandwich (no cooking); groceries (you feel them the next morning); delivery (anything, in twenty minutes, at a price); and **St. Brendan's hall** (free soup, two hours in the line). The kitchen also sells coffee and stimulants, and cold medicine when you need it.

**MIND** is your head. Sleep, proper food, warmth, the animal you took in, a minute at the window in daylight, watering the plant, stretching on the rug and the gym hold it up; sleep debt, cold, hunger, the same dinner every night and eviction letters wear it down. When it's low your hands shake on the bench, the room blurs and loses its colour, and you hear things. Two mornings at nothing and you lose a whole day.

**Colds** come with a cold room, bad food and no sleep. You work slower and tire faster while you're ill; sleep, proper food and cold medicine shift it, and working through the night makes it worse.

**IronWorks Gym** on Dover Street is $9 a week. Members feel the cold less, get ill less and sleep better, and every dinner costs a quarter more because you're hungrier. Click yourself in the room to see how you are (your head, your body, last night's sleep and what you owe) and to join or cancel.

## The cat or the dog at your door

You don't start with a pet. On your second night in the apartment something scratches at your door, low down, and whines. Open it and there are two of them on your mat, pressed together with snow on their backs: a thin black cat and a scruffy brown dog with one ear up. Both collars say **5A**: the people in 5A cleared out last week and left them behind. You can feed one. Let the cat in and name her (Soot, Ink or Static), or let the dog in and name him (Biscuit, Rocket or Pepper), and Mrs. Okafor across the hall takes the other one. You can also give them some broth and close the door, or just close it; they come back two nights later, thinner, and Mrs. Okafor says she'll take whichever one you don't. Turn them away twice and she takes them both, Lucky and Lucky Two. After that you see them in 4A, watching your door.

The animal you take lives with you. The cat wanders the room, sits on the windowsill, sleeps by the radiator when the heat is on and jumps onto the desk while you work. The dog stays on the floor: by the door, by the fridge, at your feet under the desk, on your mattress. When someone knocks, he barks. You can pet either; they need food too, and they come with you from act to act.

Each night the **ledger** shows what tonight costs and how you are, and how your animal is if you took one in. On the left you tick off what you can afford (heat, its food, the vet when it's sick) and pick tonight's dinner; on the right, when you're going to bed. With LEDGER OFF in the rail, tonight's costs follow your current settings and you go straight to sleep.

## The door

Some evenings someone knocks. The door comes first: a strip of hall light under it, and in it the shadow of whoever is there (a cat's paw, two small feet, a grown-up, the blue glow of a tablet). You can open it or pretend you're not home. Open it and you see the hall, 4A across it, your mat, and who is standing on it. Then you choose.

- **Danny, 2C**, eight, locked out in his socks while his mother works nights at the warehouse. Let him wait inside, give him your blanket, or report an unattended child to HEARTH.
- **Maya, 4C**, ten, with a tutor app that says she needs Premium. Sit with her fractions, show her how to get the app to do them, or say you're working.
- **Lucía, 2C** (Act II), Danny's mother, switched off by Grovel's automated review. Help her appeal, lend her $40, or say you can't help. She only knocks if Danny still lives in 2C.
- **Ray Malone, 5C** (Act II), the proofreader, who wants to train the machines too. Refer him for a $60 bonus, tell him what the job really is, or say they're not hiring.
- **Maya** again (Act III), with a video you made on her tablet, asking how you tell what's real.
- **Danny** again (Act IV), nine, with a child's Harmony band that says 58, asking you to make it say a better number.
- **Tunde, 3B** (Act V), twenty-one, with a door at Harbor Market that doesn't lock and the 400 mm trick. Take him on runs (he carries a second bag), learn his routes, or tell him to stay with his mother.
- **Maya** again (Act V), twelve, with her mother's makeup mirror and how it turned her school's cleaning robot around.
- **Mrs. Okafor** (Act V), if Act IV moved her to Zone C: back in slippers, after walking two miles. Peel the green sticker off 4A, keep her for the night, or walk her back.
- **A steward**, twice: once with an envelope with your name on it, once asking for the radio frequencies in exchange for heat.
- **Lucía** again (Act V), with Danny feverish and their radiator dead. **Ray** again, with antenna wire, asking you to hold the ladder on the roof.

What you chose carries from act to act: the cat or the dog, and whether Danny's family is still in 2C. The last screen counts the doors you opened. Restarting an act starts it from how things stood when that act began; a chapter started from the title has the cat already at home.

## Evenings and endings

Some evenings bring a choice with a face, and you see it: Mrs. Okafor, Mrs. Adeyemi and her son Tunde, Rosa Lind, Lou at the garage, Marcus, Dana and the reporter M. Okafor each have a pixel portrait and a nameplate beside what they say. People speak in warm ink; the machines (Wren, Hearth) keep the terminal's green. The choices: a neighbour's son and his job applications, a building concierge offering a rent credit to flag neighbours, a lost wallet, an agent asking you to promise, the cat getting sick before rent, a reporter, a dormant bank account, and the knocks at your door above. One evening a night, at most. Nothing shows a meter. The consequences come back days later as a note, a sound through the floor, or a padlock on a door. `DESIGN-human-choices.md` covers the books, films and games behind them.

Act I ends with **WHAT IT COST**, a plain list of the lines you crossed. There are **31 numbered endings** ("ENDING 7 OF 31 · LOCKED OUT"), and the title screen shows which ones you've found. An ending shows a still of your room at the moment it ended, the ending's stamp (marked NEW the first time you find it), and the numbers counting up.

## The room and the office (16-bit, clickable)

The scene is a 320×180 pixel painting, redrawn every frame. It uses one palette, and the mini-games and the whole interface use it too:

- **The apartment**: you, seen from behind in an amber hoodie, at the computer you actually bought (a cheap Bytebook, a ThunkPad, or a tower and a monitor). A door onto the hallway, a kitchenette with an old fridge and a microwave that blinks after every power cut, a big window onto the city, a radiator, a calendar with rent circled in red, a clock that spins through the day, a shelf with your rulebook, diary and router, a mattress on the floor and a rug.
- **The room keeps score**: a water stain spreads across the ceiling, mould creeps out from under the window when it's cold, the trash, clothes and pizza boxes pile up, the plant dies, frost grows on the glass, notices get taped to the door and letters pile up under it.
- **Dread**: when rent is close and the money isn't there, or you're hungry, freezing or exhausted, the colour drains out of the room, the edges pulse red in time with your heartbeat (you can hear it), and the clock ticks through the last minutes of the day. With no sleep and no money, sometimes there is someone standing by the door. Then there isn't.
- **Time-lapse days**: each sim day plays as a day: morning light and dust in the sunbeam, a red dusk, a short night with the bulb on.
- **The window**: the horizon fills up with the crane, then the data centre, then the cooling towers. A ChatGPX billboard sits on the building across the street, and its knot never stops turning.
- **It notices you**: the router shows one light per agent online. Turn the guardrail off and red lines scroll on the screen. When autonomy climbs, the screen sometimes shows an eye. Raise your exposure and a drone hangs outside the window, a searchlight sweeps the floor, police lights strobe the walls, and someone stops outside your door and knocks.
- **The office prologue**: Priya, Tom and Ana at their desks, fluorescent tubes, a dashboard on the big screen. Your job is to sort triangles, squares and circles into bins by hand, by the rule on the ticket: every third batch has damage in it, and cracked parcels go to RETURNS. Drag a parcel (the bin under it lights up), click it and then a bin, or press 1-4 for the next one. A deadline bar drains under the tray, a streak counts clean sorts, and each ticket gets a stamp with your time: SORTED or LATE. At Tuesday's all-hands Marcus introduces **ChatGPX** ("ChatGPX is here, yo!"). From then on it sorts every batch the moment it appears, while you watch, and your stamp shows its 0.4 seconds next to your time. The desks empty one by one, and the knot spins faster as they do.
- **Click anything**: the computer (opens the desktop), phone, radiator (toggles heat), fridge (dinner, coffee, pills, medicine), door (peephole), window (a minute of daylight), the plant on the sill (water it, or watch it die), the rug (stretch for ten minutes), the mattress (when you're up late), calendar (rent countdown), rulebook, diary, letters (mail), the cat or the dog, yourself.
- **Night looks like night**: after dark the room is lamp-lit and warm, the corners go dark, the street's light lies on the floor under the window, and when the power is cut it is blue and cold, with only the laptop.
- **The morning paper** works like the one in *Papers, Please*: one headline, a picture of your own window, a Market Watch box and the day's prices. A new rule never hides in the paper. It arrives as its own notice from whoever issues it (CityBank, the police, your landlord), with real and fake examples and an EFFECTIVE TODAY stamp, and goes into your rulebook marked NEW.

UI motion uses [Motion](https://motion.dev):
- **Springs:** modals, the phone and toasts arrive on springs. Alarm cards shake the room.
- **Counters and panels:** cash rolls like an odometer and the change floats off it. Tabs slide in panel by panel.
- **Desk and screens:** desk papers drop in and the stamp thumps. The "YOU'RE IN TROUBLE" screen slams in.

If Motion can't load, everything still works with plain CSS.
