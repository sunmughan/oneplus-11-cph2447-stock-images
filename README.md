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

All 47 partition images live in this repo, in the root directory:

- Files under 100 MB are normal git files.
- Files over 100 MB (`boot.img`, `vendor_boot.img`, `modem.img`,
  `recovery.img`, `vendor_dlkm.img`, `system.img`, `system_ext.img`,
  `vendor.img`, `odm.img`) are stored with Git LFS. To clone them,
  install Git LFS first (`git lfs install`), then clone normally;
  or download any single file from its raw link on GitHub.
- `my_product.img` (2,897,543,168 bytes) and `my_stock.img`
  (3,079,491,584 bytes) are larger than GitHub's 2 GiB per-object
  limit, so each is stored as two Git LFS parts under 2 GiB
  (`.part1`, `.part2`). Rejoin them in order before use:

```
cat my_product.img.part1 my_product.img.part2 > my_product.img
cat my_stock.img.part1 my_stock.img.part2 > my_stock.img
```

  After rejoining, verify the SHA-256 against `MANIFEST.md`
  before flashing.

`MANIFEST.md` in this repo lists every file with its exact byte size
and SHA-256 hash. Verify a downloaded file with
`sha256sum <file>` before flashing.

## Source

Extracted and verified (per-operation SHA-256 plus final partition
SHA-256 against the OTA manifest) from the official
CPH2447_16.0.5.1301 `payload.bin`.
