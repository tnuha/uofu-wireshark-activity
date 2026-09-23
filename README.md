# Wireshark Activity!

The activity for today is analyzing the packet captures in this repository
and some additional ones we'll have you capture yourself.

The following is a set of questions to answer:

## `httpforever.pcap`

This is a packet capture I took using `curl` while on the University of Utah
campus network.
Try and analyze the following:

- [ ] What website did I visit? (hint: this is related to the name of the file)
- [ ] What HTTP message did I send to the website?
- [ ] What HTTP message did the website send in response?
- [ ] Identify the data for this message. Was my message accepted?
- [ ] How many TCP messages were sent during my HTTP message?
- [ ] How many TCP messages were sent during the server's HTTP message?
- [ ] How did my laptop learn the IP address for the web server? Be as descript as possible.

## `utahedu.pcap`

This is a lot more involved due to the volume in number of messages.
We also hope that the previous section helped you with the forensics flow.
So, with the knowledge that this was captured again from my laptop on the
University of Utah network, answer the following questions:

- [ ] What website did I visit?
- [ ] How did my laptop learn the IP address for the web server? Be as descript as possible.
- [ ] Did this take "more" or "less" effort than the previous website? Elaborate on why.
- [ ] Obviously since I'm talking to a webserver, a web protocol should be involved, but HTTP is absent. Why?
- [ ] With wireshark capturing packets on your own machine, try and reproduce this exchange as much as possible. Check it off, and reason why the differences are what they are.

