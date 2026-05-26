# Engin Iktir Theme — Changes

## Design updates (2026-05-26)

### General
- Page background changed from beige (`#f7f5f2`) to white (`#ffffff`)
- Content column width increased from ~803px to 840px (wrapper max-width: 1236px)

### Header / Top Bar
- Topbar padding reduced (26px → 10px) to compress the header zone
- Top bar CTA buttons: text labels hidden, icons only (16×16px), text hidden on both desktop and mobile
- First CTA button icon changed from info circle to sad smiley face

### Navigation (Desktop)
- Dropdown nav arrows (chevrons) enlarged to 18×18px via CSS
- Dropdown behaviour unchanged: hover to open

### Navigation (Mobile Drawer)
- Items with submenus split into a clickable text link + a separate chevron-only toggle button
- Text labels now link independently; only the arrow opens/closes the submenu
- Long item text (e.g. Therapeutenausbildung) uses `white-space: nowrap` + ellipsis to keep arrow on the same line
- All drawer link text changed to full white (`#ffffff`) — top-level and sub-items

### Sidebar Cards
- Icons moved from standalone left column into the card title (`h3`) inline
- Icon circles resized from 42px to 28px

### Footer
- Background changed from navy blue (`--navy`) to dark charcoal (`#1a1a1a`)
