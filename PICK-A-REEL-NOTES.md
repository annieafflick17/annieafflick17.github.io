# "Pick a reel" Editing page (saved for later)

This branch holds a redesigned Editing page that isn't live yet.

- Clicking **Editing** opens a "Pick a reel" screen with three film reels:
  **Narrative**, **Documentary** and **Music Video**.
- Choosing a reel opens the film strip with only that category's projects.
  A list on the left switches categories, and "← All reels" goes back.
- A category with no projects shows a "Coming soon" card.

Current sorting:

| Project | Category |
| --- | --- |
| When Silence Meets the Shore | Documentary |
| Harlequins | Narrative |
| Gone Wrong | Narrative |

## Adding a project

Each project in `index.html` (in the `allProjects` list) has a `category:`
line set to `"narrative"`, `"documentary"` or `"music-video"`.

## Publishing

When you're ready, merge this branch into `main`. GitHub Pages will publish
it within a few minutes. Any changes made to `main` in the meantime need to
be carried over.
