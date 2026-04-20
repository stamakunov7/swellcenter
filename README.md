# The Swell Center (BSAN E-Business Prototype)

This project is a beginner-friendly static web application prototype for a college e-business assignment. It represents **The Swell Center**, a wellness center that combines fitness, mental wellness, recovery services, and appointment booking.

## Project Files

- `index.html` - Home page with business overview and call-to-action.
- `services.html` - Services page with a structured table.
- `booking.html` - Booking page with an accessible appointment form.
- `style.css` - Shared responsive styles for all pages.
- `paper-draft.md` - Draft APA-style write-up for the assignment submission.

## How to Run Locally in GitHub Codespaces

1. Open this repository in GitHub Codespaces.
2. In the terminal, run:

   ```bash
   python3 -m http.server 8000
   ```

3. Open the **Ports** panel in Codespaces and click the forwarded URL for port `8000`.
4. The homepage will be available at `index.html`.

## How to Publish with GitHub Pages

1. Push your project files to your GitHub repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/ (root)`
4. Click **Save**.
5. Wait for deployment, then open the published URL shown in the Pages settings.

## Notes

- The app uses only HTML and CSS (no framework).
- All links are relative to support GitHub Pages.
- You can replace placeholder text and image URLs with your final content before submission.
