---
title: "Google Dorks"
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
"" | Search for a specific phrase | ["GameBoy Color"](https://www.google.com/search?q=%22GameBoy+Color%22&oq=%22GameBoy+Color%22)
OR | Search for either one or another text | ["GameBoy Color" OR "GameBoy Colour"](https://www.google.com/search?q=%22GameBoy+Color%22+OR+%22GameBoy+Colour%22)
\- | Search for results that does contain specific phrase/word | ["GameBoy Color" -amazon](https://www.google.com/search?q=%22GameBoy+Color%22+-amazon)
\* | Wildcard for any word | [GameBoy \*](https://www.google.com/search?q=GameBoy+%2A)
allintext: | Search for results that contain all phrases | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
intext: | Search for a specific word in a text | [intext:"Nintendo US"](https://www.google.com/search?q=intext%3A%22nintendo+us%22)
allinurl: | All words occur in a URL | [allinurl:nintendo us](https://www.google.com/search?q=allinurl%3Anintendo+us)
inurl: | Search for a concrete word or a phrase in a URL | [inurl:NintendoGame store](https://www.google.com/search?q=inurl%3ANintendoGame+store)
allintitle: | All words occurs in a title | [allintitle:Xbox store](https://www.google.com/search?q=allintitle%3AXbox+store)
intitle: | A word or a phrase occurs in a title | [intitle:"GameBoy Color" shop](https://www.google.com/search?q=intitle%3A%22GameBoy+Color%22+shop)
site: | Search for a specific word or a phrase on a specific website | [site:allegro.pl T-shirt](https://www.google.com/search?q=site%3Aallegro.pl+T-shirt)
ext: | Search for a website or a file with a specific extension | [ext:pdf "GameBoy Color"](https://www.google.com/search?q=ext%3Apdf+%22GameBoy+Color%22)
related: | Search for results related to a specific website | [related:amazon.com](https://www.google.com/search?q=related%3Aamazon.com)

### Google Dorks

The below Google queries are interesting Google Dorks that may help us retrieve interesting or data leakage.

Google Dork | Meaning
--- | ---
intitle:"scada login" "login" | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
intitle:"index of" scada | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:wp.pl admin | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:onet.pl intitle:login | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:onet.pl intitle:"index of"| [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
inurl:"home?p_p_id" site:com | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:.pl intitle:"Swagger UI" | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:wp.pl filetype:xml | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
site:pastebin.com intext:"*@credit-suisse.com" | [allintext:"GameBoy Color" "Nintendo DS"](https://www.google.com/search?q=allintext%3A%22GameBoy+Color%22+%22Nintendo+DS%22)
