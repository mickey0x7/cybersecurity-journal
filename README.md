Cybersecurity Journal

Day 1 — [26-06-2026] — Linux Basics, Networking & First Wargame
Time

~2 hours
What I Did

Created accounts on GitHub, LinkedIn, TryHackMe, and HTB Academy, using the same username across all of them.
Practiced basic Linux commands.
Learned how to use nano after getting stuck saving a file.
Completed OverTheWire Bandit Level 0.
Finished the first TryHackMe networking lesson.

What I Learned

Today I learned that the Internet began with ARPANET, a project funded by the U.S. Department of Defense. Years later, Tim Berners-Lee created the World Wide Web, making the Internet much easier to use.
I also learned that every network device has two important identifiers:

MAC Address – identifies the specific hardware interface itself.
IP Address – identifies the device on a network and can change.

IPv4 uses four octets ranging from 0–255. Because IPv4 has a limited number of addresses, IPv6 was created with a vastly larger address space.
I also learned the basic idea of spoofing, where an attacker pretends to be another device by forging information such as an IP or MAC address.

Biggest Problem

I didn't know how to save and exit nano.
Solution

Ctrl + O → Enter → Ctrl + X
Reflection

Today felt like the first real step into cybersecurity. Everything still feels new, but I completed every planned task and solved the problems I encountered instead of giving up.

Tomorrow

Bandit Level 1,2,3
Continue TryHackMe Pre-Security or else related rooms


Day 2 — [insert date] — Bandit Levels 1–3 & Computer Fundamentals
Time

~1.5 hours
What I Did

Solved Bandit Level 1 — a file literally named -.
Solved Bandit Level 2 — a filename containing spaces.
Solved Bandit Level 3 — a hidden file inside a directory.
My planned TryHackMe networking room was locked ("Intro to LAN" and "OSI Model" both turned out to be premium now), so completed "Inside a Computer System" instead.

What I Learned

A file named - confuses cat because a bare dash is the shell's symbol for "read from somewhere else," not a real filename — adding ./ in front forces it to be read as a file sitting in the current folder. A filename with spaces gets split into separate arguments unless it's quoted or tab-completed, which made Level 2 harder than Level 1 even though the underlying idea — the shell taking filenames literally — was the same in both. ls by itself hides anything starting with a dot; ls -la shows everything, which is how Level 3 turned out to be the easy one of the three.
On the TryHackMe side, I went through a body-part analogy comparing PC components (CPU, RAM, storage) to parts of the human body, which made sense quickly. The boot process section — power on, firmware, bootloader, OS — didn't fully land yet.

Biggest Problem

Got stuck on Level 1 and Level 2 longer than expected, and the boot process explanation in the TryHackMe room didn't click.

Solution

Level 1: cat ./- instead of plain cat -. Level 2: tab-completion instead of typing the filename by hand, since it auto-escapes the spaces. Boot process: not solved yet — flagged to revisit before moving further into the Computer Fundamentals module.

Reflection

Two levels stalled me today where Day 1's single level didn't, which feels like the difficulty curve starting to show up already. Didn't skip the part I didn't understand just to mark the room complete — left it as an open item instead of pretending it's settled.

Tomorrow

Bandit Levels 4–6
TryHackMe "Computer Types" room
Revisit the boot process explanation


