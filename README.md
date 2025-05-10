This case study marks the first in a structured series of Indicators of Compromise (IOCs) designed to train cybersecurity defenders by walking through both the technical forensics of an attack and the attacker mindset that drives it. Each entry adheres to a strict investigative framework but is also paired with a "softened narrative" — a storytelling overlay that humanizes the threat and reveals the psychological and strategic aspects of the attack. The goal is to create not only technical understanding, but true pattern recognition and attacker fluency.

What This Case Represents
This IOC captures a foundational stage in the cyber kill chain: reconnaissance — where the attacker has not yet breached the system, but is actively probing to discover what might be open, unguarded, or improperly exposed. The network scanning attempt (detected via firewall logs and Windows Event IDs) is the digital equivalent of rattling every doorknob on a locked building, searching for the easiest point of entry.

From the defender’s perspective, this case highlights a few critical truths:

Not all IOCs represent an intrusion. A port scan is noisy, obvious, and often thwarted — but it is also a signal of interest. It tells you your organization is being actively evaluated for weaknesses.

Early detection is still valuable. Just because the attacker failed doesn’t mean they’ll give up. This case emphasizes the importance of early visibility, firewall logging, and geolocation filtering as tools that can reduce noise and identify persistence patterns.

Pattern recognition begins here. This case sets the stage for understanding the full arc of an attack — because many successful breaches begin exactly this way. Future IOCs in this series will pick up where this one left off.

