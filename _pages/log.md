---
layout: default
title: Progress Log
---
### Week: July 12, 2021
 * Goals:
   * Finish Chapter 3 and resubmit for review.
   * Finish Chapter 4 and resubmit for review.
   * Finish Chapter 5 and submit for review.
   * Get offsets of all LETs run of TAMU data.


### Week: July 5, 2021
 * Goals:
   * Finish Chapter 3 and resubmit for review.
   * Finish Chapter 4 and resubmit for review.
   * Get MCU of 1.9 MeV run of TAMU data.
 * Accomplishments:
   * Finished reply and edits of micro-SEFI paper. 
   * Chapter 3 is almost complete, I am just adding the references and some figures.
   * Chapter 4 is half-way done. I am still missing some text.
   * MCU analysis of 4_0 LET is running in debug mode because it failed once.

### Week: June 28, 2021
 * Accomplishments:
   * Send for review chapter 3 and first section of chapter 4 with first sentences as the main idea of all paragraphs.
   * Updated tool with newest version of pandas.
   * Tool now won't run into memory issues. I was able to generate the offsets which was no tpossible before.

### Week: June 21, 2021
 * Goals:
   * Finish Chapter 3 and submit for review.
   * Upload updated tool (with pandas 1.2.4).
   * Fix tool to deal with TAMU data.
   * Preliminary results of TAMU MCU analysis (shapes, frequency, sizes).
 * Accomplishments:
   * Continued chapter 3 and 4 of dissertation with whole paragraphs.
   * Uploaded MCU tool to github repo.

### Week: June 14, 2021
 * Worked on Chapter 3 first sentences (almost done with the whole chapter).
 * Started Chapter 4 and 5 (first sentences). 
 * Continued with TAMU data analysis. Long scrub cycles are causing two problems in memory. The first one happens after computing offsets of huge amounts of data. This one was solved by partitioning the data. The other problem is that the scrub cycle itself is long. I am working on soving this one. So far, I tried breaking up the scrub cycle and recombining the data (this is the naive and not the best solution). I am also updating the code to pandas 1.2.4 version. The code was created before pandas 1.0 was released, hence, it has some room of improvement.



### Week: June 7, 2021

* Worked on TAMU data analysis. Attempted to analyze all data to generate offsets. This failed due to corrupted runs.
* Worked on comments of Dissertation.
* Worked on Chapter 3 of dissertation. Adding only first sentences of each paragraph.



