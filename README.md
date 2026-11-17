# ShiftKit Lebanon

An open source toolkit for building shift and temp work marketplaces in Lebanon.

**Status: planning stage.** No code has been released yet. This README describes what the project will be, so developers can follow along and give feedback from the start.

## Why this exists

Lebanon has no platform that connects businesses with workers for short shifts and temporary jobs. Restaurants, events, retail and logistics companies still find extra staff through WhatsApp groups and word of mouth. Students and young workers who want flexible income have no reliable place to find it.

Anyone who tries to build this kind of platform in Lebanon has to start from zero: matching logic, payments in a mixed currency economy, local contract rules, and an interface in three languages. ShiftKit will give developers a shared, open base for all of that, so each team does not rebuild the same pieces.

## What it will include

1. **Job posting:** a clear data model for shifts (role, location, date, hours, pay, requirements) and tools to create, edit and close them.
2. **Worker matching:** ranking available workers for a shift by distance, skills, availability and past ratings.
3. **Trilingual interface:** ready interface text in Arabic, English and French, with full right to left support for Arabic.
4. **Local work rules:** a configurable rules module for short term work contracts in Lebanon, so platforms can check shifts against hours and rest requirements.
5. **Ratings and reliability:** a simple two way rating system for businesses and workers, with no show tracking.
6. **Pay handling:** support for pay in US dollars and Lebanese pounds, since both are used day to day.

## Who it is for

* Developers building staffing, gig or shift platforms in Lebanon and the wider region
* Startups that want a tested base instead of writing everything from scratch
* Students and contributors who want to work on a real project with local impact

## Roadmap

**Phase 1: Foundations**
Data model for shifts, workers and businesses. Project structure, license and contribution guide.

**Phase 2: Core features**
Job posting module, matching engine, and the trilingual interface text.

**Phase 3: Local rules and pay**
Contract rules module and dual currency pay handling.

**Phase 4: Real world use**
Integration into a live staffing platform in Lebanon, with fixes and improvements shared back here.

## How it will be maintained

ShiftKit is built alongside a staffing platform that two cofounders are launching in Lebanon. Every part of the toolkit will be used in production there, which means real testing and steady updates. Improvements made for the platform that are useful to others will come back to this repository.

## Contributing

Contributions will be welcome once Phase 1 is published. Until then, the best way to help is to open an issue with:

* Features you would need for a platform like this
* Local rules or practices the toolkit should account for
* Translation feedback for Arabic or French

## License

ShiftKit will be released under the MIT License, so anyone can use it, change it and build on it freely.
