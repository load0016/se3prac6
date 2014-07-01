Test Plan: Scott Loader - load0016
==================================

Baggage Handling System for a Major Airport: Denver Airport Baggage Handling System

More information about the Denver Airport Baggage Handling System can be obtained from: http://calleam.com/WTPF/?page_id=2086

Approaching the Design
----------------------

The baggage handling system for the Denver Airport will be the base of this test plan. The design of the baggage handling system is to automate the handling of baggage through the entire airport. From initial check-in/arrival, the baggage would be sent through the airport to the desired location with minimal human interaction which would minimalize flight delays and less waiting with baggage carousels.

Decomposing the Problem
-----------------------

Components can be identified from the baggage handling system:

 - Check-in
   - Baggage weight is measured
   - Baggage is labelled with destination and flight number
 - Conveyor System
   - Conveyor belt system to guide baggage to and from terminals
 - System Software
   - Database for storing baggage information

Risks of this Design
--------------------

 - Identification of baggage: make it difficult to determine where the baggage goes when problems occur
 - Mechanical failure: can cause major delays if human baggage handlers aren’t on stand when problems occur
 - Misdirection of baggage: can occur when baggage isn’t labelled correctly from check-in

The greatest risks lie at the check-in area. If the labelling of the baggage is incorrect, this could cause major problems with the final destination of the baggage. If the labelling is read incorrectly at check-in, what’s to say it won’t get read incorrectly again while on the conveyor system and cause massive delays with other flights? If the baggage is read incorrectly, the bag will be sent on a different flight causing lost baggage.

Important Tests
---------------

 - Unit Testing:
   - Considering the system is so large, testing of individual components will ensure the system is tested correctly. Unit testing can be done on all the necessary components to ensure they all work together correctly.

 - Stress Testing:
   - A stress test would check if the system can work under heavy loads of traffic, both in the conveyor system and system software. This will ensure the system is capable of running correctly in busy peak times when many flights are leaving and arriving at the same time.

 - Recovery Testing:
   - Mainly refers to the conveyor system. If the conveyor system were to have failures, this will have heavy impact and will cause massive delays for flights. Considering the main advantage of this airport handling system is its state-of-the-art baggage handling system, major testing will need to be undertaken on the conveyor system to ensure it runs correct with any scenario.

Less Important Tests
--------------------

 - Black Box Testing:
   - Considering there are 88 airport gates in 3 concourses and most likely a large amount of check-in areas. A black box test won’t be sufficient as baggage would be sent from any check-in area to any of the 88 airport gates. This type of test wouldn’t work considering there to many situations to ensure a correct test.

 - System Testing:
   - A system test shouldn’t be needed considering unit testing will be done. Plus, considering the system is so large, there’s no guarantee that the whole system will be tested correctly, many scenarios will need to be tested which will defeat the purpose of the test.

 - Comparison Testing:
   - A comparison test wouldn’t work considering this is a state-of-the-art system which has never been done at this scale. Because of that, there wouldn’t be any system to compare it to as it’s the only one of its kind.
