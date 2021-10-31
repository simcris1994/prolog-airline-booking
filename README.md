# Prolog Airline Booking
Uses logic programming, in Prolog, in order to mimic the rules of a flight booking system.

In logic programming, one does not define the steps that need to be taken in order to compute something, like an algorithm. Instead, one defines relations between entities, which can be used to infer whether or not a statement is true.

This program allows the following relations to be defined:
  - a passenger's birthdate
  - the country that issued a passenger's passport
  - airport characteristics: code, city, country, weather conditions
  - visa agreements between countries
  - a passenger's reservation for a specific flight
  - flight legs
  - aircraft characteristics
  - aircraft seats
  
Based on these relations, we can ask the program a few questions:
  - Is passenger X allowed to fly into airport Y?
  - Is a reservation legal?
  - Is there a double booking?
  - Is a specific weather type suitable for a certain aircraft?
  - Is an aircraft allowed to take off?
  - Are airports A and B connected?
  - What airports are there on the path between A and B?
  - Given a route, are there any airport passenger X is not allowed to visit?
  - ... and more
