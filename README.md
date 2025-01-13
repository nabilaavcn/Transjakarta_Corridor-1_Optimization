
This repository focuses on optimizing Transjakarta's Corridor 1 in light of the upcoming MRT system, aiming to minimize overlap between the two systems and ensure continued accessibility for passengers. The study evaluates different strategies, including rerouting and removal, based on passenger travel patterns and operational efficiency.

Key Areas:
1.	Analyse passenger travel patterns using tap-in/tap-out data to better understand Corridor 1's role in transportation.
2.	Assessing the impact of removing Corridor 1 on user accessibility.
3.	Rerouting Simulation: Creating alternative routes to reduce overlap with MRT while maintaining essential services in areas not served by the system.

The aim of this project is to ensure Transjakarta maintains an efficient and accessible public transport system as the MRT develops, providing insights into the best approach for optimizing Corridor 1's operation and reducing redundancy with MRT services.

---

**Background**

Transjakarta, one of Jakarta's major public transportation providers, strives to offer its customers effective, reasonably priced, and traffic-free services. Corridor 1 Blok M – Kota is one of the busiest routes, handling up to 65,000–70,000 people daily. The Transjakarta Corridor 1 route, which is thought to overlap with the MRT line, is being examined for removal or rerouting in light of the building of the MRT system that would connect Lebak Bulus to Kota in 2029.

Nonetheless, there is disagreement over the policy, particularly among those who take public transit. Given that Transjakarta consumers vary from MRT users in several ways, others contend that Corridor 1 should not be eliminated. This has to do with variations in prices, accessibility, and general travel trends. Furthermore, Transjakarta is now a complementing transport system as it has been combined with other transit options like the Jabodebek LRT and KAI Commuter.

**Problem Statement**

How can Transjakarta address the transportation demands of users who rely on Corridor 1 while optimising operations to minimise overlap with MRT?

**Approach**
1.	Analysis of Corridor 1 Passenger Travel Patterns: This study uses tap-in/tap-out data to identify the primary routes of travel and the function of Corridor 1 in terms of user mobility.
2.	Impact Evaluation of Corridor 1 Removal: Examining the possible loss of user accessibility in the event that Corridor 1 is entirely eliminated.
3.	Corridor 1 Rerouting Simulation: creating other routes that minimise overlap with MRT lines while preserving service for people in non-MRT locations.

**Data**

1. transID:	Unique transaction ID for each transaction.
2. payCardID:	Customer's main identifier, the card used for entrance and exit.
3. payCardBank:	Bank name of the card issuer.
4. payCardName:	Customer's name as embedded in the card.
5. payCardSex:	Gender of the customer as embedded in the card.
6. payCardBirthDate:	Customer's year of birth.
7. corridorID:	Corridor or Route ID for grouping routes.
8. corridorName:	Name of the corridor or route, indicating start and end points.
9. direction:	Direction of the route: 0 for Go, 1 for Return.
10. tapInStops:	Tap In (entrance) Stop ID for identifying the stop name.
11. tapInStopsName:	Name of the Tap In (entrance) stop where customers tap in.
12. tapInStopsLat:	Latitude of the Tap In Stop.
13. tapInStopsLon:	Longitude of the Tap In Stop.
14. stopStartSeq:	Sequence number of the stops (1st stop, 2nd stop, etc.) related to the direction.
15. tapInTime:	Date and time of the customer's tap-in.
16. tapOutStops:	Tap Out (exit) Stop ID for identifying the stop name.
17. tapOutStopsName:	Name of the Tap Out (exit) stop where customers tap out.
18. tapOutStopsLat:	Latitude of the Tap Out Stop.
19. tapOutStopsLon:	Longitude of the Tap Out Stop.
20. stopEndSeq:	Sequence number of the stops (1st stop, 2nd stop, etc.) related to the direction.
21. tapOutTime:	Date and time of the customer's tap-out.
22. payAmount:	Amount paid by the customer, some free and some paid.
23. age:	Customer's age.
24. ageCategory:	Customer's age category (e.g., Adult, Teenager).
25. serviceType:	Type of service (if applicable).
26. distance_km:	Distance of the trip in kilometers.
27. seqDiff:	Difference in sequence between stops.
28. tripDuration:	Duration of the trip in minutes or hours.
29. dayOfWeek:	Day of the week when the trip occurred.
30. peakHour:	Whether the trip occurred during peak hours.
31. tapIn_timeOfDay:	Time of day when the customer taps in.
32. tapOut_timeOfDay:	Time of day when the customer taps out.

