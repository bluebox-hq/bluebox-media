# bluebox-media

Public image and video assets for emails and blog posts. GitHub Pages serves every file in this repo at a public URL.

**Everything here is public.** Do not upload unreleased or confidential material. Git history keeps deleted files.

## Link format

```
https://bluebox-hq.github.io/bluebox-media/<path-in-repo>
```

The site root (`https://bluebox-hq.github.io/bluebox-media/`) returns 404 because there is no `index.html`. File links work.

## Assets

### Images

| Asset | Link |
|---|---|
| Email background | https://bluebox-hq.github.io/bluebox-media/images/2026/bluebox-email-background.jpg |
| Lockup, white | https://bluebox-hq.github.io/bluebox-media/images/2026/bluebox-lockup-white.png |
| Signature logo | https://bluebox-hq.github.io/bluebox-media/images/2026/bluebox-signature-logo.png |
| Overview preview GIF | https://bluebox-hq.github.io/bluebox-media/images/2026/bluebox-overview-preview.gif |
| Routines preview GIF | https://bluebox-hq.github.io/bluebox-media/images/2026/bluebox-routines-preview.gif |

### Video

| Asset | Link |
|---|---|
| Overview video | https://bluebox-hq.github.io/bluebox-media/video/2026/bluebox-overview-video.mp4 |
| Routines demo video | https://bluebox-hq.github.io/bluebox-media/video/2026/bluebox-routines-demo.mp4 |

## Folder layout

```
images/<year>/   images and GIFs
video/<year>/    video files
```

## Add an asset

1. On the **Code** tab, open the target folder, for example `images/2026/`.
2. Click **Add file → Upload files**. Files upload into the open folder.
3. Drag in the files.
4. Click **Commit changes** and select **Commit directly to the `main` branch**.
5. Wait for the **pages build and deployment** run on the **Actions** tab to turn green.
6. Open the link in a private browser window to confirm it loads.
7. Add the asset to the tables above.

To create a new folder, click **Add file → Create new file**. Type the path, for example `images/2027/`, then name the file `.gitkeep`.

## Rules

- Use lowercase file names with hyphens. Do not use spaces, because spaces become `%20` in the link.
- Do not rename, move, or overwrite a file after its link is in a sent email or a published post. Upload a new file with a new name.
- The maximum file size is 100 MB. The web upload accepts files up to 25 MB. Use `git` or GitHub Desktop for larger files.
- Do not use Git LFS. GitHub Pages does not serve LFS files.
- Keep files small. Most email clients do not play video, so link a preview image or GIF to the video.
