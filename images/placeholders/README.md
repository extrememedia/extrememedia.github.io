# Placeholder Images — replace before launch

Every photo on the site comes from this folder. The files shipped here are
**generated, on-brand gradient panels** (not real photos) so the site looks
finished out of the box. **Replace them with real Highlands photography before
you launch.**

## How to replace a photo

**The easy way:** drop your real photo here using the **same filename** (e.g.
`students-learning.jpg`). Nothing else to change.

**The flexible way:** put your photo anywhere under `public/images/` and update
the matching `src` in [`data/images.ts`](../../../data/images.ts). Always update
the `alt` text there too, for accessibility and SEO.

## Tips for great photos
- Use warm, natural light and real, candid school moments.
- Landscape (3:2) works best for most slots; the gallery also uses squares.
- Aim for ~1600×1067px, optimized JPGs (under ~400 KB each).
- Get photo/media permission for any identifiable students.

## Filename → where it's used

| Filename | Used for |
|----------|----------|
| `hero-campus.jpg` | Home hero background |
| `students-learning.jpg` | Academics, mega menu |
| `classroom-smiling.jpg` | Employment |
| `preschool-play.jpg` | Preschool program & admissions |
| `elementary-reading.jpg` | Elementary program |
| `middle-school-project.jpg` | Middle school program |
| `chapel-worship.jpg` | Faith / statements |
| `athletics.jpg` | Athletics, programs |
| `campus-life.jpg` | About, campus life, gallery |
| `teacher-student.jpg` | Character, parent resources |
| `family-tour.jpg` | Admissions, contact |
| `science-lab.jpg` | Academics, gallery |
| `music-arts.jpg` | Gallery, arts |
| `library-reading.jpg` | Gallery |
| `playground.jpg` | Gallery, preschool |
| `summer-camp.jpg` | Summer camp |
| `extended-care.jpg` | Extended care |
| `outreach-service.jpg` | Outreach |
| `graduation.jpg` | About, accreditation |
| `art-class.jpg` | Gallery |

## Regenerate or fetch stand-ins
- Regenerate branded placeholders: `npm run images`
- Print royalty-free photo search links (Unsplash/Pexels): `npm run fetch-images`
- Download quick photographic stand-ins: `bash scripts/download-images.sh --fetch`
