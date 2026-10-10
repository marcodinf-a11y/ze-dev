Type: wayfinder:map

Archived local draft. The [GitHub map](https://github.com/marcodinf-a11y/ze-dev/issues/1) is canonical.

## Destination

A reviewable blueprint for a historical game development studio economy simulation: player experience, core loop, simulation rules, domain language, modular monolith architecture, and a path for teaching programming concepts while building it. The blueprint should be clear enough to turn into implementation work for a Godot game using C# where practical, targeting Linux and Windows.

## Notes

- This is a planning map. Do not implement the game while working these decisions.
- Consult the grilling and domain-modeling skills for player-facing and domain decisions.
- Treat 1950 and Bertie the Brain as the historical opening anchor. The reference is https://en.wikipedia.org/wiki/PC_game; historical accuracy and gameplay compression need an explicit decision.
- The requested technology is Godot, primarily C#, with GDScript where C# is unsuitable. Verify version-specific engine claims when they become relevant.
- The form of the teaching material remains open pending user input.
- Game data must come from configuration files or databases rather than being hardcoded. Mod support is a requirement from day one; source formats and mod boundaries are decisions below.
- This is an open source project under the MIT License, published at https://github.com/marcodinf-a11y/ze-dev.
- GitHub Issues is the decision tracker. The local files are an archive and source-backed research assets.

## Decisions so far

- [Research historical market milestones](https://github.com/marcodinf-a11y/ze-dev/issues/4): 1950 is an exhibition and research phase; later hardware and distribution changes overlap rather than replacing one another all at once.
- [Define player role and campaign goal](https://github.com/marcodinf-a11y/ze-dev/issues/2#issuecomment-6095827924): inventor opening, creative and business direction, legacy across studio runs, optional succession, and separate sandbox mode; continuation leadership and character balance need later exploration.

- [Prototype the core decision loop](https://github.com/marcodinf-a11y/ze-dev/issues/3#issuecomment-6096364441): continuous time, milestone and discovery reviews, self-funded or commissioned opening projects, feedback after delivery, and parallel projects as the studio grows.

## Not yet specified

- How deep the economic model should run within each era once the desired player experience and time scale are settled.
- Which studio growth and failure pressures deserve detailed mechanics after the core loop is chosen.
- How historical events, platform changes, and competitor behavior should combine once the timeline approach is decided.
- Save compatibility and balancing tools after the simulation boundaries are defined; data authoring and mod compatibility are covered by the data-source and mod-support tickets.
- Interface and accessibility needs after the moment-to-moment decisions are understood.
- Concrete learning milestones after the desired teaching format is chosen.

## Out of scope

- Building a playable release or writing implementation tickets during this planning map.
