# License
The source code in this repository is licensed under the MIT License.  
Branding assets (logo, ABC Arizona font, screenshots) are **not** covered by this licence; see the Assets section for details.
``` |

---

## 2️⃣ Separate the **Proton** Assets

### a) Don’t commit them to the public repo  
- Store the logo, font, and any screenshots **outside** the repository (local folder, private cloud, or a separate private GitHub repo).  
- Add the folder name to `.gitignore` (e.g., `assets/proton/`). This prevents accidental leaks and keeps the public history clean.

### b) Document the assets in a dedicated file  
Create `ASSETS/LICENSE` (or `ASSETS/README`) that says exactly how you’re handling Proton’s stuff:

```text
Proton AG Branding Assets
-------------------------

The following files are used **solely for a non‑commercial Bootcamp project**:

- Proton logo (SVG/PNG)
- ABC Arizona typeface (WOFF2)
- UI screenshots taken from proton.me

These assets are **not** covered by the MIT licence applied to the source code.
They remain the exclusive property of Proton AG.

Usage:
- Displayed only in the internal class presentation.
- Not redistributed, published, or sold.
- If Proton grants explicit permission, the permission notice will be added here.

© Proton AG. Used with permission for an educational project.  
All other code © Sir~ 2026, licensed under MIT.
