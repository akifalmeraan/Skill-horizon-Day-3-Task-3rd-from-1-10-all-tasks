Task 1) Deliverables
Doman:- example.com
Registrar:- whois.iana.org and id:- 376
Creation date:- 1995-08-14to4 
Expiry date:- 2026-08-13to4
NS:- IANA-SERVERS.NET


TASK 2) 
A record:- 23.215.0.136 to 23.192.228.84
NS record :- iana-servers.net
MX record:- NA Skill-horizon-Day-3-Task-3rd-from-1-10-all-tasks
Performed information gathering of domain and subdomains, emails and metadata extraction etc etc


TASK 3) Emails found 1) email.example.com
2) info@example.com
3) mail@example.com
4) you@example.com
5) them@example.com
6) me@example.com


TASK 4) Extracted metadata information of Osmania University
1) Time table pdf
2) extracted metadata by using (exiftool metadata.pdf) command
3) Tools used :- exiftool



TASK 5 Google dorks attempted
RESULTS
1) site:hackthissite.org filetype:pdf 
Result:- YES
2)  site:hackthissite.org filetype:docx
Rsult:- No
3)  site:hackthissite.org filetype:loh
Result:- No
4)  site:hackthissite.org filetype:sql
Result:- No
5)  site:hackthissite.org intitle:"index of"
Result :- Yes
6)  site:hackthissite.org inurl:login
Result :- Yes
7)  site:hackthissite.org ext:bak
Result:-No


Task 6) Social media and OSINT(employees and public info)
1)  The founder of HackThisSite.org is
Jeremy Alexander Hammond. He created it in 2003, and is also known by the online moniker "sup_g".
2) Specific Department Emails

    a)Advertising: advertising@hackthissite.org 
    b)Donations: donate@hackthissite.org

3) HACKTHISSITE.ORG :- A staff operates as a group, and it is this collective "HackThisSite Staff" that maintains the website.
4) Contact methods

    Email: hackbloc@gmail.com
    IRC: irc.hackthissite.org on the #hackbloc or #hackthissite channels, SSL port 7000
    Discord: Join their official server
    Forums: Visit their online forums for discussions
    Postal Mail: Hack This Site, 412 N. Main St. STE 100, Buffalo, WY 82834 



TASK 7) URLs & LEAK DATA IN JS FILES.

1) Found api key of booking.com in gtihub
   api_key:eyJrIjoiT0tTcG1pUlY2RnVKZTFVaDFsNFZXdE9ZWmNrMkZYbk@localhost:3000/api/org

2) SECRET KEY:- AWS_SECRETS_ACCESS_KEY = 'uvvr0ZTkimd7nLKxAZWr+k53spkrCn5DUNYB1Wrk'


3) JS url
   js urls - Google Search</title><script nonce="1wBwPI7ywJTNd1cqaCA9LA"
   



TASK 8) Identifying possible secrets(leak) from passive recon


1) https://www.google.com/xjs/_/js/k=xjs.s.en_GB.xrFV_MEa130.2019.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEACAAAEAgAIBAAQAAAAAAAAAAAhAAHgAAAAAAAAAAAAAAAAAAAAAAAAABAQAAACABgAAAAAAAAAAAAAAAIAAABAAAAAAAAAAAAaAAABAAAEFAAAAFAAAAAAAAAAAAAAAAAAJEAAAAAAQSIAEAPhvf0ADAAAAAAAAgAAAAAAAAAAAAAAAAIAIAAAAAAAAAFgAABAUBgAgACGAAAAAAAAAAAAAAAAAAAAEAAAAAAAAgAAAAAAAIAAAAAAKAAAQAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAEAEAAAADgAAAAAgAAAAAAAAAAAAAAAAAAAABAAAACAAAYAAAAAAAAUABDADwAABAAAAADgAABACAEAAABcQBEBAEAAAAAAQA4AjwdwSMEBAAAAAAAAAAAAAAAAAAAAAAKwIJgDyQ8IIAAAAAAAAAAAAAAAAAAAAAAAAAApwibWEgAQ/d=0/dg=0/br=1/rs=ACT90oE-zpAFvhmy84cPAhTg7lFK5ycI1g/cb=loaded_h_0/m=sy3f1,P10Owf,sy7jr,sy7jq,sy1ql,sy1kr,sy1kp,sy1kq,sy20s,sy20r,VD4Qme,VEbNoe,sy7jp,TmFfhf,sy61c,xuUld,sy613,qcH9Lc,pjDTFb,gCngrf,sy60q,sy4bl,sA1ssc,sy60n,khkNpe?xjs=s4

