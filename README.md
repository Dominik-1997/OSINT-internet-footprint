# OSINT-internet-footprint

There is a lot info in on the internet and malicious actors often get a lot of data from publicly accessible websites. I am checking my internet/ social media footprint, to see how safe I am.


The only information i personally publicised about myself is:
  Facebook (accesible for friends only)
	    My first and second name
	    My home city
      Two photos from ~10 years ago
      
  Linkedin (private)
      Two universiteis I attended (Although my profile is private, google search still displays my university)
  Github
  	My Github profile name contains my birth year (I do not share my repositories anywhere except for the CVs)
   My email address
   	My email address also contains my birth year
      
Information that can be deducted:
  Facebook
      Although you can't find my birthdate in my personal information, you can check when people were wishing me happy birthday for my 18th birthday so one could get my date of birth from there 



I used reverse Google Image Search on both pictures from facebook to see if they somehow circulated internet and I found nothing
Reverse image search on Pimeyes also found nothing

So we can conclude that there are no easily findable pictures of me on the internet.

To analyse more than can be done quickly by hand i used Spiderfoot

I hosted an instance of a Spiderfoot on my vm using the command:
sudo spiderfoot -l 127.0.0.1:5000

Analysis conducted using Spiderfoot on Kali linux:

Search terms:
My name - 0 correlations
My email - 0 correlations
My phone number - 0 correlations 
My IPv4 - 0 correlations


To conclude
I am not completely invisible online, I do not share any SPII but technically my name, date and place of birth could be found if you are my acquaintance on Fb. This information is PII. 

Final remark
59% of US adults use birthdays or names in their passwords. That’s why it’s important not to share private emails and use PII in passwords
