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
-	Virus – unauthorized code, attaches to host app/file/executable
-	Activated by the host
-	Virus Types:
-	Macro – mini application (ex. small functions in a large application) 
-	Boot-sector – infects boot up, harddrive SSD, takes over hardware
-	Attachment – ex. Email
-	File infector – downloadable files
-	Polymorphic – slip under radar, constantly changes
-	Network – virus comes in through a network.

•	Worms
-	Self-sufficient (no need host activation)
-	Self-replicating
-	Resource consumption (network bandwidth, storage, memory)
-	Fileless
-	Stealthy
-	Runs in memory
-	Rootkit
-	Takes control of computer
-	Privileged access
-	Difficult to detection
-	Low-level access
-	Keyloggers
-	Byproduct of malware
-	Capture keyboard input
-	Can be physical attacks (USB’s)
-	Backdoors 
-	Like a trojan
-	Software-based
-	Malware
-	Applications
-	Logic Bombs
-	Sits dormant.
-	Utilizes an event trigger
-	Time
-	Date
-	Action/inaction
-	Ransomware
-	Crypto malware
-	Locks computer
-	Asking for payment in return
-	Bots
-	Collection of exploited devices
-	Trojans and RATs help to construct
-	Used in command and control or C2	
-	Trojan
-	Looks safe
-	Delivers malware
-	First step
-	Paves the way for keyloggers, RAT (remote access)
-	PuPs
-	Unwanted Software
-	Installer bundles


Password Attacks
-	Used against authentication systems
-	Automates the process

-	Brute Forces Attack (slow time)

-	Guessing attack
-	Every possible combination
-	0000
-	0001
-	Dictionary
-	Brute force type attack
-	Uses large dictionary list
-	Rainbow Tables (medium time)
-	Use precomputed chains (calculations done ahead of time)
-	Chains are stored in tables
-	Time reduction
-	Tables can be vary large files
-	Spraying
-	Cracking multiple accounts at once
-	Adding Salt
-	Random data added to a password when hashing (doesn’t work with rainbow tables)
-	Salting the Hash
-	Each user gets a different random hash
-	Storing Passwords
-	Use a hash (fixed-length string of text)
-	One-way trip (can’t be reversed, original password is gone)
-	SHA-256 hash algorithm
Physical Attacks
-	Malicious USB cable, OS identifies it as a HID (Human Interface Device)
-	Cable takes over once plugged in (downloads and installs malware)
-	Malicious flash drive
-	Older OS would automatically run files
-	Could still act as a HID/keyboard
-	Attackers can load malware in documents (pdf files, spreadsheets)
-	Can be configured as a boot device
-	Acts as an Ethernet adapter
-	Skimming
-	Stealing credit card information
-	Copy data from the magnetic stripe (card number, exp date, name)
-	ATM skimming 
-	Includes a small camera to watch for your pin
-	Card Cloning
-	Get card details from a skimmer (clone original card)
-	Only magnetic stripe works, chip can’t be cloned
Adversairal Artificial Intelligence
-	Machine Learning
-	Computer identify patterns in data and improve their predictions
-	Requires a lot of training data
-	Ex. Stop spam, recommend products or movies
-	Poisoning the training data
-	Confuse the AI, attacker sends modified training data
-	Evasion attacks
-	AI is only as good as the training
-	Attacker finds holes and limitations
-	Securing the learning algorithm 
-	Check training data
-	Constantly retrain with new data





