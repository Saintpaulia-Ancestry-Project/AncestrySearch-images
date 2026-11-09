# AncestrySearch-images

African violet (*Saintpaulia*) cultivar photographs for the
[Saintpaulia Ancestry search site](https://saintpaulia-ancestry-project.github.io/AncestrySearch/).
The site's code and data are in the [AncestrySearch](https://github.com/Saintpaulia-Ancestry-Project/AncestrySearch)
repository.

## What is here

```
photos/   full-size photos (longest side 1600 px, WebP)
thumbs/   thumbnails of the same photos (longest side 400 px, WebP)
```

A photo has the same file name in both folders: `<cultivar-id>-<number>.webp`, for example
`rob-s-lucky-penny-1.webp`. The cultivar id is the name used in the cultivar's page address on the site.

## Credits

The photographer credit and caption for every photo are recorded in `data/images.csv` in the
AncestrySearch repository, and are shown under each photo on the site.

## Copyright

Each photo remains the property of the photographer credited for it. Please do not reuse photos from
this repository without the photographer's permission.

## Adding photos

Do not add files here by hand. Use `scripts/add_images.py` in the AncestrySearch repository, which names,
resizes and records each photo, strips camera metadata such as GPS location, and keeps the credit list in
step. See "Adding photos" in that repository's README.
