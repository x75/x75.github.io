---
layout: post
title: Jetpack the Story, Part 2
comments: true
tags: robotics, research, startups
---

### Jetpack the Story, Part 2 Founding mechanics

> ycombinator, standard documents, SAFE agreement

The magic crew introduced us to ycombinator and the recipes for
building startups that they have come up with. One of those is a well
consolidated process for setting up a company (incorporating) with
minimum headache. The process emphasizes the use of standard documents
that do not have to be modified when going from one company to the
next. A central piece in this is the _Simple Agreement on Future
Equity_ (SAFE), a **four-page** document that can be consumed and
understood by virtually anyone. In the SAFE a standard early-stage
investment deal is laid down, requiring only a few variables to be
filled in: the name of the company, the name of the investor, and the
number of shares returned for what amount of investment.

To be clear about it, we're **not** associated with ycombinator in any
way but we are adopting some of their processes and tools that are
publically available.

The /Future/ bit in the SAFE takes care of the fact that all of this
is only relevant _if and only if_ some kind of positive liquidation
event (LE) occurs during the time the SAFE is valid for. Relevant LE's
are created either by a new investment round, the company being sold
or being closed down. We took a SAFE and went with that.

> create the company with Stripe Atlas in the US

One of ycombinator's own startups is the payment service provider
Stripe. They have a product called Atlas which takes the YC
standardization idea to an app level. The Atlas app allows you to
create a company by registering a Delaware LLC or C-Corporation and
open a workable bank account in the name of the newly founded company
through a five page form.

In case you're a pure software business at this point you're probably
pretty much set. If you registered a corporation like we did, the
Atlas process involves a few more steps that you'll be churning down
in the weeks after the company initialization (for an LLC that's
probably true as well but I have not been there).

> company structure: shareholders, directors, officers

A corporation is a legal entity designed for fluid changes in equity
among a potentially large number of parties. The standard document
creates a stock of 10M shares initially. These shares are common stock
(CS) which means that they come with a right to vote in the
shareholder assembly. Another kind of stock is a so called preferred
stock (PS), which does not include the right to vote but is served
first in a liquidation event.

The corporation, its structure and organs are defined by the bylaws
which are standardized and part of Atlas. At the top of the decision
chain are the shareholders with common stock. The shareholders then
name one or more directors into the Board of Directors, which in turn
may elect the company's officers (CEO, CFO, ETCTO, ..). In the case of
a two person founding team you end up in all three levels.

> issuing stock, 40/40, 20 pool

Founding a company does not make you its owner automatically. To
become the owner the company needs to issue the stock to the parties
involved. In order to avoid paying huge income tax for the non-liquid
assets of the young company, this needs to be done within a month
after registering the company. During this period the shares are
guaranteed to be valued by their par-value which is a very tiny
amount. After completing the purchase agreement, one has to make sure
to actually pay this amount to your own company and make sure the
transaction is recorded in the company logs.

The stock purchase agreement also comes out of the Atlas process. The
precise allocation of shares depends on the number of founders and
their indivdual stakes of course. In addition, it is considered good
practice to leave a portion of shares unissued. These comprise a pool,
which we can use later on to give to the first few critical team
members as an incentive. After few discussions we went for a 40 / 40 /
20 split among founder / founder / pool using a standard four year
vesting, one year cliff.

> enter operations

Depending on your situation you will need to divert company money
towards yourself. Starting with a full-blown employment is maybe too
complicated in terms of admin overhead and also not so flexible. Based
on different advice from our network we picked the
two-freelancers-invoicing-to-company model. This means each founder
will invoice their services and expenses to the company every one or
two months, either in a direct way or as successive installments of a
lump budget.

> enter Germany

Like many Atlas users we are operating our business outside the US, in
our case Germany. The freelancer model sketched above is not a
long-term solution. Also, German authorities and businesses will not
interact with you as a legal company. This means for example no
business accounts with vendors, no bank accounts with German banks, no
tax ID, and so on, making employment impossible. To a domestic
business entity you have to have an entry in the commercial registry
(Handelsregister).  The usual advice in this case is to create a
German subsidiary of the foreign company, for example a GmbH. We did
not want to do this in the first place so that did not work for us.

> Zweigniederlassung

Turns out there is a good solution which is to create a German
/branch/ of the company (Zweigniederlassung). The branch can be
registered with the German commercial registry. This can be done by
any notary and requires /legalized/ copies of the original foreign
documents.

> German commercial registry, certified copies, ..., the Apostille

Legalization is done through a process called an /apostille/ which
exists by decree from the 1961 Den Haag convention. Apostilles can be
obtained through a large number of service providers, some of which
offer online interfaces allowing you to order the required documents
with an apostille from the Delaware state.

This is the top of the stack and WIP. Next step is to make sure the
documents match the German requiredments and to get them
translated. Stay tuned for updates.

> TODO: taxes 2019

WIP

> TODO: working contracts w/ German branch

Get draft, find templates.

> TODO: hiring

WIP

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

