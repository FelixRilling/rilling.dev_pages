---
title: "Gender-Diverse Forms"
date: 2017-02-02
updated: 2021-09-25
tags:
    - HTML
    - LGBTQIA+
    - Forms
---

Pretty much everyone who uses the internet probably had to fill out a form at some point that asked for your gender. Most forms tend to have very limited options for specifying gender, ranging from a dropdown from 'female', 'male' and sometimes 'other' to things like two radio buttons to pick either 'female' or 'male'.
This can be quite frustrating for people which do not fit into either of these 'female' or 'male' boxes, and even if an option for 'other' is available, such an option groups together many wildly different gender identities into one box, which is sub-optimal.

Other issues can appear when companies who are aware of these issues try to fix them by offering options for a wider range of commonly used genders: Dropdowns can end up having _too_ many options and finding the best match gets hard. This approach also often ends up including several genders which are usually perceived as identical (why are you offering the options 'Woman' as well as 'Trans Woman'?).

Let's look at how we can design forms to account for these issues and avoid them.

<!-- more -->

## You Aren’t Gonna Need It

Even though ["You aren't gonna need it" (YAGNI)](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it) is focused on programming, the same can also be applied in other cases. One of the best ways to ensure you are not at risk of leaking the personal data of your users is to not collect any in the first place. This obviously excludes essential data such as usernames or email-addresses but can be relevant for the gender of your users.
Often the gender selected by the user is only used in very few places, such as the greeting in mails sent to them. In such cases, often it is easiest to simply use a gender-neutral greeting such as 'Dear \<username\>' or 'Dear customer' instead. This not only avoids the need of having to know the users gender, but also reduces the amount of logic for building the mail. Another solution to this is only asking for the users pronouns rather than their gender.

<!--
## How it's been so far:

Most forms currently have a structure similar to this:

![Old Gender Form](form_old_1.png)

or this:

![Old Gender Form with Radio buttons](form_old_2.png)

As you already might have guessed: You can't possible include all gender labels into a list like this.

## A possible solution

So here is an idea how to solve this:
Instead of asking for an explicit gender, simply asking for the preferred pronoun is way easier - most of the time that is the only thing a gender selection input is used for anyways. While this is obviously quite a bit of a change, I feel like this would be a relatively minor change with quite an improvement on inclusion.
Here is an example on how this could look:

![Form with pronoun-sentence](form_new_1.png)

In this case we use a sentence where we ask for the users pronouns in the subjective and possessive form,
allowing us to interact with the user using the correct pronouns.

## Names and legal names

In cases where you need the users legal name, for example when sending receipts,
including an optional text-field for the legal name can be a good idea:

![Form with pronoun-sentence and optional legal name](form_new_2.png) -->

## Additional Resources

-   [Designing forms for gender diversity and inclusion](https://uxdesign.cc/designing-forms-for-gender-diversity-and-inclusion-d8194cf1f51)