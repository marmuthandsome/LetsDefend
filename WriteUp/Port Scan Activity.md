## Port Scan Activity | LetsDefend

<img src="https://app.letsdefend.io/_next/image?url=https%3A%2F%2Fapi.letsdefend.io%2Fstatic%2Fimg%2Fpirate_zyeX8zj.jpg&w=640&q=75" width="300px" align="center">

This is the link for the room [Port Scan Activity](https://app.letsdefend.io/challenge/port-scan-activity/)

Can you determine evidences of port scan activity?

Log file: https://api.letsdefend.io/download/downloadfile/port%20scan.zip Pass: 321

Note: pcap file found public resources.

---

Tools:

- [WireShark](https://www.wireshark.org/)

### Question 1

**What is the IP address scanning the environment?**
```
1	0.000000	***	10.42.42.50	TCP	74	46104 → 80 [SYN] Seq=0 Win=5840 Len=0 MSS=1460 SACK_PERM TSval=3299940 TSecr=0 WS=64
```

### Question 2

**What is the IP address found as a result of the scan?**
```
1	0.000000	10.42.42.253	***	TCP	74	46104 → 80 [SYN] Seq=0 Win=5840 Len=0 MSS=1460 SACK_PERM TSval=3299940 TSecr=0 WS=64
```

### Question 3

**What is the MAC address of the Apple system it finds?**
```
Ethernet II, Src: Apple_92:6e:dc (***), Dst: QuantaCo_82:1f:4a (00:23:8b:82:1f:4a)
```

### Question 4

**What is the IP address of the detected Windows system?**
```
1	0.000000	***	10.42.42.50	TCP	74	46104 → 80 [SYN] Seq=0 Win=5840 Len=0 MSS=1460 SACK_PERM TSval=3299940 TSecr=0 WS=64
```

Thank you for reading 👋.

---
