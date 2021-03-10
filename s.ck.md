---
id: 644e92f4-67d2-4cf1-9748-846d53e96870
title: Convert Kit
desc: ''
updated: 1615309897618
created: 1615309853592
---


# Templates
- source: [^1]
<!-- -->

[^1]: https://help.convertkit.com/en/articles/2502633-basic-email-personalization-with-liquid-faqs

- You can add a subscriber’s first name and email address by pasting the following shortcodes into your emails: {{ subscriber.first_name }} and {{ subscriber.email_address }}
- You can also automatically inject the content of any of your subscribers’ custom fields. Generating the shortcode is simple: use the same format as for the first name & email shortcodes above, but use the name of your custom field instead, and replace any spaces with underscores.
    - For example, a custom field called ‘Last Name’ would become {{ subscriber.last_name }}, one called ’Photography Experience’ would become {{ subscriber.photography_experience }}, and so on.

- NOTES
    - In preview emails, field shortcodes will show up as [FIRST NAME GOES HERE], [EMAIL ADDRESS GOES HERE], etc. This means you've added the shortcodes correctly — those placeholders will be replaced with the actual values once the broadcast is actually sent out.


