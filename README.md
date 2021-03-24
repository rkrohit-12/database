# database

Use expressjs with mongodb or mysql for this. You need design database tables yourself based on the question.

We have two entities “candidate” and “test_score”
candidate has properties name, email address
Every candidate has to give 3 tests like “first_round”, “second_round” , “third_round” and scoring for every test is done out of 10. 

Now using expressjs, only need to create api to do the following
Insert a candidate into database
Assign score for a candidate based on the test
Api to get highest scoring candidate and average scores per round for all candidates
