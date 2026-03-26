# Creator to Fastr Bulk Migration Skill - Development Notes

**Thread Date:** March 25-26, 2026
**Participants:** Charmi Chhaya (QA/Testing), PK (Developer)

## Overview
Iterative development of a bulk migration skill to convert experiences from Creator platform to Fastr platform. Testing done on experiences #80-100.

## Initial Version Issues (v1)
**Testing:** 20 experiences, 75 minutes total

### Problems Found:
1. **Performance:** 75 minutes for 20 experiences, asked for multiple permissions even with bypass mode on
2. **Duplicate Experiences:** Created 2 separate experiences per page (Desktop and Mobile) but both were identical with desktop and tablet variants
3. **Font Issues:** Some fonts accurate, others show "missing font" in text panel
4. **Carousel Handling:** Mixed results
   - ✅ Works: Regular carousels (example: 99th experience)
   - ❌ Fails: Embedded carousels, arrows render as blank shapes (82nd experience)
5. **Layout Issues:** Scenes overlapping, extra objects outside boards (98th experience)
6. **Button & Text:** Button shapes broken, text alignment off (87th experience)

## Second Version (v2)
**Testing:** 7 experiences, 9 minutes total ⚡

### Improvements:
- ✅ **85% faster** (9 mins vs 75 mins per same quantity)
- ✅ **Single experience** per page (no more duplicates)
- ✅ **Some fonts** now pulling through correctly

### Remaining Issues:
1. **Buttons:** Still broken/misshapen
2. **Fonts:** Some still show "missing font" (manual fix possible)
3. **Excel Reading:** Off-by-one error - reading wrong rows (wanted 98th, got 99th)
4. **Carousel Pages:** Boards created but appearing all black (#98 carousel)

## Third Version (v3)
**Status:** In testing

### Latest Issue:
- Boards are being created and moved correctly
- **Objects on boards are not rendering** - boards appear blank
- Example: 98th carousel page has empty boards

## Technical Notes
- Platform used: Claude Code desktop app (not Cowork or terminal)
- Source: Creator experiences
- Target: Fastr Next workspace
- Excel doc drives which experiences to migrate (starting at cell 2)

## Key Takeaway
The skill is rapidly improving - from 75 minutes to 9 minutes is a huge win. Main blockers now are:
1. Object rendering on boards (critical)
2. Button shape rendering
3. Excel row mapping accuracy
4. Font fallback handling

---
*Last Updated: March 26, 2026*
