# Website catalog format

`sfx-catalog.md` contains YAML front matter followed by Markdown. The DigDeScript website uses this version-1 contract to import the product description.

- `schema_version`: contract version; currently `1`.
- `title`: product display name.
- `platform`: supported platform description; technical metadata, not a marketing headline.
- `summary`: short plain-text product summary.
- `website`: official HTTPS product page URL.
- `id`: stable product identifier and URL slug.
- `category`: `software` or `plugins`.
- `status`: `published` or `draft` for the product description, not the package release.
- `release_repository`: repository whose published stable release supplies version, publication date and download assets.
- `image_dark` and `image_light`: repository-relative screenshot paths.

The website imports the `## Free and Pro` section for its feature comparison and uses metadata and release assets for product identity and downloads. Other Markdown sections remain useful GitHub documentation; they are not rendered as the entire sales page. Keep this heading stable. Prices, promotions, checkout URLs and membership links belong exclusively to website commerce configuration, not this document. A bundled comparison is used when GitHub is unavailable.

Version and release date are intentionally not duplicated in front matter. Import only a validated, published, non-prerelease release; do not expose draft assets. Preserve the last good local copy if synchronization fails. Render Markdown with raw HTML disabled and validate links and asset paths.
