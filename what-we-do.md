---
title: SparX - What We Do
layout: default
---

# What We Do

We are tasked to design and engineer the products that will shape
Staples' future.

## Our Vision

Use data and technology to drive eCommerce to the point where every
business process is optimized, and where every customer experience is
special, personal, "indistinguishable from magic".

## How We Work

We design and build [actual products](/who-we-are#actual-products), in
[small teams](/who-we-are#small-teams), leveraging
[data science and engineering](/who-we-are#data-science--engineering-excellence)
to transform eCommerce.

## Our Current Products

### Personal Offers

Boosting sales by sacrificing margins is easy -- try it, it just
works. This is just a race to the bottom. And so is raising margins
and sacrificing a good portion of your existing sales.

The real art is to somewhat manage to increase sales _and_ margin at
the same time; and this is exactly what our "Personal Offer" product
pulls off.

The core idea is actually quite simple. Imagine that you have a
product -- say a notebook -- whose cost structure is such that:
- you still make good profits with a 10% discount
- but would go quickly in the red if you were to offer a bigger discount.

One of the traditional approach to increase sales for the notebook is
to offer a 10% discount to everybody, or at least to a significant
part of your customer base.

This approach is far from being the most effective. To understand why,
let's focus on a concrete example. Bob & Alice both want to buy the
notebook and come to your online store. The problem is that Bob is
just in a hurry, and could care less about price, as long as the price
is not completely outrageous. Alice, on the other hand, is a very
savvy shopper, with a lot of time on her hand, and it would take at
least a 20% discount to get her sale.

If you give them both a 10% discount what happens?
- You secure Bob's sale, but you unnecessarily sacrificed 10% of the
  cost in terms of margin, because he would have bought anyway.
- For Alice, this is even worse. You loose both the sale and the
  margin, because 10% is not enough. Darn!

So what our "Personal Offer" product does is to:
- detect that Bob is _not_ price sensitive, and we do _not_ give him
  any discount
- detect that Alice would buy with a 20% discount, and we secure her
  sale by giving it to her, since we "saved" a 10% discount on Bob.

In this way we just doubled our sales and margins, all at the same
time!

Of course this is easier said than done, because Bob might actually be
price sensitive for specific products, specific times of the day and
of the year, when shopping from a specific location, when exhibiting
specific browsing patterns, etc. This is where our expertise in data
science and machine learning is handy.

"Personal Offer" is already running in production on staples.com and
demonstrating its capacity to boost sales & margins at the same
time. This is just the start though, we are improving our models every
day.

### Personal Email

Another of our products running in production is "Personal Email". The
idea is also quite simple, but it is a powerful one.

We inject personalized content and offers on marketing and
transactional emails. The personalization take into account everything
we know about the customer: his online and offline shopping patterns,
browsing history, etc.

There is a twist though. We do not decide on the actual content when
the email is sent. We defer that decision to the last possible moment:
when the customer opens the email.

This approach is challenging in that it forces us to flex our
engineering muscles: we need to be able to run sophisticated machine
learning algorithms in a couple of milliseconds to avoid impacting the
customer experience.

However this approach has also proven to be extremely powerful:
- Recommendations can take into account customer activity up to the
  second before the email was open. This maximizes the relevancy and
  impact of the personalized content.
- Even better, we can plug some adaptive algorithms in the mix that
  can self-adapt in real-time to patterns that would be hard to
  _anticipate_ but that can be _discovered_ in real-time: weather
  episodes, local events and celebrations, etc.

### Smart Shipping

Another area of expertise for SparX is precise shipping times
computations.

Some websites provide shipping estimations in a very generic form :
something like "1 to 4 business days". This is a shame, because if you
know for a fact that a specific product will arrive the same day for a
specific customer, this is a competitive advantage, and you want to
communicate it!

When you already have a great shipping infrastructure like Staples
does, the great thing about communicating personalized and
highly-accurate shipping times is that it has the potential to drive
sales _without_ impacting margins. Hard to pass!

Our shipping models are based on historical data and can predict both
handling and shipping time.

### Multi-Variate Testing Platform

We have a strong culture of
[fact-based decisions](/who-we-are#bias-for-action-results--fact-based-decisions). This
means that we measure all our products on a multi-variate testing
platform, that we designed and built to match our needs.
