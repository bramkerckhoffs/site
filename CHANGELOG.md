# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project follows semantic versioning when tagged or released.

## [0.1.2] - 2026-06-05

### Added
- Image lightbox expansion with click-to-zoom behavior; click the expanded image or anywhere outside it to zoom out.

### Changed
- Refined article navigation styling with lighter inline links and locally hosted arrow icons.
- Shifted docs and category page layouts to a larger responsive breakpoint so mid-sized screens give the content more room.
- Replaced Manrope with locally hosted Geist Sans and Geist Mono.
- Updated secondary `ButtonLink` styles to use a transparent background with a visible border in light and dark mode.
- Renamed docs article slugs to match titles for `write-your-first-article` and `set-up-compass`.
- Removed animation from previous/next article hover state; article title and icon now turn blue on hover.

## [0.1.1] - 2026-06-05

### Added
- New `Start Here` starter articles for creating articles, publishing Compass, restructuring categories, and branding the docs site.
- Reusable checklist components for interactive task lists inside MDX content.

### Changed
- Simplified the search results dropdown to show article titles with frontmatter-driven description previews.
- Updated starter docs to use interactive checklists for publishing and branding workflows.

## [0.1.0] - 2026-06-04

### Added
- Initial Compass Astro docs theme release.
- MDX-based documentation structure with category-driven navigation.
- Pagefind-powered search for the docs homepage and sidebar.
- Reusable docs components including callouts, tabs, accordions, steps, buttons, and quote blocks.
- Light and dark mode support.
