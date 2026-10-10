Type: wayfinder:map

Archived local draft. The [GitHub map](https://github.com/marcodinf-a11y/ze-dev/issues/1) is canonical.

## Destination

A reviewable blueprint for a historical game development studio economy simulation: player experience, core loop, simulation rules, domain language, modular monolith architecture, and a path for teaching programming concepts while building it. The blueprint should be clear enough to turn into implementation work for a Godot game using C# where practical, targeting Linux and Windows.

## Notes

- This is a planning map. Do not implement the game while working these decisions.
- Consult the grilling and domain-modeling skills for player-facing and domain decisions.
- Treat 1950 and Bertie the Brain as the historical opening anchor. The reference is https://en.wikipedia.org/wiki/PC_game; historical accuracy and gameplay compression need an explicit decision.
- The requested technology is Godot, primarily C#, with GDScript where C# is unsuitable. Verify version-specific engine claims when they become relevant.
- The player's precise starting role and the form of the teaching material remain open pending user input.
- This is an open source project under the MIT License, published at https://github.com/marcodinf-a11y/ze-dev.
- GitHub Issues is the decision tracker. The local files are an archive and source-backed research assets.

## Decisions so far

- [Research historical market milestones](https://github.com/marcodinf-a11y/ze-dev/issues/4): 1950 is an exhibition and research phase; later hardware and distribution changes overlap rather than replacing one another all at once.

## Not yet specified

- How deep the economic model should run within each era once the desired player experience and time scale are settled.
- Which studio growth and failure pressures deserve detailed mechanics after the core loop is chosen.
- How historical events, platform changes, and competitor behavior should combine once the timeline approach is decided.
- Save compatibility, balancing tools, and content authoring workflow after the simulation boundaries are defined.
- Interface and accessibility needs after the moment-to-moment decisions are understood.
- Concrete learning milestones after the desired teaching format is chosen.

## Out of scope

- Building a playable release or writing implementation tickets during this planning map.
