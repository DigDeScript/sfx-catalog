# Website catalog format

`sfx-catalog.md` contains YAML front matter followed by Markdown. This is a proposed version-1 contract for the future website importer; synchronization is not yet implemented.

- `id`: stable product identifier and URL slug.
- `category`: `software` or `plugins`.
- `status`: `published` or `draft` for the product description, not the package release.
- `release_repository`: repository whose published stable release supplies version, publication date and download asset.
- `image_dark` and `image_light`: repository-relative screenshot paths.

Version and release date are intentionally not duplicated in front matter. Import only a validated, published, non-prerelease release; do not expose draft assets. Preserve the last good local copy if synchronization fails. Render Markdown with raw HTML disabled and validate links and asset paths.
