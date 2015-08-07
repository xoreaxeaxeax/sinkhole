# The Memory Sinkhole
As [presented at BlackHat 2015](https://www.blackhat.com/us-15/briefings.html#the-memory-sinkhole-unleashing-an-x86-design-flaw-allowing-universal-privilege-escalation) this is an x86 design flaw that allows ring -2 privilege escalation.

* sinkhole.asm contains the proof of concept APIC overlay attack.
* Coming shortly:
  * Loadable kernel module for deploying the ring -2 rootkit through the sinkhole
  * (Benign) SMM rootkit sample

(Currently working on the "benign" part)
