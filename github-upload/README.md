# வளைகாப்பு அழைப்பிதழ் — Valaikappu Invitation

A single-file, offline-capable digital invitation for **A S தர்ஷினி w/o A H ஸ்ரீராம்**'s வளைகாப்பு.

## Live

Enable **Settings → Pages → Deploy from branch → main / root**. The invitation is served from `index.html`.

## Contents

| File | What it is |
| --- | --- |
| `index.html` | The complete invitation — all images, fonts and scripts inlined. Works offline, no build step. |
| `Valaikappu Invitation.html` | Identical copy under a friendly filename. |
| `src/Valaikappu Invitation Responsive.dc.html` | Editable source. |
| `src/art/` | Original artwork used by the source. |

## Notes

- Mobile-first, with a tablet breakpoint at 768px.
- Motion respects `prefers-reduced-motion`.
- Regenerating `index.html` requires re-bundling the source; edit the source, not the bundled file.
