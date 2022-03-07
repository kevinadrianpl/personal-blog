+++
author = "Kevin Adrian Pillay"
title = "Securing Linux against attacks"
date = "2022-01-09"
tags = [
    "antivirus",
    "linux",
    "security",
]
categories = [
    "Linux",
]
+++

At some point, most people believed that it was tough to break into Linux distributions but this assumption needs to change.

We are now all starting to realise that the malware-free experience they once had is quickly disappearing.
During the last few years, there has been an increase in malware, ransomware, and malicious code that targets Linux specifically. It has become known that Linux malware now accounts for more than one-third of all malware in existence. This means that Linux users can no longer continue with the assumption that only Windows is at risk for these malicious attacks. Linux attacks have tripled since 2016 and skilled attackers have identified easier methods to exploit Linux directly.

Let’s look at why Linux attacks are occurring more often and what you can do to prevent them:

### Assuming that Linux is safe is the wrong approach

There are many users who assume that their Linux system is untouchable and choose inaction over readiness. Think for a moment about Java and other cross-platform solutions that are designed to work on multiple systems. Consider the recent Java based malware like HEUR: Backdoor, it no longer matters which operating system you’re using. This can also be executed on Linux systems and cause significant damage.

Another example is the recent Log4j exploit known as Log4Shell, this affects Linux servers around the world as well as one of the worst exploits in recent history. 

Windows threats may be more common, but you can’t assume that Linux is more secure. Administrators may be unprepared to face the risks of their Linux systems and should take precautions.

### Having unpatched services and systems is asking for malware

Content management systems like WordPress have given users powerful tools to manage websites with modules and plugins making is easier to manage and update your website. Majority of these third-party tools hook directly into most permissions of your web server, including FTP read-write access. Some of these plugins are not always coded properly or securely, making these tools entry points for attacks. This means that patching web servers like Apache, or nginx does not always solve the problem. You must be aware of the weaknesses of the services running on top of other services you use, to ensure you are not vulnerable and are protected.

### Linux systems can infest other systems with viruses and malware

There are native viruses built for Linux machines, but Linux can also be carriers that can pass malware to other vulnerable systems in your network or remotely. Linux can also become a carrier for Windows based viruses. The only solution is to have an anti-virus installed and regularly updated, as well as signature files and behavior-based detection which a lot of anti-virus software can do these days, to look for and fix both types of threats, especially threats that live in a Linux filesystem.

### Any system can be targeted now

Whether it’s Windows, Mac, or Linux, files on any system are vulnerable to malware. Linux was never completely secure, today it is much less so because of the growing amount of threat actors out in the wild. Unpatched software, for example SSH and services like Apache and FTP, increase vulnerability. Regular updates and patching lower the risk of getting compromised, but people often see these critical tasks as optional and ignore notifications asking them to do so which can be a critical mistake. If updates are not performed out of concern for breaking an older app or just plain forgetfulness, you may get breached and suffer more damage.

### Use Linux-based scanners

To target UNIX-specific threats and to eliminate the risks of running scans across your entire network, you should instead use a local Linux-based scanning tool. This way you can avoid the hassle of failures and speed up scanning with local scanners that do not rely on networking. Linux tools are developed specifically for Linux, they use signature files and behavioral scanning designed to detect Linux-specific threats.

### Using Windows based tools on Linux can expose you

When you rely on Windows tools to scan Linux shares over a network, you can leave traffic exposed. Even though your team has access, you should know that some of the largest hacks were carried out by disgruntled employees seeking to do harm or looking to financially gain by either selling off information or credentials. You should not be paranoid though; you should keep the rule of least-privilege in mind and limit access to only those that need it.

### Automating the process

Consider automating the scanning process, native-OS malware scanning tools that can scan Linux hosts systematically to keep you informed will help you stay ahead of any breach.
It only takes one vulnerable machine or server with a few exposed ports for attackers to get into your network, so manually checking logs of machines may only work for the short-term, you cannot rely only on human analysis which is why automating these tasks can become useful.

You should consider tools like Ansible, Chef, and Puppet to advance your automation. Imagine how easy it would be to check for updates or search for older versions of Apache on your systems with a few simple lines of code. Open-source versions of these tools are available and can help you to keep updated with a documented trail.

### The importance of education

Threats and attacks are frustrating to system administrators, IT administrators and end users too, because they take time away from valuable work or personal time. Rather than shifting the blame, it is more productive to develop a culture of vigilance that rewards both you or your users for understanding threats and avoiding them rather than dismissing them without a second thought. Remember that you are taking the time to educate yourself and your users about best practices and warning signs to look at before a threat takes over, this will reinforce the importance of watchfulness and vigilance.

### Choose a proper anti-virus solution

Usually, not all antivirus solutions are created equally. Native antivirus for Linux is superior to a Windows based solution if you are using a Linux OS. There are such large differences between native antivirus tools that you need to take the time to research to make the right choice. Open-Source software may appeal to everyone at first glance because they are advertised as free but maintenance and set up requirements are usually more complex and cost more time and effort. Other critical factors you need to look at is ease of use, performance, detection rates, support, and scalability if you are using it in a business environment. You should be extra vigilant before planning.

## Becoming more secure starts right now

Linux has been so relied on as a reliable system capable of handling heavy duty tasks for enterprise servers in businesses. This is the reason it has become a legitimate target for threat actors. The data they store and the networks they support are so valuable that attackers have decided it is worth the time to invest in creating malware geared toward Linux. So rather than ignoring the reality of what it is, make sure you take the simple steps to help reduce your vulnerability and reduce your risk significantly.

### It will not just make your systems secure; it will make you secure
