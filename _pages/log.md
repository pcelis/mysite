---
layout: default
title: Progress Log
---

### Week: July 26, 2021
 * Goals:
   * Debug offsets for 15 LET.
   * Finish Chapter 6 and submit for review.
   * Finish Chapter 5 and submit for review.
   * Update Chapter 2 (background). I realized that this chapter keeps on groing with more topics to cover. Might be the last to submit for review.
 * Accomplishments
   * TBA

### Week: July 19, 2021
 * Goals:
   * Debug offsets for 15 LET. The program gets killed after more than a day of running.
   * Finish Chapter 4 and resubmit for review.
   * Finish Chapter 5 and submit for review.
   * Finish Chapter 2 and submit for review.
   * Get MCUs of all LETs run of TAMU data.
 * Accomplishments
   * The program of LET 15 is running again in debug mode.
   * (Partially) finished running 24_3 LET but computer rebooted again. I need to check if it actually finished or not.
   * Finished Chapter 4. I am reading it before submitting it again.
   * Chapter 5 is about 50% or more done.
   * Created spreadsheet summarizing all the MCU results comoputed so far.
   * Try alternatives for the 15_0 let, started it running on the weekend after another power outage.


### Week: July 12, 2021
 * Goals:
   * Finish Chapter 3 and resubmit for review.
   * Finish Chapter 4 and resubmit for review.
   * Finish Chapter 5 and submit for review.
   * Get offsets of all LETs run of TAMU data.
 * Accomplishments
   * Submitted micro-SEFI TNS paper.
   * Added more background to chapter 2.
   * Finished chapter 3 and subitted for review.
   * Finished chapter 4 beam test sections. I am missing half of fault injection. 
   * Got Offsets of 3 runs and a half. The run 15 had an error and it killed the program. 
[21408926 rows x 5 columns]
Group Name:(1, 'LVDS', '0019:2', 367)
Killed



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



