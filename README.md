# OSINT-internet-footprint

<p> There is a lot info in on the internet and malicious actors often get a lot of data from publicly accessible websites. I am checking my internet/ social media footprint, to see how safe I am.


<p>The only information i personally publicised about myself is:

<ul>
  <li>Facebook (accesible for friends only)</li>
	<ul>
      		<li>My first and second name</li>
      		<li>My home city</li>
		<li>Two photos from ~10 years ago</li>
    	</ul>
  <li>Linkedin (private)</li>
	<ul>
      		<li>Two universiteis I attended (Although my profile is private, google search still displays my university)</li>
    	</ul>
  <li>Github</li>
    <ul>
      <li>My Github profile name contains my birth year (I do not share my repositories anywhere except for the CVs)</li>
    </ul>
  </li>
    <li>My email address</li>
    <ul>
      <li>My email address also contains my birth year</li>
    </ul>
  </li>
</ul> 
 <br>     
<p>Information that can be deducted:
<ul>
<li>Facebook</li>
	<ul>Although you can't find my birthdate in my personal information, you can check when people were wishing me happy birthday for my 18th birthday so one could get my date of birth from there </ul>
</ul>


<br>
<p>I used reverse Google Image Search on both pictures from facebook to see if they somehow circulated internet and I found nothing
<p>Reverse image search on Pimeyes also found nothing
<br>
<p>So we can conclude that there are no easily findable pictures of me on the internet.
<br>
<p>To analyse more than can be done quickly by hand i used Spiderfoot
<br>
<p>I hosted an instance of a Spiderfoot on my vm using the command:
sudo spiderfoot -l 127.0.0.1:5000
<br>
<p>Analysis conducted using Spiderfoot on Kali linux:
<br>
<p>Search terms:
<p>My name - 0 correlations
<p>My email - 0 correlations
<p>My phone number - 0 correlations 
<p>My IPv4 - 0 correlations
<br>

<p>To conclude
<p>I am not completely invisible online, I do not share any SPII but technically my name, date and place of birth could be found if you are my acquaintance on Fb. This information is PII. 
<br>
<p>Final remark
<p>59% of US adults use birthdays or names in their passwords. That’s why it’s important not to share private emails and use PII in passwords
