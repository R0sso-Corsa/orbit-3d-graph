# Orbit 3D Graph

Explore your Obsidian vault as an **interactive, offline 3D force-directed graph**. Every markdown note becomes a node, every note-link becomes an edge.

## Features
- 3D force-directed graph of your whole vault (notes as nodes, links as edges)
- Node size scales with link count (degree)
- Nodes colored by top-level folder
- Live refresh when notes are created / deleted / renamed or links change
- Search notes by name or path
- Toggle show/hide unlinked (isolated) notes
- Orbit controls: drag to rotate, scroll to zoom, right-drag to pan
- Click a node to open the note; Shift / Cmd / Ctrl + click opens in a new tab
- Fit graph to reframe the whole view
- Pause / resume the force-layout animation
- Stats footer with note and link counts
- Graceful fallback if WebGL is unavailable

## Controls
| Action | Input |
| --- | --- |
| Rotate / orbit | Left-drag |
| Zoom | Mouse wheel / scroll |
| Pan | Right-drag |
| Open note | Click a node |
| Open note (new tab) | Shift / Cmd / Ctrl + click a node |
| Reframe whole view | **Fit graph** button |
| Pause / resume layout | **Pause** button |
| Refresh data | **Refresh** button |
| Toggle unlinked notes | **Unlinked notes** checkbox |
| Search | Top search box (Enter opens a single result) |

## Installation
Install **Orbit 3D Graph** from the [Community plugins](https://obsidian.md/community) browser, or via **Settings → Community plugins → Install from URL** pointing at this repository.

## Notes & roadmap
- Runtime is fully offline — no network calls once the plugin is installed.
- Built on [`3d-force-graph`](https://github.com/vasturiano/3d-force-graph) (MIT).
- Roadmap: persistent settings (node-size / color / link-opacity options, reset-to-defaults), richer tooltips, and scaling for very large vaults.

## License
MIT
