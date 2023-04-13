# CompTIA-Security-
Study Notes for the CompTIA Security+ Certification

CompTIA Security+ Notes
Social Engineering:
Phishing – When someone uses email or text to steal someone’s information/credentials
-	Typosquatting: A type of URL hijacking (ex. Gooogle.com, extra characters)
-	Pretexting: Pre thought story or prescripted scam
-	Pharming: Redirect a legit website to a fake website
-	When combing pharming + phishing: difficult for anti-malware software to stop (everything appears legitimate to the user).
-	Vishing: voice phishing over phone or voicemail (ex. Caller id spoofing, fake security checks or bank updates). 
-	Smishing (SMS phishing): done by text message (forward links, asks for personal information
-	Reconnaissance – gather information on the victim
-	Background information: lead generation sites, LinkedIn, Twitter, Facebook, Corporate web site
-	Attacker gathers information: where you work, bank, family/friends
-	Spear phishing – targeted phishing with inside information (makes the attack more believable)
-	“Whaling”: phishing the CEO (CFO or chief financial officeer is also speared)
-	Spam (emails), Spim (SMS messaging)
-	Watering Hole Attack: Large Website where most people use credentials
-	Dumpster diving – stealing physical information
-	Shoulder surfing – looking over shoulder steal information
-	Tailgating – 1 authorized person authenticates but 2 more people enters
-	 Outliers – Invoice scam (purchased scam), HOAX (misleading information), Prepending (modify URL, wrong information in URL).

Malware- Malicious Unauthorized code, executed on machine that does unauthorized affects
•	Virus – unauthorized code, attaches to host app/file/executable
o	Activated by the host
o	Virus Types:
	Macro – mini application (ex. small functions in a large application) 
	Boot-sector – infects boot up, harddrive SSD, takes over hardware
	Attachment – ex. Email
	File infector – downloadable files
	Polymorphic – slip under radar, constantly changes
	Network – virus comes in through a network.

•	Worms
o	Self-sufficient (no need host activation)
o	Self-replicating
o	Resource consumption (network bandwidth, storage, memory)
•	Fileless
o	Stealthy
o	Runs in memory
•	Rootkit
o	Takes control of computer
o	Privileged access
o	Difficult to detection
o	Low-level access
•	Keyloggers
o	Byproduct of malware
o	Capture keyboard input
o	Can be physical attacks (USB’s)
•	Backdoors 
o	Like a trojan
o	Software-based
	Malware
	Applications
•	Logic Bombs
o	Sits dormant.
o	Utilizes an event trigger
	Time
	Date
	Action/inaction
•	Ransomware
o	Crypto malware
o	Locks computer
o	Asking for payment in return
•	Bots
o	Collection of exploited devices
o	Trojans and RATs help to construct
o	Used in command and control or C2	
•	Trojan
o	Looks safe
o	Delivers malware
o	First step
o	Paves the way for keyloggers, RAT (remote access)
•	PuPs
o	Unwanted Software
o	Installer bundles


Password Attacks
	Used against authentication systems
	Automates the process

	Brute Forces Attack (slow time)

o	Guessing attack
o	Every possible combination
	0000
	0001
o	Dictionary
	Brute force type attack
	Uses large dictionary list
	Rainbow Tables (medium time)
o	Use precomputed chains (calculations done ahead of time)
o	Chains are stored in tables
o	Time reduction
o	Tables can be vary large files
	Spraying
o	Cracking multiple accounts at once
	Adding Salt
o	Random data added to a password when hashing (doesn’t work with rainbow tables)
	Salting the Hash
o	Each user gets a different random hash
	Storing Passwords
o	Use a hash (fixed-length string of text)
o	One-way trip (can’t be reversed, original password is gone)
o	SHA-256 hash algorithm
Physical Attacks
•	Malicious USB cable, OS identifies it as a HID (Human Interface Device)
o	Cable takes over once plugged in (downloads and installs malware)
•	Malicious flash drive
o	Older OS would automatically run files
o	Could still act as a HID/keyboard
o	Attackers can load malware in documents (pdf files, spreadsheets)
o	Can be configured as a boot device
o	Acts as an Ethernet adapter
•	Skimming
o	Stealing credit card information
	Copy data from the magnetic stripe (card number, exp date, name)
o	ATM skimming 
	Includes a small camera to watch for your pin
o	Card Cloning
	Get card details from a skimmer (clone original card)
	Only magnetic stripe works, chip can’t be cloned
Adversairal Artificial Intelligence
•	Machine Learning
o	Computer identify patterns in data and improve their predictions
o	Requires a lot of training data
o	Ex. Stop spam, recommend products or movies
•	Poisoning the training data
o	Confuse the AI, attacker sends modified training data
•	Evasion attacks
o	AI is only as good as the training
o	Attacker finds holes and limitations
•	Securing the learning algorithm 
o	Check training data
o	Constantly retrain with new data





