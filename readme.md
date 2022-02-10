# Split by Setupjs

## Description
A really simple page which helps you load 2 urls simulataneously.

## Motivation
When I was trying to learn the apis of a new JavaScript library, I had to open 2 tabs in the browser. One for loading the documentation and one for loading the practice page where I was trying those apis. I had to keep switching between tabs and I got annoyed on multiple occasions. And I wished I could keep these 2 html pages side by side.

## Claim
No claim at all. And I do not think it is unique. I found it easier to reinvent the wheel than to find existing one and deal with ads and trackers.

## Limitations
- It will not be able to load a page if it has `"X-Frame-Options: SAMEORIGIN"` set.
refer [this question on stackoverflow](https://stackoverflow.com/questions/8700636/how-to-show-google-com-in-an-iframe).

- Type [FQDN](https://en.wikipedia.org/wiki/Fully_qualified_domain_name) of the page.
