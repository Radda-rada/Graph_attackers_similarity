# Graph_attackers_similarity

Source IP - identifies the attacker.
Attack Type - What kind of attack was it?
Timestamp - When did the attack occur?
Domain - What was attacked?
Number of attacks - How much events belong to which IP?

What graphs can be built:
Graph 1 - Number of Attacks per Attacker (This could be a bar graph where the x-axis is the unique source IP addresses (or attackers), and the y-axis is the count of attacks from each source IP. This will show you which attackers are most active.)

Graph 2 - Types of Attacks per Attacker. (This could be a stacked bar graph or grouped bar chart where the x-axis is the source IPs and the y-axis is the count of attacks, and each type of attack is represented by a different color (stacked) or bar (grouped). This shows you what types of attacks each attacker is launching.)

Graph 3 - Timing of Attacks. (This could be a time series line graph where the x-axis is the timestamp (you might group this into time intervals like hours, days, weeks, etc. depending on the amount of data you have), the y-axis is the count of attacks, and each line represents a different attacker (source IP). This will show you when each attacker is most active.)

Graph 4 - Attackers intersections. Code is inside. (To evaluate intesections of attackers (if several ips have the same target and tools))
