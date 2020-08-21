---
layout: post
title: Jetpack the Story, Part 3
comments: true
tags: jetpack jcl robotics research startups micro-funding
---

### Jetpack the Story, Part 3 Enter Germany

> intro and recap

In [part one](/2020/02/20/jetpack-the-story-1-init) we talked about
the the time and the things leading up to the agreement to create
Jetpack Cognition Lab and on what terms this is going to occur. [Part
two](/2020/02/28/jetpack-the-story-2-make) covered the mechanics of
creating a Delaware C Corporation and making the first steps with the
baby company. This part contains the record of registering the
business locally in Germany.

> enter Germany

Like many Atlas users we are operating our business outside the US, in
our case that is Germany. The freelancer model sketched above is not a
long-term solution. Also, German authorities and businesses will not
interact with you as a company on eye level. This means, for example,
no business accounts with vendors, no bank accounts with German banks,
no tax ID, and so on, making employment hard or impossible. To become
a domestic business entity proper you have to have an entry in the
federal commercial registry (Handelsregister). The usual advice in
this case is to create a wholly-owned German subsidiary of the foreign
company, for example a GmbH. We did not want to do this rightaway as
it means again quite a bit of administrative overhead and liabilities
down the line.

> Zweigniederlassung

It turns out that there exists a nice solution for the initial
phase. It consists of creating a German _branch_ of the company
(Zweigniederlassung in German). The branch can be registered with the
federal German commercial registry. This can be done by any notary and
requires _legalized_ copies of the original foreign documents.

> German commercial registry, certified copies, ..., the Apostille

Legalization is done through a process called an _apostille_ which
exists by decree from the 1961 Den Haag convention. Apostilles can be
obtained through a large number of providers of legal services, some
of which offer online interfaces allowing you to order the required
documents with an apostille from the Delaware state.

For us, the required documents were the Articles of Incorporation, the
Board of Directors approval of the CEO, the Bylaws, and a shareholder
listing. The articles of incorporation correspond with the German
Handelsregisterauszug, and basically consist of the Certificate of
Incorporation. This needs an apostille and can be ordered via LegalInc
for around 100 USD. The other documents are sufficiently valid as
simple declarations on part of the company representatives. All
documents need to be translated at a legal quality certification
level. This is the biggest chunk of cost in the process with quotes
ranging from 1K to above 2K EUR for a set of different translation
services. A mid-range choice worked for us.

 - TODO: add verbatim copy of list

> Registering the business with translated documents

Next, with the translated stack of your proof of company go and find a
local notary and negotiate the task. This consists of the notary
preparing a free form letter that asks to enter the Zweigniederlassung
in the German trade register. Once it is prepared you go there and
sign it. The document is sent by the notary to the appropriate German
court for processing.

If the application is accepted for entry, the court will send you
paper mail with the service charges, so you have to make sure that a
mailbox is up and running at the specified address. After the
service charges are paid, the registration will be completed.

As soon as the registration is effective, it will be published online
by the German Bundesanzeiger. A notification of your completed entry
will be sent by paper mail to you again. There is an interesting side
effect of the maneuver. Since there exists a large semi-legal industry
of scammers that will scrape the Bundesanzeiger announcements and will
send you fake invoices that try to look the official court notice
asking you to urgently pay some significant amount to a given bank
account. These fakes can be easily spotted but still might take you by
surprise. All of this is well known and authorities will issue
warnings about it, the Bundesanzeiger even keeps a blacklist of well
known entities involved in the scams. Fun fact is, that the scamming
process is so well automated, that the fakes will arrive in your mail
even before the official notice. The upside of that is that it serves
as an indicator of the completion of the registration process.

 - TODO: Include scans.
 
The next story parts will be about these topics

> TODO: taxes 2019

> TODO: working contracts w/ German branch

> TODO: the role of CEO

> TODO: hiring and building a team

### Comments

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//x75.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}

