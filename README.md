CodeFunDo-2019

Team ‘CODEenCODE’

#                                                       CROSS STATE VOTE 

Problem to be addressed: The 2019 problem statement addresses **Indian elections as the major theme** to ponder upon. After all the tedious process done by the Election Commission there are still many loopholes in the current election drive and **one of those issues is that if a person lives in any other constituency other than their registered one, they are not able to vote.**

This problem arises from the fact that Election Commission has the data set of the eligible voters and each and every person (eligible to vote) is assigned a serial number which is used to identify his/her casted vote to a particular candidate standing from that constituency. And **without that serial number, a person is not able to verify his/her identity and are rendered unable to vote.**

The current voter turnout is only a **meagre 67.11%.**

A very **self-relatable example** is for us students only studying in IITs and other technical institutions. We live far away and thus even being eligible to vote and our card made, we are not able to cast our vote. We want to improve upon this situation. 

Solution: We want to solve the above problem by using a different strategy and then implementing it with the concept of blockchain. 

### *Strategy:* 

•	Every **person must be assigned a specific and unique number**/identifiable value for marking his/her vote count. 

•	The **current practice of the serial number should be avoided** and instead that unique identity can be generated from one’s Aadhar card number. **That number can be a hash generated as a function of the party, candidate and aadhar number**. Also, the machine installed at the booth can be digital and should be able to access candidate data for that constituency from the central database 

•	And then simply a **counter variable** can be used for each candidate. For every vote it can be increased by 1. An independent candidate will have only a single counter variable. 

•	In the end, **only the counter variable values can be checked** instead of current method first which involves compiling the data and then counting the votes from each and every machine. 

### *BlockChain technology Implementation:*
  
•	**Each booth can be made as a node among the chain of blocks in the Distributed Ledger System (DLS)**. 

•	Going by our strategy, a booth (in a constituency) can cast as many votes as it requires according to the number of voters arriving and it will only store the counter variables in a particular block in the DLS. 

•	**According to our strategy only a single machine can do the work and rest of them can verify it being exactly same**.


