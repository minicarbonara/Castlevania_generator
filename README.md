# Castlevania Generator

## What I'm building

A simple HTML+CSS+JS minisite that will generate a randomized title and sinopsis for a made up game in the Castlevania series. The title will be follow the structure "Castlevania: XXXX of YYYY" picking from two arrays, while the sinopsis will be a sort of limerick using story staples of the series. The whole thing will be styled to look gloomy and goth, and to look good on both mobile and desktop browsers.

---

## How I'm building it

Several development phases:

### 1. General visual structure

- Hand-draw UI sketch and wireframe
- Define general div structure over sketch
- Code general div structure with dummy title and sinopsis (Lorem ipsum)
- Style basic divs just for position
- Set media queries telling mobile and desktop browsers apart

### 2. Basic styling

- Select Google fonts for title and block text
- Find png Castlevania logo, texture img for general BG and text BG
- Apply fonts and colors to dummy texts, adjust positioning
- Load BG images and adjust scaling and/or mosaic

### 3. Writing the base text

- Create a basic sinopsis structure with `<span>` applying unique IDs to the replaceable texts
- Apply unique IDs to the two replacers in the title
- Set the action button and script to randomize each ID'd text from a diff. array
- Test and adjust spacing/position if needed

### 4. Filling the arrays

- Fill up the different arrays with at least 6 options each
- Test some more for text size variation

### 5. Getting fancy

- Play with a one-time animation to fade in the UI on first load
- Play with refresh animations when the text is re-randomized