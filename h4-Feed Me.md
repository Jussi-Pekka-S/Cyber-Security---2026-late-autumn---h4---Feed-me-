x) Why would you want to use a feed reader (and RSS/Atom)? Couldn't you just browse to each website? 
(This task does not require tests with a computer. Find suitable sources yourself if needed.).
- Yes, you can use browser to each website, but the feed reader is more efficient with the workflow than going through sites.
- RSS/Atom can be used to collect updates automatically:
- for an example to follow 30 sites through one feed reader and not separate sites.
- Can be used to organize sources: Infrastructure, AI, Cybersecurity to name a few.
- They show what is new automatically, so the user does not need to remember what has been read.

y) Supreme court of Finland, [case Osuuspankkikeskus port scan KKO:2003:36](https://www.finlex.fi/fi/oikeuskaytanto/korkein-oikeus/ennakkopaatokset/2003/36)
Have a brief look, summarize the key thing in a couple of bullets or sentences.
- Person used a computer program that was capable of searching for open proxy servers.
- This activity was used to target the IT-System of Osuuspankkikeskus-OPK.
- User did not access the system, but Supreme Court concluded that the user could have.
- In this case the software that was being used and under the circumstances, the activity was taken as a part of an attempted intrusion.
- The connection originated from the person's IP-adress.
- In this case no "malicious objective/motivation" was required, because:
- Unauthorized entry to an information system does not require some particular additional objective.
- The person was 17-years old, but Supreme Court decided not to reduce the damages in this case.
- It is important to remember that: "nothing happened" and "nothing got through the firewall" are not the sambe thing.

a) Install a feed reader. Show that it can read a feed (RSS or Atom). Include a screenshot of this
- I installed the Thunderbird
 <img width="768" height="1024" alt="863f1bc4-29c0-4424-9f7a-ce14ca682994" src="https://github.com/user-attachments/assets/92634714-1b63-4146-98c5-3d5409548f63" />
<img width="768" height="1024" alt="fd0939cb-4d9d-45e8-b6da-302c93e84bf4" src="https://github.com/user-attachments/assets/31e146e9-2837-46ce-9977-174283d47a90" />
<img width="768" height="1024" alt="8abb6eea-48e7-4c25-9e02-40f393cec622" src="https://github.com/user-attachments/assets/6e11e72b-52ac-484e-a787-b6d0d259cf3e" />

b) Add the feed for Krebs. https://krebsonsecurity.com/feed/
- Check the picture on part C, that shows Krebs on Security as added.

c) Add a feed for Schneier on Security. Find the blog, and locate the feed.
- Schneier on Security + the Krebs on Security
<img width="768" height="1024" alt="b3957937-49b5-419e-8bde-2e4da24d80b3" src="https://github.com/user-attachments/assets/e75aa169-f98f-40ca-9548-0d549125c9e9" />

d) Find and add two more security related feeds. Explain how you found them, and why you chose them.
- Cisco Talos Blog (https://blog.talosintelligence.com/rss/)
<img width="768" height="1024" alt="7f31dac5-242b-4843-91f5-96e672f0e372" src="https://github.com/user-attachments/assets/4709d340-7c06-4b2f-ab91-b4ddb38b6f00" />
<img width="768" height="1024" alt="2346e4a7-bee9-4b84-9ac0-c9081b130bac" src="https://github.com/user-attachments/assets/a4f8ad08-e504-4683-bfa1-1a7b25a08c9a" />

- SANS Internet Storm Center (https://isc.sans.edu/rssfeed_full.xml)
<img width="768" height="1024" alt="bf6bfd8d-049d-45af-bef8-7fe46edc0743" src="https://github.com/user-attachments/assets/39334f1a-4e42-42f0-a507-6cc62663eb75" />
<img width="768" height="1024" alt="3a2306ce-b74b-4830-b54b-210a0b5ddde1" src="https://github.com/user-attachments/assets/060ef83f-29d1-4d80-b27c-2a197a4cd759" />

- I was just browsing the internet and looking for feeds that would fit this purpose, and I think these two would fit the picture.

e) Follow security feeds for a while. What did you learn? 
What are the benefits and downsides of following feeds with a reader, compared to some other methods of following cyber security scene?
- Schneider on security is about security with different aspects like privacy, AI, policy, surveillance.
- Krebs is about cybercrime ecosystems, ransomware groups, fraud, breaches and the infrastructre & people behind attacks.
- SANS gives observations that are operational considering new threats, defensive concerns and suspicious network activity
- Cisco Talos Bloc is about operations and research. With subjects like incident-response trends, threat actors, Snort coverage and malmware analysis.
- Benefits are for an example: Better coverage that needs less manual work, good signal preservation, the disclosure to publishers is minimal, user-controlled information stream.
- Downsides are for an example: Security feeds are only as good as the sources that are selected, Some feeds might be inconsistent, volume might become too big.

f) Port scan. How can criminals know what services your employer has?
Disconnect your computer from the internet while doing the test (after you have installed the required software). 
Do the test inside your virtual machine.

Install nmap port scanner
<img width="768" height="1024" alt="ccfb7691-f9bd-4444-a715-013a21527607" src="https://github.com/user-attachments/assets/ee690fea-2113-41e1-8b03-4801e391a577" />

Disconnect from the internet. Show that 'ping 8.8.8.8' stops working when internet is disconnected.
<img width="768" height="1024" alt="9475e450-e11e-4822-a3a2-dfaa853b2ff3" src="https://github.com/user-attachments/assets/239dfbf2-3c8a-4487-9d1f-d6a3705b1efc" />

Port scan your own computer. Use "localhost" as the address.
<img width="768" height="1024" alt="61912a20-450d-4f3f-916e-2594f47c1c9b" src="https://github.com/user-attachments/assets/acd57ea1-c1bf-4506-8738-80368f6b800a" />


Install a daemon
- Unfortunately this was out of my reach, as I tried this but did not succeed.
<img width="1024" height="768" alt="7fdc12bf-037e-4e7b-866e-dbe2cc8effba" src="https://github.com/user-attachments/assets/f629269d-d81f-4b16-a11c-71c289b9e58c" />

Port scan again
- Did not succeed, as the daemon was out of my abilities. 

Analyze and explain the results
- Well the localhost was offline, so the uptime is 0.00 days.
- Network distance is also 0 hops, because of the localhost.
- IP ID Sequence is all zeroes as well, because of offline status.
- TCP Sequence Prediction difficulty was 261 (Good luck!), so it means that these are very hard to read for the invader.
- It read all the files from the computer and nmap read the IP adress + send packages.

g) Voluntary bonus, a bit hard: Identify a port scan against Apache on the host being scanned, e.g. in logs. Perform the test against "localhost" address and disconnect the internet while port scanning.
- I tried to add Apache, but did not succeed. Check pictures
<img width="768" height="1024" alt="2e1d84a3-e25b-4066-83bf-9082698dbd45" src="https://github.com/user-attachments/assets/320c531d-aa43-4c59-9cec-d7ac37d8304a" />
<img width="768" height="1024" alt="3a052017-fcfa-409f-b7ea-cddc2ad8ceaf" src="https://github.com/user-attachments/assets/805cee23-7aa9-4edf-a69f-75f20a3c4690" />

SOURCES:
https://www.finlex.fi/fi/oikeuskaytanto/korkein-oikeus/ennakkopaatokset/2003/36
https://terokarvinen.com/cyber-security/#homework
https://krebsonsecurity.com/
https://blog.talosintelligence.com/rss/
https://isc.sans.edu/rssfeed_full.xml
