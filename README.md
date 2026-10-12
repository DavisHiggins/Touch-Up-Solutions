<p align="center">
  <a href="https://touchupsolutions.vercel.app"><img src="assets/hero.svg" width="100%" alt="Touch Up Solutions catalog redesign: shop repairs by the material. Animated cover with the Touch Up Solutions logo and headline beside wood, leather, metal, and laminate swatches whose scratches are repaired in turn." /></a>
</p>

<h1 align="center">Touch Up Solutions</h1>

<p align="center"><strong>A catalog and how-to redesign for a repair-products manufacturer, organized around the material a customer is fixing.</strong></p>

<p align="center">
  <a href="https://touchupsolutions.vercel.app"><img src="assets/btn-open.svg" height="44" alt="View the redesign" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/touch-up-solutions"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Catalog redesign · Designed, built, and presented to Touch Up Solutions by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="880" alt="Screen recording of the redesign: the Wood Repair category with filter pills and priced products, then a guide link leading to the 'Use Burn-In Sticks' how-to page." />
</p>

<p align="center"><sub>Real capture of touchupsolutions.vercel.app: from a material category into the how-to guide beside it. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **Browse by material.** Dedicated shops for wood and furniture, leather and vinyl, metal, and accessories, each with filters for product types like adhesives, burn-in sticks, fill sticks, and markers.
- **Guides next to the products.** A how-to library (cabinets, furniture scratches, laminate flooring, burn-in tools, metal epoxy, touch-up paint) sits beside the categories it applies to, and every guide links back to the right supplies.
- **Two kinds of customer.** Separate Home User and Industrial User shops, with a quote request and quick-order path for trade buyers.

## The problem

Touch Up Solutions makes repair products for wood, leather, metal, and laminate. That breadth is a strength in a showroom and an obstacle online. Buyers arrive knowing the material they're repairing and the job in front of them, but a broad catalog makes it hard to narrow down to the one product that fits.

The redesign structures the catalog around that starting point and puts the answer to "how do I use this?" right beside the products.

## What I built

- Information architecture across 24 pages: home, product catalog, material shops, how-to guides, programs, videos, and a resources page for safety data sheets
- A single catalog that feeds every category grid, with filters per category
- A persistent cart drawer and checkout flow
- The visual system: dark walnut and cool-light surfaces, amber calls to action, Playfair Display and DM Sans

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    D[One product catalog] --> G[Material category pages]
    G --> F[Filters by product type]
    G --> C[Cart drawer]
    H[How-to guides] <--> G
```

| Decision | Why |
|---|---|
| **Lightweight by design** | A catalog this size doesn't need heavy machinery. The pages load fast, deploy anywhere, and stay easy for the company's own team to maintain. |
| **One catalog feeds everything** | Adding or repricing a product is a single change that shows up on every page that lists it. |
| **Guides and products link both ways** | A buyer who starts with a technique or with a product reaches the other in one click. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="Touch Up Solutions redesign homepage: 'Manufacturing, Distributing, Selling, and Supporting' beside cards for wood, leather, and metal repair." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="How To Guides page on a phone with a wood kitchen cabinet guide." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-catalog.png" alt="Wood Repair category with filter pills and priced adhesive products beside an Application Guides panel." /></td>
  </tr>
</table>

<sub>Homepage · Wood repair catalog · How-to library on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| Pages | HTML, CSS |
| Behavior | JavaScript |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://touchupsolutions.vercel.app"><img src="assets/btn-open.svg" height="44" alt="View the redesign" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. The Touch Up Solutions name, logo, and product imagery belong to Touch Up Solutions.</sub></p>
