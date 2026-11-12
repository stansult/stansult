# Hi, I'm Stan

I'm a software QA engineer based in Orange County, California. I've worked on web, mobile and backend systems at PayPal, Atom Tickets, Amazon and Gaia Interactive, combining exploratory testing, test automation and hands-on investigation.

I also build browser extensions, games and small tools. I enjoy figuring out how things work, finding the cases that are easy to miss, and making repetitive tasks a little less annoying.

[Online resume](https://stansult.com/resume) · [LinkedIn](https://www.linkedin.com/in/stansult/)

## Chrome extensions

### Dropdown Extractor

Copy the options from a dropdown to your clipboard, including their displayed text and underlying values. Supports native dropdowns and many custom implementations. Includes a playground and Playwright tests that exercise the real extension.

[Chrome Web Store](https://chromewebstore.google.com/detail/dropdown-extractor/gbocefdbkfckcdbdhmaipklcfhgmeghm) · [Playground](https://dropdown-extractor.stansult.com) · [Source](https://github.com/stansult/dropdown-extractor)

### Album Filter

Find albums in long Facebook photo-album lists with in-page filtering and automatic loading. Its test playground covers dynamic content, filtering and UI behavior, with TypeScript and Playwright coverage.

[Chrome Web Store](https://chromewebstore.google.com/detail/hflbafejehpoclienjonceojnnlckahm) · [Playground](https://album-filter.stansult.com) · [Source](https://github.com/stansult/album-filter)

### Table Filter

Scan a virtualized table into a local view, then filter and sort its rows in the browser. Currently focused on the My Shows table at [TrackSeries](https://trackseries.tv/myshows).

[Source and installation](https://github.com/stansult/table-filter)

## Games

### Faker

A multiplayer browser party game for 3–20 players. Most players know a secret word and give clues. One player has to bluff their way through without knowing it.

I built the game with a JavaScript frontend, a serverless backend and persistent room state. Tests cover game logic, API workflows and multiplayer browser scenarios, with CI checks before deployment.

[Play Faker](https://play-faker.us) · [Source](https://github.com/stansult/faker)

## Tools

A few small utilities for everyday tasks.

- **[Screenshots](https://github.com/stansult/screenshots)** is a bash script that prepares and combines screenshot images.
  - **Montage** mode combines images into one layout.
  - **Zip** mode pairs corresponding images from multiple sets.
  - **Each** mode processes images individually.
  - **Paginate** splits a long screenshot into a paged pdf.
- **[PDF Slim](https://github.com/stansult/pdf-slim)** reduces PDF sizes and cleans up scanned documents, with configurable quality and output options.
- **[Circle Img](https://github.com/stansult/circle-img)** prepares images for circular crops, keeping meaningful content inside the circle. Useful for contact pictures and avatars.
- **[Thread Splitter](https://github.com/stansult/slice-txt)** ([source](https://thread-splitter.stansult.com)) is a browser tool that splits long text into thread-ready posts, with emoji-aware character counting and formatting options.
