---
title: "Google-Dorks"
date: 2024-02-21

---

### What are Google Dorks?

Google Dorks are the form of Google Hacking.
They use specially selected Google search operators (keywords) and words or sentences that we try to find on the website/websites.
This process might be used in the Reconnaissance phase of a penetration test.


### Google search operators

The below operators are some interesting operators that might be used to filter Google search results.

Operator | Meaning | Examples
--- | --- | ---
"" | Search for specific phrase | "GameBoy Color"
OR | Search for either one or second text | "GameBoy Color" OR "GameBoy Colour"
\- | Search for results that does contain specific phrase/word | "GameBoy Color" -amazon
\* | Wilrcard for any word | GameBoy *
allintext: | Search for results that contain all phrases | allintext:"GameBoy Color" "Nintendo DS"
intext: | s | s
allinurl: | s | s
inurl: | s | s
allintitle: | s | s
intitle: | s | s
site: | s | s
ext: | s | s
related: | s | s



Google Dork | Meaning
--- | ---
intitle:"scada login" "login" | lorem ipsum | lorem ipsum dolor | lorem ipsum dolor sit
intitle:"index of" scada | lorem ipsum dolor sit amet consectetur | lorem ipsum dolor sit amet | lorem ipsum dolor sit
site:wp.pl admin | lorem ipsum | lorem | lorem ipsum
site:onet.pl intitle:login | lorem ipsum dolor sit | lorem ipsum dolor sit amet | lorem ipsum dolor sit amet consectetur
site:onet.pl intitle:"index of"| lorem ipsum | lorem ipsum dolor | lorem ipsum dolor sit
inurl:"home?p_p_id" site:com | lorem ipsum dolor sit amet consectetur | lorem ipsum dolor sit amet | lorem ipsum dolor sit
site:.pl intitle:"Swagger UI" | lorem ipsum | lorem | lorem ipsum
site:wp.pl filetype:xml | lorem ipsum | lorem | lorem ipsum
site:pastebin.com intext:"*@credit-suisse.com" | lorem ipsum dolor sit | lorem ipsum dolor sit amet | lorem ipsum dolor sit amet consectetur