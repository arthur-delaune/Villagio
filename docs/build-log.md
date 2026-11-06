# Build log

A high-level view of how the Villagio prototype is progressing. The product code lives in a private team repository. This log tracks milestones, not implementation details.

**Stack:** Next.js · React · Tailwind CSS · shadcn/ui, built with AI-assisted development (Claude Code)

---

## November 2026

### Nov 5: families and activities, two-screen publishing
- **Families and activities.** One shared catalogue structures the whole product. It has four families (Sport, Dance, Music, Arts), each with its activities, and it drives publishing, search and link previews.
- **Sizes the way parents say them.** Each kind of gear gets its own size logic: shoe size, clothing height in cm, instrument fractions (1/2, 3/4…), hockey ranges, helmet sizes. The common values are one tap away.
- **Publishing in two screens.** The listing flow went from several steps down to two. The activity is suggested automatically from the title. The faster a parent can list, the more listings the marketplace has.
- **Helmet safety shown to the buyer.** When an item is a helmet or protective gear, the seller states its safety standard and year, and both are shown on the listing. Sellers are reminded to list only gear that has never taken a hit and is still within its lifespan. This brings the *guides & labels* differentiator into the product itself.

### Nov 4: design system v1 and club spaces
- **Design system v1.** Brand guidelines, logo, icon set, and every page redesigned from the mockup. The signature element is *« L'étiquette »*, the name label passed from one child to the next. Colour, type and contrast rules are written down, so the product stays consistent as the team grows.
- **Brand homepage.** Campaign card, a "pass it on" banner, real gear photography and a desktop layout. The demo photos were checked one by one: gear only, no children, no names.
- **Club spaces (demo).** A club directory, a page for each club and access with a club code. This is the core differentiator from the product strategy, now clickable. Public club pages show only a counter of relays between families. Parents' names stay visible to club members only.

### Week of Nov 3: search, sharing and richer listings
- **Share to WhatsApp, with rich link previews.** Every listing generates its own branded preview card when it is shared. Parents already coordinate in club and class WhatsApp groups, so a listing that looks good there is Villagio's first organic distribution loop.
- **Richer listing details.** A clear condition scale (from "new with tags" to "fair", each with a one-line definition), brand and model, a negotiable flag and the original retail price, which shows the parent how much they save compared to buying new.
- **Give it away.** Parents can list an item for free. Passing outgrown gear on to the next family is core to the community spirit, and it seeds supply early on.
- **Search page with filters.** Parents can browse listings and narrow them down to find the right item quickly.
- **New activity: ice hockey.** A dedicated gear catalogue, helmet safety-standard guidance and sample listings, including the hockey bag. This tests how easily Villagio extends to a new activity, using the activity-specific *guides & labels* approach.
- **Platform maintenance.** The framework was kept up to date with the latest security release.

## October 2026

### Week of Oct 27: first screens and the publish flow
- **Homepage V0 and listing page.** These are the first end-to-end screens of the marketplace.
- **Homepage art direction.** Signature label, typography and colour palette, aligned with the brand: warm, reassuring and practical.
- **"Publish a listing" flow.** The seller journey from photo to published listing.
- **Photo upload done right.** Instant preview, support for iPhone photos (HEIC) and clear error messages. A small detail, but it removes a lot of friction for parents listing from their phones.

### Week of Oct 14: foundations
- The team set up the project foundations: the framework, the design-system components and the shared development conventions.

---

**Next up:** smoother navigation, local search by club and neighbourhood, and messaging between parents.
