+++
author = "Kevin Adrian Pillay"
title = "How to defend yourself against password attacks"
date = "2021-12-31"
description = "The importance of secure passwords"
tags = [
    "passwords",
    "security",
    "bruteforce",
]
categories = [
    "Passwords",
]
+++

In the digital world, password attacks have always been and will continue to be a common way for threat actors to gain access to your data. No matter how many methods we try to
make a good password, many users will continue to use the same basic passwords in multiple places simply because it's easier to remember. 

Let’s explore exactly how these password attacks work, as well as the most effective ways to reduce the risk of getting compromised or exposed on the internet.

## What are the different types of password attacks?

While the end goal of any password attack is to crack a user’s password to gain access, there are several different methods threat actors have at their disposal. 

### These are the most common ones:

- Dictionary Attacks – A dictionary attack begins with an attacker systematically trying every word in common language dictionaries like English, or Spanish for example, 
  to break into a system, relying on the tendency of people to use a single, real word as their passwords. However, as time has gone on, attackers have graduated 
  from only using a dictionary as their source to also using password or word lists that can be found on the internet. Password, 1234567, password1, 111111, and qwerty 
  remain popular favourites among end-users, unfortunately.
  
- Brute-Force Attacks – Unlike plaintext passwords in dictionary attacks, brute-force attacks use trial and error even more randomly, working through every combination of 
  letters, numbers, and symbols. These attacks benefit from the fact that most users keep their passwords short. The shorter the password, the faster these attacks 
  can work. These attacks generally aren't hard to do and can be done with penetration software. 
  Popular tools such as [hashcat](https://hashcat.net/hashcat/) and [John the Ripper](https://www.openwall.com/john/) are commonly used by both the good guys and bad.

- Hybrid Attacks – This is another form of password guessing, these attacks combine the power of dictionary and brute-force attacks, covering more possible combinations.

- Password Spraying – This s also called credential stuffing. Password spraying uses credentials stolen through social engineering attacks such as phishing and successful 
  results from dictionary, brute-force, or hybrid attacks. Taking a password that is known to work for at least one system or application, an attacker tries it across an 
  accounts of a user or company to see if it will work elsewhere, granting further access. Since passwords are reused by users so frequently, credential stuffing is often 
  very successful.

## Here are a few strategies for reducing the risk of a password attack

- Pentesting - A good way to know if your accounts or devices are vulnerable to password attacks is to launch one yourself with a pentest. An automated pentesting tool can be 
  used to run password attacks. For example, a password spraying scenario can be run to see if your device is vulnerable, thus exposing which machines are sharing credentials. 
  This gives you time to change the password before you are actually attacked and should prompt you to re-evaluate how your passwords are created and enforced.
  Many credential stuffing attacks begin with attackers that have already successfully stolen credentials through phishing attacks. You should always monitor any links opened, 
  clicked, or have credentials entered via email or websites. We must be more vigilant to avoid being vulnerable to phishing.

- Always use Multi-Factor Authentication (MFA) - MFA adds an additional roadblock in the way of attackers by requiring more than one piece of the puzzle in order to log in. 
  This requires knowledge, possession, and inherence. Essentially, this requires something only the user will know or have, like a password, something a user has, like a phone 
  or security token, and something only the user can provide, like a fingerprint or facial scan. The more requirements there are, the more work an attacker will have to do to 
  gain entry.

- Enforce a strong password policy - While MFA adds more protection, you need to be as secure as possible. For example, many types of MFA logins only request the second form 
  of authentication once the first has been validated. This means an attacker may not be able to gain access, but they will know they had the right credentials. From there, 
  they can launch a password spray attack on your other devices or accounts and may find something that doesn't have MFA and allows them access. This is why it’s important to 
  ensure that passwords are complex. Password managers can help by enforcing a strong password policy. Your passwords should consist of more than 12 characters, and contain 
  random numbers, symbols, and letters. Many businesses encourage the use of password phrases like s3cur1ty1sF*n! Which is generally easier to remember.

- Monitor your activity - Attackers usually rely on being undetected. You should occasionally check your logs for any unauthorized activity or failed password logins. This 
  usually means someone is trying to bruteforce attack your account. Consider setting up your device to automatically lock out a user after a certain number of failed attempts.

- Find time to learn about security - Try to read up about secure practices regularly, training on security ensures you understand both the importance of password security, 
  as well as new ways attackers can steal your credentials. Learn about ways to avoid being susceptible to phishing attacks, for example, learn how to better spot suspicious 
  emails and links.

### Finally, 

Your security posture and password policies should be done a regular basis to remain agile and refine security strategies as new techniques emerge. For example, MFA has only 
become mainstream in the last few years. With the right measures in place, passwords can remain one of the best and most important lines of defence for your life. 
