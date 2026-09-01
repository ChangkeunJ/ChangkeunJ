Hi, I'm David (@ChangkeunJ), a freelance full-stack developer in Busan, Korea.
I build small tools that show their working.

Things I made:

- **[visa-times](https://github.com/ChangkeunJ/visa-times)** — how long each Australian visa is
  taking, read once a day and kept with the dates each number held. Home Affairs republishes the
  figure over the top and keeps nothing, so a month later there is no record of what it said.
  Movements go out as a feed; there is no account to make.
  [Live](https://visa-times.pages.dev/)

- **[rent-check](https://github.com/ChangkeunJ/rent-check)** — what a tenancy actually starts
  at, from the bond every Australian landlord has to lodge with the state. 1.8 million New South
  Wales lodgements since 2021, so the quartiles are worked out here rather than taken from
  someone else's median, plus the Queensland and Victorian medians, the suburbs behind each
  postcode, and what each state's Act says about the increase.
  [Live](https://rent-check-5kx.pages.dev/)

- **[rate-ledger](https://github.com/ChangkeunJ/rate-ledger)** — every advertised rate the
  Australian banks publish under the Consumer Data Right, read once a day and kept with the
  dates each number held. 249 lenders and 24,000 rates, stored as intervals, so what a bank
  was charging on a past date is still answerable. [Live](https://rate-ledger.pages.dev/)

- **[paperpack](https://github.com/ChangkeunJ/paperpack)** — working holiday tax and
  departing superannuation for Australia, worked out in the browser. TypeScript, zero
  dependencies, no backend: every figure carries the government page it came from, and
  nothing you type ever leaves the tab. [Live](https://paperpack-7v7.pages.dev/)

- **[australian-law-mcp](https://github.com/ChangkeunJ/australian-law-mcp)** — MCP server
  over Australia's Federal Register of Legislation. Ask what an act said on any past date,
  and check citations against the official register before relying on them.

- **[april-number](https://github.com/ChangkeunJ/april-number)** — what your own Australian
  hospital policy's listed premium did on 1 April, rather than the industry average. Joins
  two of the Ombudsman's monthly files; seven languages, nothing leaves the browser.
  [Live](https://april-number.pages.dev/)

Mostly TypeScript, Postgres and Cloudflare these days. Embedded research and e-commerce
platforms before that.

[reiot92@gmail.com](mailto:reiot92@gmail.com)
