Data Pipeline: From Absolute Chaos to Client-Ready
"I didn't just write code. I went to war against messy data... and I won."

*Data Source: Kaggle (Author: fronkongames) - https://www.kaggle.com/datasets/fronkongames/steam-games-dataset*

🤯 The Nightmare (The Problem)
Imagine downloading a dataset of 125,855 Steam games, only to realize it's a complete disaster. This wasn't just "dirty data"—it was a crime scene:
- The Merged Monster: Two crucial columns (Discount and DLC count) were brutally fused into one, breaking the entire table structure.
- The Text Bomb: One game description contained a massive wall of text that literally crashed Excel's 32,767-character limit. 💣
- The Fake Websites: Developers listed pure garbage URLs like http://myfakegoblinwife (missing dots, missing domains).
- The Black Hole: Crucial data like Reviews and Metacritic url were missing over 90% of the time.

If a human tried to clean this manually, they would lose their minds. I didn't.

⚔️ The Do-or-Die Moment (The Real Threat)
Here is the brutal truth: **If those fused columns were not surgically split first, every single cleaning effort afterward would be 100% meaningless.** The entire table structure was fundamentally broken. You cannot fix a broken arm by putting a band-aid on it. I had to rebuild the skeleton before healing the flesh.

🛠️ The Counter-Attack (The Solution)
Instead of crying, I built an automated pipeline to execute a surgical strike on the chaos.
- Surgical Splitting: Detected and split the merged monster back into two distinct columns, saving the whole dataset from being useless.
- Brutal Deletion: Dropped useless, dead-weight columns that were holding the file hostage.
- Automated Validation: Set up a strict "police checkpoint" to catch violations (fake websites, missing names) and instantly nullified them.
- Pattern Hunting: Hunted down and fixed any website URL missing a dot.
- Anti-Crash Armor: Engineered a custom function to auto-adjust column widths and safely truncate giant text strings.

📊 The Result & The "Real-World" Optimization (The Victory)
- Before: 40 messy columns, 6 validation errors, and a literal text bomb. Total chaos.
- After: 36 perfectly clean columns, 0 nulls, 0 duplicates, optimized data types (saving 25% memory).
- The Delivery Masterstroke: Because the dataset was massively heavy and contained special characters that corrupt standard Excel files, I split the final output into 6 lightweight, perfectly formatted CSV parts. This guarantees the client can open the files instantly without crashing their machines.

<img width="989" height="619" alt="1000012672" src="https://github.com/user-attachments/assets/4cfbf9b1-52ac-48be-af1c-8ac96929bb0b" />

*(Screenshot of the final, beautifully styled client-ready report)*

💡 The Business Value
This project proves I don't just "know code." I can take a completely broken, real-world dataset and turn it into a professional, client-ready report in seconds. No drama. Just results.
