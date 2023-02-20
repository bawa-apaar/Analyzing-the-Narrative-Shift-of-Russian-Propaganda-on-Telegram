# Analyzing-the-Narrative-Shift-of-Russian-Propaganda-on-Telegram
This is the comprehensive evaluation of the telegram posts that were broadcast by pro-Russian propaganda channels before and after Russia invaded Ukraine.

## Dataset
Given Telegram’s popularity and growing influence, I collect and analyze data from the most prominent Russian Telegram channels. Specifically, we (I, Dr. Ugur Kursuncu, Dr. Dilshod Achilov) identified four Telegram channels are: `Kadyrov_95 (3M subscribers)`, `Solovyov (1.3M subscribers)`, `Operation_Z (1.3M subscribers)`, and `Colonelcassed (843k subscribers)`. Main rationale for selecting these channels is driven by the following three factors: they (a) are consistently ranked in the top ten most following channels, (b) are led by the most prominent Kremlin-linked propagandists, (c) have been active content creators of Russian pro-war propaganda. While two of the channels (Kadyrov_95 and Solovyov) predominantly post content about general issues pertaining to Russia (and Kremlin’s related spin-off version), the other two mainly focus on Russian war efforts in Ukraine. 

I used telegram's Telethon library to interact with Telegram. 

To install Telethon:
`python3 -m pip install telethon`
CSV files for the data is present under Dataset folder.

We are analyzing the drift among the posts and corresponding user interaction among pro-russian channels from a year before to a year after the war. We performed comprehensive comparative analysis on the posts with respect to: (1) Post volume by modalities  (2) Views (3) Forwards (4) Reactions (5) Replies and (6) Content. 

