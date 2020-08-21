---
layout: post
title: Jetpack the Story, Part 2
comments: true
tags: jetpack jcl robotics research startups micro-funding
---

### Jetpack the Story, Part 2 Founding mechanics

> recap

In [part one](/2020/02/20/jetpack-the-story-1-init/) of the story we
talked about the the time and the things leading up to our agreement
to create Jetpack Cognition Lab on private equity funding. This
current part covers the mechanics of creating a Delaware C Corporation
and making the first steps with the baby company.

> ycombinator, standard documents, SAFE agreement

The [magic](https://www.magic.do) crew had introduced us to
[ycombinator](https://www.ycombinator.com) and the model for funding
early stage startups that they have created over time. It consists of
a well consolidated process for setting up a company and dealing with
investments with minimum headache. The process makes use of a set of
standard documents that do not have to be modified when going from one
company to the next. A central piece in this is the _Simple Agreement
on Future Equity_ (SAFE), a **four-page** document that can be
consumed and understood by virtually anyone. In the SAFE a standard
early-stage investment deal is laid down, requiring only a few
variables to be filled in: the name of the company, the name of the
investor, and the number of shares returned for what amount of
investment.

Note: We are **not** associated with ycombinator in any way. What we
did is adopt some of their processes and tools which are publically
available.

The /Future/ bit in the SAFE takes care of the fact that all of this
is only relevant _if and only if_ some kind of positive liquidation
event (LE) occurs during the time the SAFE is valid for. Relevant LE's
are created either by a new investment round, the company being sold
or being closed down. In addition the SAFE puts rules in place to
avoid unintended investor interference, which is a well known reason
for startup fails. We took a SAFE and went with that.

> create the company with Stripe Atlas in the US

One of ycombinator's own startups is the payment service provider
Stripe. They have a product called [Atlas](https://stripe.com/atlas)
which takes the YC standardization idea to the app level. The Atlas
app allows you to create a company by registering a Delaware LLC or
C-Corporation and open a workable bank account in the name of the
newly founded company through a five page form.

In case that you are a pure software business you are probably pretty
much set at this point. If you registered a corporation like we did,
the Atlas process involves a few more steps that you will be churning
down in the weeks after the company initialization (for an LLC that's
probably true as well but I have not been there).

> company structure: shareholders, directors, officers

A corporation is a legal entity designed for fluid changes in equity
shares among a potentially large number of parties. The standard
document creates a stock of 10M shares initially. These shares are all
common stock (CS) which means that they come with a vote in the
shareholder meeting. Another kind of stock is the preferred stock
(PS), which does not include the right to vote but is served first in
a liquidation event.

The corporation, its structure and organs are defined by the Bylaws
which are standardized and part of the Atlas document stack. At the
top of the decision chain are the shareholders with common stock. The
shareholders then name one or more directors into the Board of
Directors, which in turn may elect the company's officers (CEO, CFO,
ETCTO, ..). In the case of a two person founding team you end up in
all three levels.

> issuing stock, 40/40, 20 pool

Founding a corporation does not make you its owner automatically. To
become the owner, the company needs to issue the stock to the parties
involved. In order to avoid huge income taxes for the non-liquid
assets of the young company, this needs to be done within a month
after registering the company. During this period the shares are
guaranteed to be evaluated at their par-value which is a very tiny
amount. After completing the purchase agreement, one has to make sure
to actually pay this amount to your own company and make sure the
transaction is recorded in the company logs.

The stock purchase agreement also comes out of the Atlas process. The
precise allocation of shares depends on the number of founders and
their indivdual stakes of course. In addition, it is considered good
practice to leave a portion of shares unissued. These comprise a pool,
which we can use later on to give to the first few critical team
members as an incentive. After a few discussions we went for a 40 / 40 /
20 split among founder / founder / pool using a standard four year
vesting, one year cliff setup.

Note: the income tax issue is reflected onto your country of (tax)
residence if you are not a US citizen or tax payer. Thus the 83b
election form does not need to be completed and handed in for
foreigners.

> enter operations

Depending on your situation you will need to direct company money
towards yourself as an income. Starting with a full-blown employment
is maybe too complicated in terms of administrative overhead and
liabilities created. Based on different ad-hoc advice from our network
we picked the two-freelancers-invoicing-to-company model. This means
each founder will invoice their services and expenses to the company
every one or two months, either in a direct way or as successive
installments of a lump budget.

> summary

This article is a technical description of how to incorporate your
company and some of the first steps towards getting it
operational. Details include the process of creating a US company with
Stripe Atlas as a foreign entity, considerations on issueing stock to
founders, and how to pay yourself for freelance services in this first
phase.

Registering the business locally within Germany is the subject of
[part three](/2020/08/19/jetpack-the-story-3-enter-germany/) of the
story, coming soon.

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