Found key :- this.kme


2) https://www.gstatic.com/og/_/js/k=og.asy.en_US.ZB_JWty8yBQ.2019.O/rt=j/m=_ac,_awd,ada,lldp,qads/exm=/d=1/ed=1/rs=AA2YrTuOdAa9YWDd3u-N0sm5Gvsh4Lr-DQ
   Found mail:- robert@broofa.com

3) https://www.google.com/xjs/_/js/k=xjs.s.en_GB.xrFV_MEa130.2019.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEACAAAEAgAIBAAQAAAAAAAAAAAhAAHgAAAAAAAAAAAAAAAAAAAAAAAAABAQAAACABgAAAAAAAAAAAAAAAIAAABAAAAAAAAAAAAaAAABAAAEFAAAAFAAAAAAAAAAAAAAAAAAJEAAAAAAQSIAEAPhvf0ADAAAAAAAAgAAAAAAAAAAAAAAAAIAIAAAAAAAAAFgAABAUBgAgACGAAAAAAAAAAAAAAAAAAAAEAAAAAAAAgAAAAAAAIAAAAAAKAAAQAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAEAEAAAADgAAAAAgAAAAAAAAAAAAAAAAAAAABAAAACAAAYAAAAAAAAUABDADwAABAAAAADgAABACAEAAABcQBEBAEAAAAAAQA4AjwdwSMEBAAAAAAAAAAAAAAAAAAAAAAKwIJgDyQ8IIAAAAAAAAAAAAAAAAAAAAAAAAAApwibWEgAQ/d=0/dg=0/br=1/rs=ACT90oE-zpAFvhmy84cPAhTg7lFK5ycI1g/cb=loaded_h_0/m=sy5jg,sy5jd,sy5jb,sy5ja,M2ABbc?xjs=s4
(no leak found)

4) https://www.google.com/xjs/_/js/k=xjs.s.en_GB.xrFV_MEa130.2019.O/am=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEACAAAEAgAIBAAQAAAAAAAAAAAhAAHgAAAAAAAAAAAAAAAAAAAAAAAAABAQAAACABgAAAAAAAAAAAAAAAIAAABAAAAAAAAAAAAaAAABAAAEFAAAAFAAAAAAAAAAAAAAAAAAJEAAAAAAQSIAEAPhvf0ADAAAAAAAAgAAAAAAAAAAAAAAAAIAIAAAAAAAAAFgAABAUBgAgACGAAAAAAAAAAAAAAAAAAAAEAAAAAAAAgAAAAAAAIAAAAAAKAAAQAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAEAEAAAADgAAAAAgAAAAAAAAAAAAAAAAAAAABAAAACAAAYAAAAAAAAUABDADwAABAAAAADgAABACAEAAABcQBEBAEAAAAAAQA4AjwdwSMEBAAAAAAAAAAAAAAAAAAAAAAKwIJgDyQ8IIAAAAAAAAAAAAAAAAAAAAAAAAAApwibWEgAQ/d=0/dg=0/br=1/rs=ACT90oE-zpAFvhmy84cPAhTg7lFK5ycI1g/cb=loaded_h_0/m=qTnoBf,sy9p,sOXFj,oGtAuc,NJ1rfe,sya2,q0xTif,y05UD,PPhKqf,sy6lm,sy2f8,sy26q,sywv,sy26p,sy26r,sy1nd,sy2p8,sy26y,sy14r,sywu,sywt,syws,sywr,sy26x,sy26w,syzr,sy26u,sy26t,sy26z,sy270,sy26s,sy2z3,sy2is,sy2it,sy2iy,sy2h1,sy2h2,sy279,sy271,sy2ct,sy27b,sy278,sy157,sy2cy,sy28w,sy299,sywo,syxe,sywp,syxf,epYOx?xjs=s4
(no leaks found)

5) 	https://www.google.com/js/bg/JL85nlevmaDG18WpyQQxg1d04qfnhF16RsSSikJQ3G0.js
   (no leaks found)
