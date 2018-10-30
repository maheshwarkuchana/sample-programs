---
title: Even Odd in Every Language
layout: default
---

# Even Odd

An even number is an integer which is "evenly divisible" by two. This
means that if the integer is divided by 2, it yields no remainder.

An odd number is an integer which is not evenly divisible by two. This
means that if the integer is divided by 2, it yields a remainder of 1.

## Requirements

Create a file called Even Odd using the naming
convention appropriate for your language of choice.

Write a sample program which accepts an integer on the command line and
outputs if the integer is Even or Odd.

## Testing

Verify that the actual output matches the expected output. See the
[requirements][1] section for an example of the expected output.

## Articles

{% for article in site.even_odd %}    
  {% unless article.title contains 'Every Language' %}
  - [{{ article.title }}]({{ article.url | relative_url }})
  {% endunless %}
{% endfor %}

## Further Reading

- Fill out as needed

[1]: #requirements