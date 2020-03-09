# compuerDBJmetertest
# Perfromance test with Jmeter
# Note: This is not Production ready code and this is only used for showing technical ability For testing purpose , Please take care extra care when running with  tests **

# This colelction test is targetted to Get all the computers and Creates the new compuers and wont delete the test data , so please have less iteration tests 

Instructions to run the tests
# With Postman

import below collection on the Postman
computerDB.postman_collection.json
Click Run from the Postman collection runner ** Please 
Configure Iteration as minimal as possible ex: 1
click Run computerDB

# with Jemeter

open the Jemeter window and import the below test plan 
computerDB.jmx
Currently Loop count and Threads are configured as 2 for 
Click Run button on Jmeter UI

# with Loadiam (postman collection / jmx file runner  if you dont have Jemter setup 
Got to https://loadium.io/test/new/jmeter

import jmeter testplan  computerDB.jmx 
# please configure as least number of therad and loop count and test duration
click run test 

sample test result available in below link 
https://loadium.io/test/public-report/sif9s7ms56ag5cd6kvv5ik2hmoa3l69j/session/q6e20mfft4koo1c9j2cs120julk30hvn

Performance test Implication 
This test will cerate 
Load on the Appliation and Database
un necesssary test data on the database

this may break the application / database server with running huge amount of test data or make the slowness of the application.









