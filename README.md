# Cubic: interactive demo

**[Open the demo](https://prmpsmart.github.io/cubic-demo/)**

> Know what is there, know whether you may take it, and prove what you took.

Cubic turns grid drill or probe data into a trustworthy account of the cubic metres at a site: how much sand is there, what it costs to reach, what limits apply, and a sealed statement that anyone can check. This page lets you try the interface with a made-up sample site. (Cubic is a working name.)

## What this demo is

- A **clickable version of the interface**, so you can see how the flow feels and tell us what is unclear or missing.
- It works on a **synthetic sample site** (made-up data patterned on Lagos lagoon surveys). Every screen of that site carries a "SYNTHETIC TEST DATA" banner.
- It runs **entirely in your browser**. Nothing you enter is sent anywhere, and it stays on your device. It works with no internet once loaded.
- The figures are real arithmetic on the sample file, but the **ranges are illustrative** and the **seal is a demonstration**, not yet a signed record. This is not a permit, not a reserve, and not a basis for any decision.

## Try it in five minutes

Open the demo, then open **Sample site: Lagos Lagoon (synthetic)**.

| Step | What to look at |
| --- | --- |
| **Check it** | The file has four negative overburden values. See the effect of fixing them (about 94,680 m³ becomes 113,080 m³) and note that nothing changes until you choose. Every choice is recorded. |
| **Declare** | What the file cannot say about itself, asked once. After saving, see how your words are checked against the numbers. |
| **What you have** | The coverage map (hatched nodes had no access and are never filled in), sand and overburden volumes, the stripping ratio and tonnage, each as a range with a data quality grade. |
| **Does it pay?** | Enter your own price, cost and royalty (nothing is assumed). See the break-even stripping ratio and move the profit sliders. |
| **May we?** | A screening check with four possible outcomes. It is never an approval, and anything unchecked reads "not assessed", never "clear". |
| **Issue** | A sealed statement: save it as a PDF or download the statement file. |
| **Verify** | Drop the statement file in. Then change one number in it and drop it in again: the change is caught. |

You can also create your own site with **New site**, and bring your own CSV with the columns `x, y, z, ore_grade, over_burden_depth, ore_depth`. It stays in your browser.

## The few rules the interface holds to

- A **resource**, not a reserve, unless the economics clear, there are no red flags, and a named qualified person signs. Even then it is an "indicative reserve", always with a range.
- Every number comes with a **range and a data quality grade**.
- **No silent edits:** every fix and assumption is recorded and printed on the statement.
- **Declared is not verified:** input is labelled as declared by the collector.
- **Unknown is not safe:** a check with no data is "not assessed".
- **Never a go-ahead:** the best result is "no red flags at screening level".

## Not in this demo yet

Comparing a second survey after extraction, uploading protected-area maps, working across several organisations, and a view for agencies and lenders.

## Feedback

Note anything that is unclear, surprising or missing as you go through it, and send it back to whoever shared this link. Screenshots help. The line at the top right of the demo shows the build date and version you were looking at.
