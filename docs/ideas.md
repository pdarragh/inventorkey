# Ideas

This document is for recording various ideas related to the website.

## High-Level Description

The website provides a community focal point for browsing photos of keyboards.
Photos have tags associated with them (e.g., `layout-65`, `red`, `6-degree`)
that allow for easily searching for keyboards by any number of features, or
finding recommendations based on past keyboards that were "liked".

An additional avenue to explore might be launching/organizing interest checks
(ICs).
Although the actual discussion should be relegated to GeekHack, an IC's initial
post could be a link to our site.
If a consistent layout is used for IC posts, it could make comparing/contrasting
ICs much easier.
Additionally, posts could be "saved" somewhere so users can more readily manage
their various interests.
IC posts could link back to the appropriate GeekHack or Reddit post for ease of
use.

## Names

  * Board-ers
  * keebstagram
  * instakeeb
  * keybrd
  * kibrd
  * kbrd
  * kbdgram
  * keyb-rd
  * kenterest
  * keebhoard

## Features

  * Instagram-like "feed" of cards.
      * Each card can be an album.
      * Primarily for keyboards and keycap sets.
      * Cards have tags (like hashtags, only more purpose-built).
      * Cards are posted by designers.
      * Clicking a card takes the user to a dedicated page for the keyboard.
      * Questions about cards:
          * Do cards support comments?
          * What about likes? Saves? Suggestions? Ads?
          * Is it a social network? Follows/friends/etc?
  * Exceptional search functionality.
      * Designers supply initial tags on posts, which are used for search.
          * Tags are great because it encourages using a consistent terminology
            for everything across the site, which makes search easier and more
            consistent.
      * Users can add additional tags? (Unsure.)
      * An important tag: render/real.
  * Special Interest Check posts.
      * Should these be significantly different from regular posts?

## Implementation

  * Back-end in Elixir.
      * This is the current plan, anyway.
      * Using Phoenix Framework w/ live-updating.
