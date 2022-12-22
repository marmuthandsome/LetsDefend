## Malicious VBA | LETSDEFEND

<img src="https://app.letsdefend.io/_next/image?url=https%3A%2F%2Fapi.letsdefend.io%2Fstatic%2Fimg%2FvbSource_3v68cm0.jpg&w=640&q=75" width="300px" align="center">

This is the link for the room [Malicious VBA](https://app.letsdefend.io/challenge/Malicious-VBA/)

Download the Malicious file -> [Virus](https://app.letsdefend.io/download/downloadfile/invoice.zip)

---
Let's go!

First you must download the file, after you downloaded the file open the file with notepad or notepad++

This is the spoiler for the file.

<img src="https://user-images.githubusercontent.com/67650329/193453128-e6d4a71e-2f74-4a33-bde8-f31acd08842f.png" width="500px" align="center">

We can see the Virus has Hex code. We can translate the Hax code with [CyberChef](https://gchq.github.io/CyberChef/)

And you can translate one by one until finish.

<img src="https://user-images.githubusercontent.com/67650329/193453396-44b6d564-f0f3-42ee-ade4-a80f8a162218.png" width="500px" align="center">

Note: You must see format answer {Answer}.

**The document initiates the download of a payload after the execution, can you tell what website is hosting it?**

**Answer: {https://tinyurl.com/g2z2gh6f}**

<img src="https://user-images.githubusercontent.com/67650329/193453471-381245a4-7042-4fa1-ad45-3ca899e44c44.png" width="500px" align="center">

**What is the filename of the payload (include the extension)?**

**Answer: {dropped.exe}**

<img src="https://user-images.githubusercontent.com/67650329/193453529-c9994659-c6df-403f-83c9-54d5bf7d01b6.png" width="500px" align="center">

**What method is it using to establish an HTTP connection between files on the malicious web server?**

**Answer: {msxml2.serverxmlhttp}**

<img src="https://user-images.githubusercontent.com/67650329/193453577-ab9e5a2f-b1f6-4b55-aa28-cf91ec506539.png" width="500px" align="center">

**What user-agent string is it using?**

**Answer: {Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.0)}**

<img src="https://user-images.githubusercontent.com/67650329/193453606-3fcfa1d2-9c90-461d-90e5-e24301d4c3c8.png" width="500px" align="center">

**What object does the attacker use to be able to read or write text and binary files?**

**Answer: {ADODB.Stream}**

<img src="https://user-images.githubusercontent.com/67650329/193453652-6a535139-d2b5-4998-be08-c3b9dc3f44fe.png" width="500px" align="center">

**What is the object the attacker uses for WMI execution? Possibly they are using this to hide the suspicious application running in the background.**

**Answer: {winmgmts:\\.\root\cimv2:Win32_Process}**

---
