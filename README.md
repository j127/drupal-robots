# Drupal.org's Robots.txt File

The default robots.txt file in Drupal still has SEO problems even in Drupal 7.

I've written about that since 2008 but it was never fixed.

I just made a few quick suggestions here on Github on how Drupal.org's own robots.txt file could be simplified.

# Details

Trailing wildcards (*) aren't needed.

This rule:
    Disallow: /profile/*

is identical to this rule:
    Disallow: /profile/

which is already covered by this rule:
    Disallow: /profile

and so on...

