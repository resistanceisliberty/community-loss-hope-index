# Community Loss & Hope Index — Philadelphia

**Live:** https://resistanceisliberty.github.io/community-loss-hope-index/

Mapping community grief across Philadelphia: because loss isn't random, it's place-based and persistent.

I combined two earlier prototypes into a single site, with the original author's permission:

- [Index concept](https://merctwain.github.io/IndexConcept/): the interactive ZIP-code bubble map, key findings, and city-wide trends (built by TD Mindpower)
- [Index prototype](https://merctwain.github.io/Index/prototype1cli.html): neighborhood rankings, the bereavement gap, the compounding effect, and 2023 at a glance

The page has one header, one palette and type system, and a section nav. Clicking a ZIP in any of the lower charts selects it on the map.

A project of the [Wealth + Work Futures Lab](https://wealthworkfutures.org) at Drexel University's Lindy Institute for Urban Innovation.

## Files

- `index.html`: the page, including its styles and scripts
- `data.js`: ZIP-level indicators for 2015–2023, city-wide trends, and the mini-map polygons

It has no build step. To run it locally, serve the folder (for example `python3 -m http.server`) and open it in a browser.

## Data sources

School District of Philadelphia, PA Vital Statistics & Vital Registration, Philadelphia DHS, Philadelphia Police, PHC4, Prison Policy Initiative, Judi's House CBEM.
