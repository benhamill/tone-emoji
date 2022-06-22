# Tone Emoji

A collection of emoji to help clarify your tone in the types of text-only
environments that are so common on the internet. Inspired by the existing
text-only accessibility tool called "[tone indicators][tone-indicators]".


## What's included?

In an effort not to overwhelm, we focused on what we thought would be the most
widely useful indicators, so we include 12 in this version:
* /gen (genuine)
* /hj (half joking)
* /ij (inside joke)
* /j (joking)
* /lit (literal)
* /- (negative)
* /+ (positive)
* /ref (reference)
* /rh (rhetorical)
* /s (sarcastic)
* /srs (serious)
* /? (what tone is this)

Here are some examples:

![tone-joking][]
![tone-sarcastic][]
![tone-genuine][]
![tone-what][]

If you think we're missing an important indicator from this set, we're happy to
hear about it, but one thing we want to keep in mind is that too large of a
vocabulary can be overwhelming. So if we add one, we probably want to do so as
a replacement of an existing one. Keep that in mind when making suggestions.


## Design

The colors are all based on Google's Material design under the thinking that
that design system is well-vetted and the colors work well together without
having to reinvent the wheel.

The leading slash is implied by the background rather than explicitly rendered
under the thinking that as a separate emoji, that piece of information is less
useful that the letter abbreviation, which should be as large as possible.

The font used in these emoji is [Noto Sans, Extra Condensed][noto-sans].

The emoji were designed and created by [Lee Fuhr][lee-link].


## Accessibility

In the interest of accessibility all of the emoji background colors have an AA
contrast rating or better as measured by https://coolors.co/contrast-checker.

For best results with screen readers (and also to help other users who are
unfamiliar with tone indicators understand what these mean), we recommend using
the file names in this repo as the long names for these emoji. That way a
screen reader would read, "How hepful! /s" as "How helpful tone sarcastic".

⚠**Note:** These are accessibility tools. Using them in a sarcastic, hyperbolic
or ironic way fundimentally undermines their use to people who benefit from
them. So do not use /gen when you're not being genuine or /j when you're being
serious. Thanks.⚠


## File formats.

The repository includes PNG and SVG exports. You can find the original artwork
and edit it [on Figma][figma-edit-link].

[figma-edit-link]: https://www.figma.com/file/pHxMnzdhpdgK4nbGlKWDx1/Tone-indicators?node-id=502%3A2
[lee-link]: https://www.cozydesign.com
[noto-sans]: https://fonts.google.com/noto
[tone-indicators]: https://en.wikipedia.org/wiki/Tone_indicator
[tone-joking]: png/tone-joking.png
[tone-sarcastic]: png/tone-sarcastic.png
[tone-genuine]: png/tone-genuine.png
[tone-what]: png/tone-what.png
