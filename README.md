# Homework1

## Description

Website for Horiseon.

![Image of Horiseon webpage](\images\Horiseon-pic.png)

## Changes to original HTML and CSS files

HTML

- In `<head>` gave website "Horiseon" `<title>`
- fixed search engine optimization link
- ???.hero image needs alt atribute???
- added alt descriptions to images in Search Engine Optimization, Online Reputation Management, Social Media Marketing, Lead Generation, Brand Awareness, and Cost Management -sections.
- deleted closing `</img>` tag
- gave navigation bar `<nav>` tags instead of `<div>`
- changed digital-marketing-meeting.jpg to `<figure>` instead of `<div>`
- put Search Engine Optimization, Online Reputation, and Social Media Reputaions under `<section>` insead of `<div>`
- put Lead Generation, Brand Awareness, and Cost Management  under `<aside>` instead of `<div>`
- changed footer section to `<footer>` from `<div>` and removed redundant class="footer"

CSS

- changed instances of .footer to just footer
- consolidated .benefit-lead, .benefit-brand, .benefit-cost into .benefitChunk and changed class in HTML
- consolidated .search-engine-optimization, .online-reputation-management, .social-media-marketing into .contentChunk and changed class in HTML
- moved CSS elements to mirror HTML flow