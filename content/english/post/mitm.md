+++
author = "Kevin Adrian Pillay"
title = "What is a Man-in-the-Middle attack?"
date = "2022-01-06"
tags = [
    "mitm",
    "man-in-the-middle",
]
categories = [
    "Man-in-the-Middle",
]
+++

What is a Man-In-The-Middle attack, how does it work, and how can I protect myself?
Man-in-the-Middle (MitM) attacks are when one website steps in-between you and a legitimate website so that whatever you do on the legitimate website can be seen and stolen by the attacker who owns the site in the middle. 

## Attackers take over the Domain Name System (DNS) server that tells your browser where to find websites online. 

This is when you type a URL into your browser, then the browser goes to a DNS server provided by your ISP that tells your browser where to find the websites. If an attacker were to take over the site listing in a DNS server, the DNS record, or the entire DNS server itself, it could re-route you to a different site that looks and acts like the site you wanted to go to. 
 
## MitM attacks can go further than simply re-routing you to a fraudulent site. 

These attacks start the same but instead of serving you a site of their own, they simply record all the information you're sending/receiving on the original site. So, if you went to your bank's website, you wouldn't see anything different at all. You'd send your details to the bank, which the attacker would intercept and then pass on to the bank. The bank would send back your information, which the attacker would save and then pass back to you. You don't see it happening, but the attacker now has a copy of all that information and can use it for whatever they want. This type of attack is much more difficult to pull off but is more successful since both sides see exactly what they expect to see the entire time.

So how do you protect yourself against it? This is difficult because you don't have direct control over the DNS servers. They're managed by groups on the internet, including the websites themselves, your ISP, your IT department, and many others. If they get compromised by an attacker, there's no way for you to be able to see that until it's too late. There are ways you can make it a lot harder for MitM attacks to work, and to defend yourself against them:

### - Always use https: when possible. 

Many websites used to use the unsecured http: protocol to send and receive data. Banks and other security-focused companies used secured https: but it's more complex and expensive to maintain; so most sites didn't use it. Over the last few years, most websites have started using it because of all and attacks that have been going on. Make sure that your browser shows the URL with https:// and that you have a green padlock icon in the address bar, that means the connection has been secured. Since secure connections require that both ends must agree on secure properties known as certificates, an attack would usually fail as the server in the middle can't match either side's certificate and cannot establish the secure link. It is extremely difficult for this to fail if you keep your system updated and the website, you're visiting does the same.
 
### - Always keep your system, your browser, and any apps you use on your desktop, laptop, and smartphones updated. 

Attackers always find ways around MitM mitigation, that is why software is updated to overcome the attackers. While you can't force the website, you're visiting to stay updated, keeping your side up to date can stop most attacks.
 
### - Don’t change settings if you don’t understand them, reach out to an expert. 

Changing settings by using unauthorized VPN systems, TOR browsers, or other tricks may seem to make your day go easier; or help you find restricted information but could also open you up to MitM attacks. Be careful when signing up to newsletters on websites. Sometimes their website is fine, but mailing lists get compromised. 

While it may not be possible to stop every attack, websites and companies like Microsoft, Apple, Samsung, Google, and others are working to make sure the attacks don't work or are stopped from working quickly. Your ISP is also keeping a close eye on anyone trying to attack your DNS servers. Always keep your systems updated and don’t fall prey to phishing and you should be fine.
