# The Memory Sinkhole
An x86 design flaw allowing ring -2 privilege escalation.

* sinkhole.asm contains the proof of concept APIC overlay attack.
* Coming shortly:
  * Loadable kernel module for deploying the ring -2 rootkit through the sinkhole
  * (Benign) SMM rootkit sample

(Currently working on the "benign" part)

# Security Advisories
* Intel @ https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00045&languageid=en-FR
