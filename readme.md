# Call record detail (CDR) analysis using K-means clustering

Project made as an assigment of Programming with Python for data science course
___

After the September 11 attacks, a series of secret regulations, laws, and processes were enacted, perhaps to better protect the citizens of the United States. Then, on May 24, 2006, the United States Foreign Intelligence Surveillance Court (FISC) made a fundamental shift in its approach to Section 215 of the Patriot Act, permitting the FBI to compel production of "business records" relevant to terrorism investigations, which are shared with the NSA. The court now defined as business records the entirety of a telephone company's call database, also known as Call Detail Records (CDR or metadata).

News of this came to public light after Edward Snowden, an ex-NSA contractor leaked the information, and a few more questions were raised when it was further discovered that not just the call records of suspected terrorists were being collected in bulk... but perhaps the entirety of Americans as a whole. The white house quickly reassured the public in a press release that "Nobody is listening to your telephone calls," since, "that's not what this program is about." The public was greatly relieved.

**The questions we try to explore in this analysis are: exactly how useful is telephone metadata? What kind of intelligence can you extract from CDR metadata besides its face value? Are we able to estimate possible home or work place using ones call metadata?**

It looks like call detail records or metadata are quite helpful if we want to estimate where particular individual live or spend most of his time. In this analysis, we presented the method to estimate probable home place. Using this method we would be able to specify where the person works, where he spends free time, what venues usually visits.