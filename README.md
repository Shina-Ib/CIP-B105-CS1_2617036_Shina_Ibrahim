# Digital Currency and Chrome Web History: Cryptocurrency Transaction Reconstruction
**Overview**

This project documents a digital forensics investigation into Chrome browser activity linked to an alleged online drug transaction.

The investigation analysed Chrome History SQLite databases and controlled recreation data to reconstruct browser activity and assess a seven-stage hypothesis.

**What Was Analysed**
1. Chrome URLs, visits, and downloads
2. Craigslist posting and management activity
3. Gmail and Imgur-related activity
4. Payment-receipt downloads
5. Bitcoin wallet addresses and transaction IDs
6. Blockchain explorers, Kraken, and mempool activity
7. UTC timeline and evidence matrix

   
**Methodology**

The databases were preserved and hashed before analysis. SQLite records were examined read-only, Chrome timestamps were converted to UTC, and related browser activity was grouped into logical sequences.

The evidence was then compared against each stage of the seven-stage hypothesis.


**Limitations**

Some websites were blocked and several URLs could not be loaded during the investigation. This prevented certain pages from being fully analysed or independently verified.


**Conclusion**

The available evidence supports several stages of the hypothesis, but some findings remain limited due to inaccessible websites and URLs. The conclusions are therefore based on the browser artefacts and records that were available for analysis.
