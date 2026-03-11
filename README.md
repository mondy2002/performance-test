# performance-test
this is a repo containing my work as performance testing in different demo websites 
websites like : https://orangehrm.com/ 
and 
https://blazedemo.com/login

Prerequisites

Before running the project, make sure you have the following installed:

Apache JMeter (Recommended version: 5.x or later)

Java (JDK 8 or higher)

Basic knowledge of performance testing concepts

How to Open the Project

Launch Apache JMeter.

Click File → Open.

Navigate to the test-plans folder.

Select the .jmx test plan file.

The test plan will load in JMeter GUI.
How to Run the Test (GUI Mode)

Open the .jmx test plan in Apache JMeter.

Review configuration settings (Thread Group, HTTP Requests, etc.).

Click the Start (▶) button.

Monitor results using listeners such as:

View Results Tree

Summary Report

Aggregate Reportjmeter -n -t test-plans/performance-test.jmx -l results/results.jtl -e -o results/report

results/report/index.html
