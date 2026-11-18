# InterfaceFoundry

**A collection of working, interactive user-interface references.**

InterfaceFoundry is a practical library of interface examples that can be explored, studied, adapted and used as starting points for new projects. It focuses on working front-end references rather than static screenshots.

## What belongs here?

Examples may include:

- AI image-generation workspaces
- Messaging and collaboration interfaces
- Web browsers and research workspaces
- 3D creation and inspection environments
- Office, document and productivity editors
- Other reusable application layouts and interaction patterns

A reference may use mock data and local state. It does not need a production backend, authentication service or live API to demonstrate its interface.

## Repository structure

Each reference should live in its own folder:

```text
interface-foundry/
├── README.md
├── index.html
└── <reference-name>/
    ├── README.md
    ├── design-spec.md
    ├── assets/
    └── html/
        ├── index.html
        ├── styles.css
        ├── script.js
        └── assets/
```

The exact source layout may vary when justified, but the implementation format must be obvious and documented.

## Reference requirements

Every contribution should include:

- **README.md** — what the reference demonstrates, how to run it and its implementation status.
- **design-spec.md** — layout, visual rules, components, states and interaction behaviour.
- **assets/** — assets used by the reference, with rights and attribution documented.
- **Source implementation** — working code that can be opened and tested.

The reference should demonstrate meaningful interactions, not merely imitate a screenshot. Mock data and local state are acceptable when clearly identified.

## Implementation formats

The initial collection is HTML/CSS/JavaScript-first. Other implementations may be added later, but each must be independently tested and clearly labelled.

Do not imply that an HTML reference has an equivalent PyQt, Rust or other framework implementation unless that port exists and has been validated.

## Quality checklist

- The example opens and runs using its documented instructions.
- Main controls and interactions behave as described.
- Layout works at the intended viewport sizes.
- Assets are included or their source and licence are documented.
- No secrets, private tokens or unnecessary telemetry are included.
- Known limitations and incomplete interactions are disclosed.

## Relationship to BuildCollective

- **InterfaceFoundry** provides working interface patterns.
- **Visual DNA** provides visual design-language guidance.
- **BuildSeeds** provides the software concept and feature requirements.

Use any repository independently, or combine all three when shaping a new application.

## Contributing

Contributions should be runnable, documented and honest about their completeness. Prefer focused references that demonstrate a coherent interface or workflow over oversized, unfinished application clones.

## Licence

This project is intended for public-domain-style reuse under **CC0 1.0 Universal**, subject to the repository licence, third-party asset notices and the licences of any included dependencies.
