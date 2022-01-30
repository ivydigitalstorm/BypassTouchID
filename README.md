# Bypass TouchID w/ a Forged Fingerprint
#### Find enclosed a reproducible lecture and lab documenting the tools and techniques I used to create a hi-resolution skin-like forgery capable of bypassing iPhone 7,6s,6,5s TouchID fingerprint biometric sensors, with a source latent fingerprint lifted from the surface of iPhone itself. 
## overview
When Chaos Computer Club disclosed their methods in 2013 I found they did not work according to the documentation on the website.  This kinda drove me nuts, so I kept working at it, reverse engineering the few tidbits that starbug did toss online, and doing some deep technological soul search until I found a good methodology -- I created my own by piecing together various pieces of tradecraft, and revising processes throughout most of 2014.  

Trials to proof efficacy of methods were held at PSU Mac Admins Conference in 2015 for a small academic audience - 100 participants! The results sampled demonstrate a significant quality to the process. This was a particularly difficult piece of research to release, demonstrated by the timeline, where research efforts were largely undertaken in 2014, with methodology proposed for academic disclosure in January 2015. What year is it now? In sum, I'm grateful to be able to offer this knowledge freely today. 

## Security Recommendation

#### The Future
What points can be scanned from our body to be used for biometric discovery?

Fingerprint authentication was broken in the 1970's, and since then not a thing is changed.  Future biometric authentication technologies are actively under refinement, and open source technologies such as Apple ResearchKit and HealthKit applications for behavioral analysis by way of device onboard sensors will enable implementation of the next biometric authentication wave: Active Authentication. Active authentication is where your devices know who you are through active measurements of your behavior.  

#### Today
Consumer TouchID users are recommended to keep calm and carry on; the combination of iOS Security Policies including TouchID is reasonable to provide security.  It is recommended to government enterprise TouchID users not to use fingerprint biometric authentication checkpoints at any perimeters, ever.  Security paranoid TouchID users who are travelling OCONUS may want to power off their device when crossing borders. ;)

Interestingly of note, the latent print in this study is scanned at 4800 dpi, printed at 300 dpi, where fingerprints in repositories such as IAFIS and SWIFT (for example) are imported at 500 dpi, and the TouchID sensor is 600dpi.

## Some fun
Researcher @ivydigitalstorm and assisting analyst @quovadimus additionally videodocumented an evening lab session which resulted in generation of 75 high quality fingerprint templates developed and processed in one evening.  Now think of the mischief that could cause!

## For the hacker community
This is a super fun lab to run and share, and I'd like to get it out there - maybe for DEF CON or another conference through the Hacker Women effort. Want to assist? DM [@HackerWomen](https://twitter.com/hackerwomen) on Twitter. 

## Contents:
Lab
1. [Forged Fingerprint Lab v1.0 (source)](https://github.com/ivydigitalstorm/BypassTouchID/tree/master/Bypass_TouchID_Lab)
1. [Forged Fingerprint Lab v2 beta (work in progress)](https://github.com/ivydigitalstorm/BypassTouchID/tree/master/Bypass_TouchID_Lab)

Slide Deck
1. [Forged Fingerprint Slidedeck - Methodology Only](https://github.com/ivydigitalstorm/BypassTouchID/blob/master/_WS02-01-Bypass_Touch_ID_With_A_Forged_Fingerprint_-_Ivy_Thomas.pdf)
1. [Forged Fingerprint Slidedeck - Methodolody & iOS Software and Hardware Security Implementations (PSU MacAdmins Deck)](https://github.com/ivydigitalstorm/BypassTouchID/blob/master/_PSU_2015-Bypass_TouchID_With_A_Forged_Fingerprint-J_Ivy_Thomas_v1.pdf)

Video
1. [POC or GTFO](https://www.youtube.com/watch?v=pUdTUau0pCE)
2. Fingerprint Forgery Lab Sessions (in progress)

::note::
**this is a first-repository effort** please be gentle while i navigate github and creative commons licensing to provide community editable lab documentation //cheers
