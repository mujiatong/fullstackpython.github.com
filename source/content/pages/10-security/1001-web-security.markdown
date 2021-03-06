title: Web Application Security
category: page
slug: web-application-security
sort-order: 1001
choice1url: /web-analytics.html
choice1icon: fa-dashboard
choice1text: I want to learn more about the users of my app with analytics.
choice2url: /api-integration.html
choice2icon: fa-link fa-inverse
choice2text: How do I integrate external APIs into my app?
choice3url: /logging.html
choice3icon: fa-align-left fa-inverse
choice3text: How can I log events that occur while the app is running?
choice4url: /about-author.html
choice4icon: fa-user
choice4text: Who created Full Stack Python?


# Web Application Security
Website security must be thought about while building every level of the web 
stack. However, this section includes topics that deserve particular
treatment, such as cross-site scripting (XSS), SQL injection, cross-site 
request forgery and usage of public-private keypairs.


## Security open source projects
* [Bro](http://www.bro.org/) is a network security and traffic monitor.

* [quick NIX secure script](https://github.com/marshyski/quick-secure) for
securing Linux distributions.


## HTTPS resources
* [How does HTTPS actually work?](http://robertheaton.com/2014/03/27/how-does-https-actually-work/)
  is a well-written overview of the protocol including certificates, 
  signatures, signing and related topics.

* This question asking [what is the difference between TLS and SSL?](http://security.stackexchange.com/questions/5126/whats-the-difference-between-ssl-tls-and-https)
  explains that TLS is a newer version of SSL and should be used because
  SSL through version 3.0 is insecure.

* If you're having users submit sensitive information to your site you need
  to use SSL/TLS. Anything before TLS is now insecure. Check out this
  [handy guide](http://wingolog.org/archives/2014/10/17/ffs-ssl) that goes
  over some of the nuances of the subject.

* [The Sorry State of SSL](https://hynek.me/talks/tls/) details the 
  history and evolution of SSL/TLS. There are important differences between
  the versions and Hynek explains why TLS should always be used. The
  talk prompted work to improve Python's SSL in 2.7.9 based on the upgrades
  in Python 3 outlined in 
  [The not-so-sorry state of SSL in Python](https://developer.rackspace.com/blog/the-not-so-sorry-state-of-ssl-in-python/).

* [How HTTPS Secures Connections](http://blog.hartleybrody.com/https-certificates/)
  is a guide for what HTTPS does and does not secure against.

* [When and How to Deploy HTTPS](http://erik.io/blog/2013/06/08/a-basic-guide-to-when-and-how-to-deploy-https/)

* [The first few milliseconds of an HTTPS connection](http://www.moserware.com/2009/06/first-few-milliseconds-of-https.html)
  provides a detailed look at the SSL handshake process that is implemented
  by browsers based on the [RFC 2818](http://tools.ietf.org/html/rfc2818)
  specification.

* [Qualy SSL Server Test](https://www.ssllabs.com/ssltest/) can be used to
  determine what's in place and what is missing for your server's HTTPS 
  connection. Once you run the test read this article on 
  [Getting an A+ on Qualy's SSL Labs Tester](https://sethvargo.com/getting-an-a-plus-on-qualys-ssl-labs-tester/)
  to improve your situation.
  

## General security resources
* The Open Web Application Security Project (OWASP) has 
  [cheat sheets for security](https://www.owasp.org/index.php/Cheat_Sheets) 
  topics.

* This page contains a
  [fantastic currated list of security reading material](http://dfir.org/?q=node/8/)
  from beginning to advanced topics.

* The [/r/netsec](http://www.reddit.com/r/netsec/) subreddit is one place to
  go to learn more about network and application security.

* [Hacking Tools Repository](http://gexos.github.io/Hacking-Tools-Repository/)
  is a great list of password cracking, scanning, sniffing and other security
  penetration testing tools.

* [Securing an Ubuntu Server](http://www.andrewault.net/2010/05/17/securing-an-ubuntu-server/)

* [Securing Ubuntu](http://joshrendek.com/2013/01/securing-ubuntu/)

* [Security Tips from Apache](http://httpd.apache.org/docs/current/misc/security_tips.html)

* [Securing a Linux Server](http://spenserj.com/blog/2013/07/15/securing-a-linux-server/)

* The EFF has a well written overview on 
  [what makes a good security audit](https://www.eff.org/deeplinks/2014/11/what-makes-good-security-audit). It's broad but contains some of their behind the
  scenes thinking on important considerations with security audits.

* [Securing Your Website](http://arstechnica.com/security/2013/02/securing-your-website-a-tough-job-but-someones-got-to-do-it/)

* [Crypto 101](https://www.crypto101.io/) is an introductory course on
  cryptography for programmers.

* [An in-depth analysis of SSH attacks on Amazon EC2](http://getprismatic.com/story/1409447605839)
  shows how important it is to secure your web servers, especially when they are
  hosted in IP address ranges that are commonly scanned by malicious actors.


## Web security learning checklist
<i class="fa fa-check-square-o"></i>
Read and understand the major web application security flaws that are
commonly exploited by malicious actors. These include cross-site request 
forgery (CSRF), cross-site scripting (XSS), SQL injection and session 
hijacking. The 
[OWASP top 10 web application vulnerabilities list](https://www.owasp.org/index.php/Top_10_2013-Top_10) 
is a great place to get an overview of these topics.

<i class="fa fa-check-square-o"></i>
Determine how the framework you've chosen mitigates these vulnerabilities.

<i class="fa fa-check-square-o"></i>
Ensure your code implements the mitigation techniques for your framework. 

<i class="fa fa-check-square-o"></i>
Think like an attacker and actively work to break into your own system. If
you do not have enough experience to confidently break the security consider
hiring a known white hat attacker. Have her break the application's security,
report the easiest vulnerabilities to exploit in your app and help implement
protections against those weaknesses.

<i class="fa fa-check-square-o"></i>
Recognize that no system is ever totally secure. However, the more popular
an application becomes the more attractive a target it is to attackers.
Reevaluate your web application security on a frequent basis.


### What topic do you want to learn about next?
