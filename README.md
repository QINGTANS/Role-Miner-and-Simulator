# Role Miner and Role Simulator
This project includes two main tasks:

1. Role Miner — infers group and role information for each event to construct the organizational structure.

2. Role Simulator — uses the discovered groups and roles to perform enhanced process simulation.

## Role Miner
The input should be an event log with case identifier, activity, timestamp, and agent instance attributes.
The output should be an extended event log with group, role and group type attributes for each event, then they can form to the following structure.
![The organizational structure generated from Role Miner](motivate_RM.pdf)
