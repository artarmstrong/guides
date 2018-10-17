---
title: Graceful Degradation
---
## Graceful Degradation

Graceful degradation is a design philosophy that centers around trying to build a modern web site/application that will work in the newest browsers, but fall back to an experience that while not as good still delivers essential content and functionality in older browsers. The degraded application may not be as nice to use for your site visitors, but it does still provide them with the basic functionality that they came to your site to use; things do not break for them.

Polyfills can be used to build in missing features with JavaScript, but acceptable alternatives to features like styling and layout should be provided where possible, for example by using the CSS cascade, or HTML fallback behaviour.

It is a useful technique that allows Web developers to focus on developing the best possible websites while balancing the issues in those websites being accessed by multiple unknown user-agents. Progressive enhancement is related but different — often seen as going in the opposite direction to <a href='https://guide.freecodecamp.org/css/progressive-enhancement' target='_blank' rel='nofollow'>progressive enhancement</a>. In reality both approaches are valid and can often complement one another.

#### More Information:
<a href='https://developer.mozilla.org/en-US/docs/Glossary/Graceful_degradation' target='_blank' rel='nofollow'>MDN Web Docs - Graceful degradation</a>

<a href='https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement' target='_blank' rel='nofollow'>W3C Graceful degradation versus progressive enhancement</a>
