# Profile Documentation

This folder contains the supporting pages and visual assets for the GitHub profile README.

## Main Pages

| Page | Purpose |
| --- | --- |
| [Projects](./pages/PROJECTS.md) | Details and technology summaries for the six featured projects. |
| [Technical Domains](./pages/AI_DOMAIN.md) | Cybersecurity, software development, data, AI, and game-development interests. |
| [Learning Focus](./pages/LABS.md) | Current learning goals and how they connect to practical projects. |
| [Collaboration](./pages/COLLAB.md) | Collaboration interests, working principles, and LinkedIn contact. |

## Maintenance Pages

| Page | Purpose |
| --- | --- |
| [Roadmap](./meta/ROADMAP.md) | Directions for keeping profile information useful and accurate. |
| [Style Guide](./meta/STYLE_GUIDE.md) | Visual, layout, color, and accessibility rules. |
| [Motion System](./meta/MOTION_SYSTEM.md) | Guidance for restrained SVG animation. |
| [Asset Index](./meta/ASSET_INDEX.md) | Inventory of profile SVG assets and their roles. |
| [Visual Audit](./meta/VISUAL_AUDIT.md) | Quality bar for the visuals used in the profile. |
| [Showcase Strategy](./meta/SHOWCASE_STRATEGY.md) | Guidelines for presenting this profile consistently. |

## Local Checks

Run the local quality checks from the repository root after editing Markdown or SVG assets:

```powershell
npm run check
```

The checks validate local links and images, SVG structure, and image alt text.

## Asset Folders

| Folder | Contents |
| --- | --- |
| [`assets/svg/system/`](./assets/svg/system/) | README overview and project-map visuals. |
| [`assets/svg/pages/`](./assets/svg/pages/) | Profile summary, section headers, and page panels. |
| [`assets/svg/navigation/`](./assets/svg/navigation/) | Navigation links used throughout the documentation. |

Community and contribution guidance lives in the repository's [`.github/`](../.github/) folder.
