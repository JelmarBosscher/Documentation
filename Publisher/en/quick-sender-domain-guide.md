# Setting up a sender domain

Copernica has created the concept called *sender domains*. 
This concept makes sending email simple and effective. 
In all Copernica services, sender domains are mandatory, 
because of the fact that it's such an essential element
when sending out your emails. Using sender domains goes 
like this: in the Marketing Suite, determine from which 
domain you want to use for mailing. After you've done 
that, Copernica will let you know how the DNS settings
have to be confirmed. 

So if you want to send emails from addresses that end 
with "@example.com" or "example.org", you can set up these
domains in the Marketing Suite dashboard. Copernica returns
a list with DNS records if you correctly followed the 
steps when setting everything up. The DNS records only need
to be given to your DNS provider or your own DNS server.

You can find more information in the [background-article for sender domains](./sender-domains). 

## Marketing Suite

The newly designed Marketing Suite interface lets you 
easily set up your sender domain. When you set up your 
domain as a sender domain, Copernica automatically makes 
sure your DNS settings are correct and up-to-date. You 
won't need to configure anything, domain-wise, after the
initial setup. This means your click, bounce and open domains 
are set up and your DKIM keys are rotated automatically. The 
sender domain settings have priority, even if you choose to only 
send email through the Publisher. You'll find the `SENDER DOMAIN`
tool in the Marketing Suite menu.

## The next step

To send your first mailing, you need [a database with profiles](./quick-database-guide) 
to send it to. After this you'll get to send your first mail, we promise!

## More information

Did you set up a sender domain? If you're curious about sender domains 
and the technologies that protect your reputation you can also find more 
information in the background articles.

* [Glossary](./definitions)
* [Sender domains background](./sender-domains)
* [DKIM](./dkim)
* [DMARC](./dmarc)
* [SPF](./spf)
