For [markdown syntax](https://www.markdownguide.org/basic-syntax/)
Can we use two tilde's around ~~strikethrough~~ when something moves from one stage to another?
# Ideas
  - 3 .compute similarity of rules by transfer effect on difficulty *PK* - the more rule X reduces difficulty of rule Y, the more similar X and Y are.
  - 4 . about a web interface for those processes: DETAILS:  PK2> You are correct.  In the example that I've computed, I only took all the sets in which the target (pk/position_A) appears.  You make a good point.  Can it be an option for the users? Check [ ] include all conditions of this experiment OR [ ] include only conditions in which the selected target condition(s) appear. [That would require an option or pull down list to select those targets.]  I am still puzzling over whether there is some way to define difficulty that will remain correct if we change the set of rules being examined.  I fear that it may not be possible at all. I agree that this analysis has to be presented with a "WARNING: the discussion here is conditioned on the specific set of rules and conditions being examined,  and should not be interpreted as an 'absolute' measure of difficulty or transfer effect."  Perhaps you can add that to the web report, in red ink. *PK*
- 5. in the "egg in my beer category" - it would be great if the analysis leading to the ecdf curves, based on not only what has been "seen" but on whether it has been solved, could be accessed by a dumb web user. This process has so many options, and produces so much output, that I am not even sure how to specify it.  For example, the graph(s) may become very cluttered, and the legend, similarly, would need to be extracted   to correspond to whichever graph is displayed. *PK*
- It's OK to briefly prioritize this computation of "conditional on what is examined, the transfer effect", but the **Gemini access** is more important because it is needed in order for Lazaros to be able to really explore that "unfunded initiative.
- 6. the results page has been fully updated in one of the recent server versions to properly account for all the members of adversarial pairs, the selection screen (http://action.rutgers.edu/w2020/tools/mw-human-form.jsp) has never been reviewed and updated in a similar way. As far as adversarial 2PG plans are concerned, the selection screen only counts the Player 0 in each pair; 
---  
# to be done

---
# in process - list start date please 

    develop pilot connection to Gemini using its API 3/11/2025  
    modifications to the board generator 3/11/2025  
    --  a. DONE	  
    --  b. include for each object on the board, an Id value (Id2) which is not associated with the cell number.  
---
# done - list completion date 

---
# checked - list checked date

modifications to the board generator 3/11/2025  
  --  a. provide a mask so that users can specify that pieces are only placed on selected cells.  
      This has been done with a more efficient implementation of the generation process. 3/15/2025 and checked (by PK) 3/18. 

 - 1. compute the difficulty of a rule from the EV score *PK*  defined as min{EV}/EV   checked 3/17/2025 
 - 2. compute transfer among rules, using change in difficulty *PK* Defined as fractional reduction in difficulty (computed as in step 1) checked 3/17/2025     
