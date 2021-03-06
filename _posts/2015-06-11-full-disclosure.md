---
layout: post
title: Full Disclosure
subtitle: "Before we get to the goods"
cover_image: skyking1.png
excerpt: "Before we start talking about the project - let's clear the air and understand who is running these tests."
author:
  name: John Stauffacher
  twitter: g33kspeed
  gplus: 115459133183253104599
  bio: Defensive Security Expert
  image: js.jpg
---
<span class="firstLetter">T</span>esting on this scale has been not only fun, but incredibly challenging. It is important to understand the background of the ones doing the tests so you can understand the bias that is brought to the test. Every test has bias - it is in our nature as humans to draw upon our life expieriences when analyzing any given data set. This should not be construed or misrepresented as extending my availability for employment, though this may seem to some to look like a CV, in all reality, I'm pretty good where I am, and I only put this out here to give context to the testing.

* Security Architect with a large national consulting firm
* Red Team Member Western Regional Cyber Defense Competition (WRCCDC)
* Bug Bounty Participant
* Actively involved in research and contribution to _Active Defense_ 

* Things I have broken:
	+ I've gotten root on a light bulb, crock pot, and soon an egg tray
	+ Once pwned a client with nothing more than using their own administrative tools ( Solarwinds etc)
	+ A bunch of other things, that I can't really state publicly ;-)
* Things I have built:
	+ Have provided Web Application Firewall consultation, and deployment to various Fortune 500,100, and 50 clients - including major companies in the Financial Services vertical
	+ Deployed an SEIM solution for a major international company in the Oil sector.
	+ Deployed NGFW solutions for a major company in the Energy sector.
* Things I have defended:
	+ Served as the Networking lead for a University in Southern California for over 5 years
	+ Served as the Networking and Security lead for a major international automobile manufacturer for over 5 years
	+ Served on security teams in both commercial banking and merchant processing

#Time and Compensation
<span class="firstLetter">T</span>he entirety of this project was done on my own off time. Long nights and weekends were spent developing the test plans, as well as actually performing the tests. I was not compensated by any of the companies in this report for this work.

#Licenses and Costs
<span class="firstLetter">A</span>ll the Anti-Bot software used in this test were licensed accordingly:

|Product          | License                                                      |
|-----------------|--------------------------------------------------------------|
| F5 ASM          | Personally paid for the $98 lab license from CDW             |
| Imperva         | Imperva SecureSphere OneBox VM available to Imperva Partners |
| Distil Networks | Temporary 'Introductory' VM license                          |

The various other software used during these tests will be listed on their respective pages. Any premium services beyond trial software used within it's trial limitations was purchased by the researcher.

#Thanks
<span class="firstLetter">P</span>rojects like this don't go down with a lot of help and contributions from many. During the course of this engagement the following companies and indivudals helped me out in one way or another:

##Caffeinated Networks [{% image cafnet-logo.png alt="Caffeinated Networks Logo" width=180 height=180 %}](http://www.caffeinatednetworks.com) &nbsp; &nbsp; 
<span class="firstLetter">T</span>he guys at CafNet went out of their way to help me out with this project. At one point the team was able to overnight a barn find server from across the US to provide the power needed to run these tests. If you get a chance hit these guys up. Send an email out to [Matt](mailto:matt@cafnet.in?subject=SuperionAir) and let him know what you think. The team at CafNet are awesome at putting together complex networking and infrastructure projects. I don't think I could have pulled this test off without their help and resources. Their website doesn't do justice all the work these guys continue to pull off.

##OJ (@thecolonial) at [{% image beyond-binary-logo.png alt="Beyond Binary Logo" width=180 height=41 %}](https://beyondbinary.io) 
<span class="firstLetter">N</span>ot only has OJ provided countless hours of entertainement keeping me awake at night. He also is the mastermind behind [GoBuster](https://github.com/OJ/gobuster/) an awesome tool for HTTP fuzzing and testing. 

##LoadImpact [{% image loadimpact-logo.png alt="Load Impact Logo" width=180 height=29 %}](http://www.loadimpact.com) 
<span class="firstLetter">L</span>oadImpact is one of the few load testing tools that is extremely flexible, low cost and easy to use. This tool saved us hours in configuration and testing time. 
##The Vendors
F5, Imperva, Distil: A huge thanks out to the vendors. 
