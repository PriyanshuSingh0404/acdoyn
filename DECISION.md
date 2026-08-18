1. Why this approach over the obvious alternative you rejected?

Honestly the fastest path was just throwing Tailwind's CDN at it and doing the standard hero + three icon cards thing. I skipped that because it's exactly the kind of page that looks fine in a screenshot but says nothing about the product. Since the brief specifically dings you for "claims without proof," I built an actual working demo instead of a static mockup — it took longer, but a visitor can click through and see what Vektor actually does instead of reading marketing copy about it.

2. One trade-off you made under the time limit, and what you'd do with a real week.

I hardcoded three migration examples instead of building something that could handle any number of them. It was the right call for the time I had — three well-polished scenarios beat five mediocre ones — but it means the demo is a bit rigid right now. Given a real week, I'd make it data-driven and let people paste in their own SQL to get a mock dry-run result. That'd turn it from "look at this demo" into "try this yourself," which is a much better hook.

3. Where did you use AI tools, and what did you personally verify or change afterward?

I used Claude to scaffold the HTML/CSS/JS from a design direction I set myself (the color system, type pairing, the two-panel layout). After that I went through it manually — ran the JS to make sure there were no errors, checked contrast in both light and dark mode, confirmed reduced-motion actually turns off the animations and isn't just there for show, and clicked through all three tabs a bunch of times to make sure nothing kept stale data from the previous tab. I also caught that my first pass at the sparkline data made all three states look nearly identical, so I reworked the numbers until safe/caution/danger were actually visually distinct.
