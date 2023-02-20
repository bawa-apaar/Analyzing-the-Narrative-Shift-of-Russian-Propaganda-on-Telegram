# Analyzing-the-Narrative-Shift-of-Russian-Propaganda-on-Telegram
This is the comprehensive evaluation of the telegram posts that were broadcast by pro-Russian propaganda channels before and after Russia invaded Ukraine.

In order to accomplish this, I collect data by crawling  and compiling content from four major propaganda channels that existed between 16 October 2020 and 9 February 2023 (155k telegram posts). The dataset encompasses the information about the multiple modalities like text, image, video in the post along with the number of views, forwards, information about reactions and replies.  To comprehend the change in the content being produced by these channels and the change in the user interaction with these posts during the specified time frame, I ran statistical analysis on the data that had been gathered. 

## Dataset
Given Telegram’s popularity and growing influence, I collect and analyze data from the most prominent Russian Telegram channels. Specifically, we (I, Dr. Ugur Kursuncu, Dr. Dilshod Achilov) identified four Telegram channels are: `Kadyrov_95 (3M subscribers)`, `Solovyov (1.3M subscribers)`, `Operation_Z (1.3M subscribers)`, and `Colonelcassed (843k subscribers)`. Main rationale for selecting these channels is driven by the following three factors: they (a) are consistently ranked in the top ten most following channels, (b) are led by the most prominent Kremlin-linked propagandists, (c) have been active content creators of Russian pro-war propaganda. While two of the channels (Kadyrov_95 and Solovyov) predominantly post content about general issues pertaining to Russia (and Kremlin’s related spin-off version), the other two mainly focus on Russian war efforts in Ukraine. 

I used telegram's Telethon library to interact with Telegram. 

To install Telethon:
`python3 -m pip install telethon`
