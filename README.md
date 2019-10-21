# sendSMS
Perl utility to deliver SMS messages to your phone via provider's web-interfaces

# About SendSMS
If you have an Alltel Wireless, AT&T Wireless, Bell Canada/Bell Mobility, Cellular One, Cingular, Sprint PCS, SkyTel, or T-Mobile cell phone or pager, and you want the ability to send SMS messages to it via a command-line utility, this is what you need. All this program requires is a computer with a baseline Perl 5.x installation and web access. NO EXTRA PERL MODULES REQUIRED!

# How do I install it?
Simply download `sendSMS.pl` and run it from a command prompt. It will give a usage summary.

# How does it work?
SendSMS connects to your service provider's web page and pretends to submit a form to their 'Instant Messaging' web page. Currently, Alltel Wireless, AT&T Wireless, Bell Canada/Bell Mobility, Cellular One, Cingular, SkyTel, Sprint PCS, and T-Mobile are supported. Users are encouraged to modify the provided templates to add support for any providers who are currently unsupported.

# Other Service Providers
 If you are interested in supporting another service provider please try to modify sendSMS on your own. It is not hard at all. Instructions and examples are included in the code, and if you're familiar with the site you're porting to, it takes about 15 minutes. If you get sendSMS working with any other providers' web sites, please email Paul Kreiner [deacon at thedeacon.org] a patch so it can be added to the next release.

# List of Contributors
* David Caplan: code to support Bell Canada / Bell Mobility
* John Carbone: code to support Sprint PCS
* Joel Chen: updates to AT&T code
* Jared Cheney: updates to AT&T code
* Barret Kendrick: code to support Cingular
* Manuel Martin: code to support T-Mobile
* Tod Morrison: code to support Cricket [deprecated]
* Anthony Valley: code to support Alltel Wireless
* Paul Kreiner: rewrote sendSMS into its present form
* Brandon Zehm: bugfixes, SkyTel support, web proxy support, and original sendSMS script
