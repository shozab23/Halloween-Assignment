# Haunted Harvest: Cursed Beach Cove at Sunset

A Halloween-themed, CSS-only animated scene built with HTML5 and CSS3. There is no JavaScript anywhere in the project. All motion and navigation come from `@keyframes`, `:target`, `:hover` and `:focus`.

**Category:** Undergraduate
**Live site:** 
**Repository:** https://github.com/shozab23/Halloween-Assignment

## Team

| Member | GitHub | Contribution |
|---|---|---|
| Shozab Mirza | [shozab23](https://github.com/shozab23) | HTML skeleton and CSS foundation, Scene 2 (Ghost Ship Horizon), Scene 3 (Midnight Bonfire), pull request reviews, README |
| Joe Turner | [ethanturner190](https://github.com/ethanturner190) | Scene 1 (Sunset Cove), pull request reviews |

Task assignments are tracked in the repository's Issues tab, and each scene was built on its own branch and merged through a reviewed pull request.

## Scenes

We chose Option 3, Cursed Beach Cove at Sunset. Use the navigation links or the "Next" buttons to move between chapters.

1. **Sunset Cove:** skeleton pirates at a bonfire, a ghost ship on the horizon, bats, a crab and a floating jack-o'-lantern
2. **Ghost Ship Horizon:** a stormy dusk with lightning, a skeleton waving from a pier, a skeleton rowing a boat, bats and a crab
3. **Midnight Bonfire:** skeletons dancing around a flickering fire, a black cat, a crab, bats, rising jack-o'-lantern lanterns and a distant ghost ship

## Required scene elements

| Element | Examples |
|---|---|
| Human activity | Skeletons dancing, waving and rowing |
| Animals | Bats, crabs, a black cat |
| Weather | Drifting clouds, rolling fog, lightning |
| Realistic movement | Waving arms, bobbing boats, flapping wings, rolling waves |
| Vehicles or objects in motion | Ghost ships, a rowboat, rising lanterns |
| Halloween theme | Skeletons, jack-o'-lanterns, a full moon |

## Technical notes

- **CSS-only interactivity:** scene switching uses `:target`, the bonfire flares on `:hover`, and links have visible `:focus-visible` outlines.
- **Responsive:** percentage-based positioning and `aspect-ratio` keep scenes readable on phones and desktops.
- **Accessibility:** semantic HTML5 structure, a skip link, descriptive `aria-label` text on each scene, and a `prefers-reduced-motion` media query.
- **Theming:** the Halloween palette is defined as CSS variables in `:root`.
- **Single stylesheet:** all styles live in `haunted-harvest.css`.

## Project structure

```
index.html            # Page markup and scene structure
haunted-harvest.css   # All styles and animations
assets/               # Images and fonts
README.md
```

## Running it locally

1. Clone the repo: `git clone https://github.com/shozab23/Halloween-Assignment.git`
2. Open `index.html` in a browser. No build step is needed.