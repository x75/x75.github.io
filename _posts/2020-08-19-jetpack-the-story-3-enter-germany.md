---
layout: post
title: Jetpack the Story, Part 3 Enter Germany
comments: true
tags: jetpack jcl robotics research startups micro-funding
---

### Jetpack the Story, Part 3 Enter Germany

This is the story of [Jetpack Cognition Lab](https://jetpack.cl),
creator of the [Bakiwi](https://bakiwi.shop) robot friend.

> recap

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
(Zweigniederlassung in German) simply by registering it with the
federal German commercial registry. This can be done by any
notary.

> German commercial registry, certified copies, ..., the Apostille

The list of required documents we obtained is this, translated
from German:
- publicly certified extract from the commercial register of the company, together with a certified translation
- publicly certified copy of the currently valid articles of association together with a certified translation
- publicly certified copies of the shareholders' resolutions containing the appointment of the company's directors, together with a certified translation
- List of shareholders

The public certification and certified translation of each document
serves to _legalize_ the foreign documents, which means to make them
legally valid in the destination country. It was not obvious
rightaway, that the named documents are legalized by different
mechanisms.

Let's translate each item to the Stripe Atlas terminology.  The
commercial register extract translates to the Certificate / Articles
of Incorporation. The articles of association translate into the
Bylaws, and the shareholder's resolutions is a document called Board
Approval. The shareholder listing explains itself.

The articles of incorporation correspond with the German
Handelsregisterauszug, and basically consist of the Certificate of
Incorporation. As a current extract from a public database, it needs
to be legalized through a process called an _apostille_ which exists
by decree from the 1961 Den Haag convention. Apostilles can be
obtained through a large number of providers of legal services, for
Stripe Atlas users the document can be ordered via LegalInc for
something on the order of a 100 USD.

The other documents are sufficiently legalized through the declaration
of authenticity on part of the company representative. All documents
need to be translated at a legal quality certification level. This is
the biggest chunk of cost in the process with quotes ranging from 1K
to above 2K EUR for a set of different translation services in
Germany. A mid-range choice worked for us.

> Registering the business with translated documents

With the translated stack of your proof of company a local notary can
be activated and the task negotiated. The notary prepares a free form
letter that asks to enter the Zweigniederlassung in the German trade
register, then you go there once, proof your identity and sign it. The
document is sent by the notary to the appropriate German court for
processing.

If the application is accepted for entry, the court will send you
paper mail with their service charges, so you have to make sure that
the mailbox is up and running at the specified address. After the
service charges are paid, the registration will be completed. The
process has indeterminate duration, in our case it took some three to
four weeks. As soon as the registration is effective, it will be
published online by the German Bundesanzeiger. A notification of your
completed entry will be sent by paper mail to you again.

There is an interesting side effect of the maneuver. There exists a
large semi-legal industry of scammers that will scrape the
Bundesanzeiger announcements and will send you fake invoices that try
to look like official court letters asking you to urgently pay a
significant amount to a given bank account. The fakes can be easily
spotted but might take you by surprise if consumed in a wrong
moment. All of this is well known and authorities will issue warnings
about it, the Bundesanzeiger even keeps a blacklist of well known
entities involved in the scams. Fun fact is, that the scamming process
is so well automated, that the fakes will arrive in your mail even
before the official notice. The upside of all that is a very fast
indication that the registration process has been completed.

Fake invoice examples

![](/assets/2020-08-19-jetpack-the-story-part-3-enter-germany/Betrugsschreiben-Fake-Handelsregister-img-000-thumb.jpg){:height="100%" width="30%"}
![](/assets/2020-08-19-jetpack-the-story-part-3-enter-germany/Betrugsschreiben-Fake-Handelsregister-img-001-thumb.jpg){:height="100%" width="30%"}
![](/assets/2020-08-19-jetpack-the-story-part-3-enter-germany/Betrugsschreiben-Fake-Handelsregister-2-img-000-thumb.jpg){:height="100%" width="30%"}


> Bank account

With the completed registration it is straightforward to get a German
bank account, if you ask the right bank. Smaller banks often don't
have a legal department that can deal with the international
regulatory machinery, as was the case with our desired banking partner
in DE. Suggestions we received that are known to work were Sparkasse
and Commerzbank.

> Summary

The next story parts will be about these topics currently work-in-progress at the lab.

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

