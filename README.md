# BoardBridge — CBSE Class XII Study Hub

A simple GitHub Pages site for Class XII students. The 2026–27 subject and chapter lists are based on the official CBSE subject curriculum PDFs. Physics currently has starter notes, formulae, derivation checklists, cautions and five original concept questions per chapter. Other subjects have the official chapter/unit structure and concise topic checklists.

## Run locally
Download all four website files into the same folder and open `index.html` in a browser:
- `index.html`
- `styles.css`
- `content.js`
- `app.js`

No package installation or server is needed.

## Publish using GitHub Pages
1. Sign in at https://github.com/ and create a new public repository, for example `boardbridge-class12`.
2. On the repository page choose **Add file → Upload files**.
3. Upload all four files above (keep them in the repository root, not inside an extra nested folder).
4. Add this `README.md` too if you want project instructions visible on GitHub.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch `main` and folder `/(root)`, then click **Save**.
8. Wait for the deployment. GitHub Pages will show the public URL, usually `https://YOUR-USERNAME.github.io/boardbridge-class12/`.

When you change the code later, upload/commit the updated files to `main`; Pages redeploys automatically.

## Accuracy and coverage notes
- This is a learning aid, not an official CBSE site. Verify your school subject combination and the current curriculum PDF.
- The current Physics question bank contains five original concept-check questions per chapter. It is not a complete 30–40 question mock, and these are not labelled as PYQs.
- PYQs are linked to the official CBSE archive instead of being copied into the repository. Match each paper to the relevant year, subject code and current syllabus before using it.
- The other four subjects have chapter lists and topic checklists; full notes and reviewed question banks still need to be added.
- Do not use commercial guidebook scans or republish copyrighted question papers without permission.

## Edit content
- `content.js` contains the subject chapter lists, Physics study notes, topic checklists and question bank.
- `app.js` contains the navigation, timer, quiz scoring and local progress logic.
- Questions use four options and a zero-based correct answer index (`a: 0` means option A).
