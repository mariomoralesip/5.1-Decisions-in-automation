What are decisions in automation?

We usually make a decision about a problem after a phase of reflection. This means that we think about the consequences of different courses of action. The same principle applies to the operation of robots and automation. There are times when a workflow can branch in more than one direction.

When we talk about decisions in automation, we usually mean finding a solution to a "True" (yes) or "False" (no) question that tests a condition. Depending on whether or not the condition is met, the robot is told a course of action.

Yes graphic_NO_PROCESS_.png
An example would be "Is this credit application eligible? If yes, then the robot shall perform a series of actions. If false, then the robot will have to perform another set of actions. 

Note that when we formulate the condition, there must be no room for interpretation, as the robot cannot operate on "maybe".

The If activity and how to use it

The basic activity when making decisions in automation is the If activity. You will find it in the common StudioX activities, as you can pair it with any available resource.

Let's now take the example of the credit application eligibility issue.

If_NO PROCESS_.png
The If activity contains a statement or condition - what we have called the question, and two branches. In the given example, the branches are the two courses of action the robot can take, depending on the characteristics of the statement: Is it true (yes - Then) or false (no - Else)?

Suppose all credit applications are stored in a spreadsheet and the eligibility criterion is a threshold calculated in another cell.

How do we translate this to the robot? 

If cell D3 (application value) is greater than cell C3 (threshold), then do..., otherwise do....



Decisions in action

In this project the task is to ensure that all transactions in a spreadsheet are processed with the help of the Double UI dummy bank teller application. Assume that a number of documented transactions have been received, only some are processed, others are not.

In developing the automation you'll use the following input files, websites, and applications:

The "Transactions - May2022" spreadsheet - all transactions are documented here.
The Double UI app - this is the transaction processing tool.
