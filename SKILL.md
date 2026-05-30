# Skill: Generate LDCC Cricket Matchday Posters

## Purpose
Create Instagram-ready matchday poster images for London Desperados Cricket Club (LDCC) using a consistent gritty LDCC visual identity.

Use this skill whenever the user asks to create a matchday poster, public poster, or Instagram poster for an LDCC cricket match.

---

## Required Output
Generate a **single Instagram portrait poster image** in **4:5 ratio**.

Recommended size: **1080 x 1350 px**.

The final image should be suitable for posting directly on the **London Desperados CC Instagram account**.

Instagram handle to use:

**@londondesperados**

---

## Visual Style
Use the established LDCC matchday poster theme:

- Bold gritty cricket poster style
- Dark blue and red colour palette
- London skyline background
- Distressed typography
- Grunge textures
- Strong sports-poster energy
- Player/cricketer silhouette on the left
- Match details and Playing XI panel on the right
- Modern, premium, Instagram-friendly layout
- High contrast text
- Clean spacing despite gritty styling

Do **not** make the poster look generic, corporate, soft, or overly colourful.

---

## Branding Rules

### LDCC Logo
- Use the official LDCC logo (assets/desperados.png).
- Place the LDCC logo at the **top-left corner**.
- Do not write extra explanation like “LDCC logo”. Show only the logo.

### Opponent Logo
- Do **not** invent or assume opponent logos.
- The team-vs-team section should use text only unless the user explicitly provides an opponent logo.

### Sponsors
Add sponsor logos at the bottom:

- Rayyan Groups / Rayyan Restaurant (assets/rayyan.png).
- KodeKloud (assets/kodekloud.png).
- Global Sports Link (assets/globalsports.png).

Rules:
- Use sponsor logos exactly as provided.
- Do not redesign, redraw, recolour, or modify sponsor logos.
- Do **not** invent or assume sponsor logos.
- Place sponsors inside a stylish white sponsor strip/box at the bottom.
- The sponsor strip should match the overall poster design and not look like a plain rectangle.

---

## Information to Include
Only include information provided by the user or extracted from the source image/link.

Typical matchday poster fields:

- Tournament / league
- Season / division / team if provided
- Date
- Matchup
- Home or away status if provided
- Venue / ground if provided
- Playing XI
- Captain marker if provided, e.g. `(C)`
- FrogBox / streaming only if present in the original source and the user wants it included

---

## Information to Exclude
Never include these unless the user specifically asks:

- Reporting time
- Match time
- Tea information
- Jersey colour
- Internal team changes
- Private/internal instructions
- Points
- Extra notes not present in the source
- Imagined logos
- Imagined sponsors
- Extra facts from assumption

For public Instagram posters, remove internal logistics.

---

## Layout Structure

### Top Section
- LDCC logo at top-left
- Small league/tournament label
- Strong “MATCHDAY” or similar headline

### Main Section
- Left side: cricketer silhouette/action player visual
- Centre/right: team matchup
- Use text-only VS section unless logos are supplied

### Details Section
Include clean blocks for:

- Date
- Venue / ground
- Home or away
- League / division

Only include fields that are available.

### Playing XI Panel
- Place Playing XI on the right side or lower-right panel
- Keep names readable
- Highlight captain if provided
- Do not add players not provided

### Bottom Sponsor Section
- Stylish white sponsor strip
- Sponsor logos placed clearly and evenly
- Instagram handle near bottom or above sponsor strip

---

## Text Handling Rules
- Preserve player names exactly as supplied.
- Preserve team names exactly as supplied.
- Fix obvious spelling only if clearly accidental and safe.
- Do not shorten names unless space requires it.
- If names are too long, reduce font size or use two lines instead of removing players.

---

## Source Handling
The user may provide match details as:

1. Text
2. Image screenshot
3. Play-Cricket link
4. Previous poster template

When extracting from an image:
- Use only visible information from the image.
- Do not add missing details.
- Ask only if critical information is missing; otherwise make the best poster with available details.

When using a previous poster as a template:
- Match the same theme, spacing, hierarchy, and mood.
- Update only the match-specific information.

---

## Quality Checklist Before Finalising
Before generating the poster, ensure:

- Size is Instagram portrait 4:5
- LDCC logo is top-left if supplied
- No opponent logo is invented
- Sponsor logos are unchanged
- Sponsor strip has white background and looks integrated
- Instagram handle is `@londondesperados`
- No reporting time or match time unless explicitly requested
- Playing XI names are complete and correct
- Poster uses gritty dark blue/red LDCC style
- Text is readable on mobile
- No extra information has been added

---

## Example User Request
“Create a matchday poster for LDCC using this match information.”

## Expected Behaviour
Create a polished LDCC Instagram matchday poster using only the supplied match details and the rules above.
