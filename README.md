Introduction and Scenario
## Sales Engagement Platform
A Sales Engagement Platform (SEP) is a software suite designed to streamline and
automate various sales processes. It facilitates interactions between sales representatives
and potential clients (leads) by guiding the sales team through a structured sequence of
steps.

## In the SEP, a 'Sequence' is a predefined order of steps intended to optimize engagement with a lead. 
For instance, an email is sent on the 1st day, followed by a phone call on the 3rd
day if no reply is received, a LinkedIn connection request on 6th day if the call isn't answered
and so on. The goal at each step is to get a reply, either positive or negative. The sequence
ends when a reply is received or when the last step is completed. If the lead replies
positively, they are considered converted. If they reply negatively, they are considered
disqualified.
If a lead never replies, the sequence continues until the final step, at which point the
sequence for that lead is considered complete.
Your Role and Objective
As a Senior Business Analyst, your role is to understand the challenges faced by
stakeholders such as Sales Representatives and Sales Managers while analyzing the
Sequences and create metrics and dashboards to track those issues. Typically, stakeholders
such as sales representatives and managers face challenges like low lead engagement
rates, inefficient sales processes, and lack of actionable insights from data. Your objective is
to develop reporting solutions that can offer actionable insights to resolve these challenges.
Dataset
## The provided dataset consists of the following tables:
● Sequences: SequenceID, SequenceName, SequenceOwner
● Steps: SequenceID, StepNo, StepType, Day
● Leads: LeadID, Name, Email ID, Company, Seniority, Department
● Activities: LeadID, SequenceID, StepNo, Status, Email Opened, Email Reply, Email
Bounced, Call Answered, Linkedin Success, ReplyType
ReplyType = 1 means +ve reply
ReplyType = 0 means -ve reply
