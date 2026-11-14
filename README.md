# Chinese Learning Lab — Phase 1

This static site package uses the approved five-course homepage artwork and builds the first working path:

**Homepage → Chinese 1 → Unit 2 → Listening Lab**

## Included
- Approved five-course homepage image with responsive keyboard-accessible hotspots.
- Functional links for Chinese 1, Chinese 2/2H, Chinese 3H, Chinese 4H, AP Chinese, and Learning Resources Library.
- Chinese 1 course page with Unit 2 available and Units 1/3 marked Coming Soon.
- Unit 2 dashboard with six activity categories.
- Student Listening Lab using the exact 15 provided phrases/sentences.
- Browser Mandarin text-to-speech with 0.78× default speed, speed options, and ~0.55 s punctuation pauses.
- Name-specific browser-local autosave, automatic progress, clear-with-confirmation.
- Copy Answers, Print My Answers, and a self-contained browser-generated PDF download (no external PDF library required).
- Separate teacher display with Chinese script and English-key show/hide controls.
- Course/library placeholders for future expansion without invented curriculum.

## Important limitations
- Browser localStorage is convenience storage, not secure authentication or a teacher submission system.
- A separate teacher URL is not secure access control. Put teacher resources behind Google Classroom/Google Workspace/LMS authentication for real protection.
- Browser text-to-speech varies by device and installed voices. Chrome/Edge with a zh-CN voice is recommended. The data structure can later point to teacher-recorded MP3 files.

## Publish for Google Classroom
### Simple option: Netlify Drop
1. Unzip the package.
2. Go to Netlify Drop and drag the entire `chinese_learning_lab_site` folder onto the page.
3. Netlify creates a public HTTPS site URL.
4. Post that URL in Google Classroom as Material or an Assignment link.

### GitHub Pages
1. Create a repository.
2. Upload the contents of this folder to the repository root.
3. In repository Settings → Pages, deploy from the main branch/root.
4. Post the published site URL in Google Classroom.

Students should open the hosted URL directly; they do not need to download HTML files.

## Add a future activity
Create a new activity page in the relevant course/unit folder and place shared content/data in `assets/js/`. Reuse the site styles in `assets/css/`. Keep course, unit, activity title, instructions, Chinese content, optional English/key, optional audio, and activity type as separable data so activities do not require a homepage redesign.
