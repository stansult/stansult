# Hi, I'm Stan

I'm a software QA engineer based in Orange County, California. I've worked on web, mobile and backend systems at PayPal, Atom Tickets, Amazon and Gaia Interactive, combining exploratory testing, test automation and hands-on investigation.

I also build browser extensions, games and small tools. I enjoy figuring out how things work, finding the cases that are easy to miss, and making repetitive tasks a little less annoying.

[Online resume](https://stansult.com/resume) · [LinkedIn](https://www.linkedin.com/in/stansult/)

## Chrome extensions

### Dropdown Extractor

Extracts dropdown options to the clipboard, including their displayed text and underlying values. Supports native dropdowns and many custom implementations. Includes a playground and Playwright tests that exercise the real extension.

[Chrome Web Store](https://chromewebstore.google.com/detail/dropdown-extractor/gbocefdbkfckcdbdhmaipklcfhgmeghm) · [Playground](https://dropdown-extractor.stansult.com) · [Source](https://github.com/stansult/dropdown-extractor)

### Album Filter

Adds in-page filtering and automatic loading to long Facebook photo-album lists. Its test playground covers dynamic content, filtering and UI behavior, with TypeScript and Playwright coverage.

[Chrome Web Store](https://chromewebstore.google.com/detail/hflbafejehpoclienjonceojnnlckahm) · [Playground](https://album-filter.stansult.com) · [Source](https://github.com/stansult/album-filter)

### Table Filter

Scans a virtualized table into a local view for filtering and sorting in the browser. Currently focused on the My Shows table at [TrackSeries](https://trackseries.tv/myshows).

[Source and installation](https://github.com/stansult/table-filter)

## Games

### Faker

A multiplayer browser party game for 3–20 players, where most players give clues about a secret word while one player bluffs without knowing it.

JavaScript frontend, serverless backend and persistent room state support shared game sessions, with tests covering game logic, API workflows and multiplayer browser scenarios. CI checks run before deployment.

[Play Faker](https://play-faker.us) · [Source](https://github.com/stansult/faker)

## Tools

A few small utilities for everyday tasks.

### Screenshots

A Bash/ImageMagick utility for transforming, combining, and pairing screenshots.

- **Montage** combines images into one layout.
- **Zip** pairs corresponding images from multiple sets.
- **Each** processes images individually.
- **Paginate** splits a long screenshot into a paged PDF.

Regression tests cover image transformations, file handling, input validation and error behavior.

[Source](https://github.com/stansult/screenshots)

### PDF Slim

Utilities for reducing PDF sizes and cleaning up scanned documents, with configurable quality and output options.

[Source](https://github.com/stansult/pdf-slim)

### Circle Img

An image utility that adds padding for circular crops, keeping meaningful content inside the circle. Useful for contact pictures and avatars.

[Source](https://github.com/stansult/circle-img)

### Thread Splitter

A browser-only JavaScript tool that splits long text into thread-ready parts within configurable character limits.

TypeScript/Playwright desktop and mobile tests cover split boundaries, input workflows, clipboard actions and JSON export. GitHub Actions CI gates deployment on passing tests.

[Try it](https://thread-splitter.stansult.com) · [Source](https://github.com/stansult/slice-txt)
