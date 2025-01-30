# Article
https://samcurry.net/hacking-subaru?utm_source=tldrdevops
## Summary
This article outlines a major security vulnerability in Subaru's STARLINK program that revealed customer data within the US, Canada, and Japan. The authors of this article were able to uncover location data, exporting a year's worth of location history, and add themselves as an authorized user on a friend's Subaru, allowing them to remotely unlock the car. They did all of this without needing any confirmation from the actual owner. Subaru patched the vulnerability within 24 hours before it was able to be exploited maliciously. 
While this article is more related to information security than SWE specifically, it does highlight how seemingly simple actions like finding exposed JavaScript files can lead to major security breaches, and emphasizes the importance of securing even the smaller parts of a system.   

### Comment by Nikita Bhaskar
This incident underscores how even small oversights in software security, like exposed JavaScript files, can lead to severe real-world consequences. It’s a stark reminder that security should be a fundamental consideration at every stage of development, not just an afterthought.

### Comment by Shamaamah Ahmad
One thing I found interesting was how the vulnerabilities were interconnected, allowing relatively small issues to escalate into critical issues. It’s a fascinating reminder of how even seemingly minor security gaps can have a big effect when they intersect. This highlights the importance of a holistic approach to system security, not just addressing isolated problems but understanding the bigger picture.
