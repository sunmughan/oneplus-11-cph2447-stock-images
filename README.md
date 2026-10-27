# OnePlus 11 CPH2447 Stock Partition Images

Stock partition images for the **OnePlus 11 (CPH2447)**, build
**CPH2447_16.0.5.1301 ONLY** (OxygenOS 16), for recovery use.

## Warning

- These images are ONLY for build CPH2447_16.0.5.1301. Do NOT flash
  them onto any other build: a mismatched image risks a bootloop.
- Before flashing anything, verify the phone's current build matches
  CPH2447_16.0.5.1301 exactly, and keep a backup of the partition
  you are replacing.
- Flash each image ONLY to its matching partition and slot
  (for example, `init_boot.img` goes to the `init_boot` partition of
  the active slot, never to `boot` or `vendor_boot`).

## Files

All images are attached to the GitHub Release on this repo (see
Releases), because files over 100 MB cannot live in the repo itself.
Download links for every image, with sizes and SHA-256 hashes, are in
the release notes.

## Split files

`my_product.img` (2.7 GB) and `my_stock.img` (2.9 GB) are larger
than GitHub's 2 GB per-asset limit, so each is split into two parts
under 2 GB (`.part1`, `.part2`). Rejoin them in order before use:

```
cat my_product.img.part1 my_product.img.part2 > my_product.img
cat my_stock.img.part1 my_stock.img.part2 > my_stock.img
```

After rejoining, verify the SHA-256 against the hash in the release
notes before flashing.

## Source

Extracted and verified (per-operation SHA-256 plus final partition
SHA-256 against the OTA manifest) from the official
CPH2447_16.0.5.1301 `payload.bin`.
