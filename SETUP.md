# Echo-Nexus GitHub Profile README

## Files

- `README.md` — profile README template
- `assets/echo-nexus-banner.png` — generated futuristic hero banner
- `.github/workflows/snake.yml` — GitHub Actions workflow to generate and publish the contribution snake

## Install

1. Create or open the **public** GitHub repository named exactly `Echo-Nexus` (the username repository).
2. Put `README.md` at the repository root.
3. Put `echo-nexus-banner.png` inside `assets/`.
4. Put `snake.yml` at `.github/workflows/snake.yml`.
5. Commit and push all files to the default branch.
6. Open the repository's **Settings → Actions → General** and ensure workflows are allowed to run. The workflow needs `contents: write`; the YAML declares that permission.
7. Open **Actions → Generate contribution snake** and select **Run workflow**. After it succeeds, the workflow publishes the SVG files to an `output` branch.
8. Wait for GitHub's profile README cache to refresh. The snake image should then load.

## Personalize

- The username in the stats, snake image URLs, and workflow is `Echo-Nexus`.
- Verify that `https://github.com/Echo-Nexus/breadbox` is the intended public repository URL.
- The README intentionally does not invent contact links. Uncomment and update the LinkedIn/email badges only after adding your real links.
- SwiftBasket, Real-Time Chat Lab, and AI Study Workspace currently link to your repository list or are marked as a concept until you set their exact public repository URLs.
- Remove any technology icon that you do not actively use or learn.

## Notes

- The typing animation uses `readme-typing-svg.demolab.com`.
- GitHub stats and streak images are third-party hosted services and can occasionally be unavailable, rate-limited, or slow. They are optional; remove a card if it breaks.
- GitHub README content supports Markdown and limited HTML, but not custom JavaScript or CSS. Animations should be hosted GIFs/SVGs/images.
- The banner is an image, not editable HTML. Replace it with your own optimized banner later if desired.


## If the GitHub Overview cards do not load

These cards are images from third-party services, so they can fail independently of your README.

1. Open each exact image URL in a new browser tab.
2. If a card endpoint returns an error, wait and retry; GitHub also caches README images.
3. The stats cards use GitHub Stats Extended, and the streak card uses `streak-stats.demolab.com`.
4. For maximum reliability, self-host the stats service or generate static cards through GitHub Actions.
