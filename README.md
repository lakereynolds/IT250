# IT250
Open the 802.1x packet capture https://www.cloudshark.org/captures/b84338df257fLinks to an external site.

What is the supplicant’s id?
What type of challenge is being requested by the authenticator?
Open the EAP-TLS packet capture using Wireshark

eap-tls.pcapDownload eap-tls.pcapOpen this document with ReadSpeaker docReader

Filter the EAP packets and inspect the IEEE 802.11 data layer

What is the supplicant/user device name, MAC address, and ID?
What is the authenticator/access point name and MAC address?
Filter the TLS packets and look at the TLS Record Layer inside EAP layer to see the certificates of user device and the authentication server

What is the subject name of the supplicant and the authenticator?
What is the name of issuer/CA?

Answers:
1. id: 9

2. 5D5-Challenge EAP

3. Intel_d2:5e:a8 (24:77:03:d2:5e:a8)

4. Buffalo_0e:33:3c (10:6f:3f:0e:33:3c)

5. supplicant: perryMordor authenticator: radiusMordor

6. Mordor
