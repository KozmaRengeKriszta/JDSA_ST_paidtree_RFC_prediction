# JDSA_ST_paidtree_RFC_prediction
A Random Forrest Classifier prediction about paid tree purchases in a fictional application (Send a Tree). 

This was an extra task (which I made up for myself) after finishing the Junior Data Scientist Academy. 

ABOUT SEND A TREE:
This is a hypotetical online application, which has one feature at the moment: sending digital trees to your friends. There is a paid feature as well: you can send "super_tree"-s. The first "super_tree" is free, the rest cost $1. 

About THE DATA STRUCTURE:
Event types (tables): 
1. registration;
2. sent_a_free_tree;
3. sent_a_super_tree
Attributes (columns) for the events:
1. REGISTRATION: file_name, date, time, user_id, event, birth year, device_type, country, source,
2. SENT_A_FREE_TREE: file_name, date, user_id, event
3. SENT_A_SUPER_TREE: file_name, date, user_id, event

THE TASK:
Try to predict which users will become paid users based on the registration data and application usage so far
