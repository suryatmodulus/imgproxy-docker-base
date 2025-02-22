# Changelog

## [Unreleased]

## [3.3.4] - 2022-11-17
### Changed
- Update Go to 1.19.3.
- Update GLib to 2.75.0.
- Update libexpat to 2.5.0.
- Update lcms2 to 2.14.
- Update libde265 to 1.0.9.
- Update libheif to 1.14.0.
- Update gdkpixbuf to 2.42.10.
- Update fontconfig to 2.14.1.
- Update harfbuzz to 5.3.1.
- Update pixman to 0.42.2.
- Update vips to 8.13.3.

## [3.3.3] - 2022-10-19
### Changed
- Update libxml2 to 2.10.3.
- Update harfbuzz to 5.3.0.
- Update pixman to 0.42.0.

### Fix
- Patch libvips to fix saving of paletted PNGs with low bit-depth.

## [3.3.2] - 2022-10-06
### Changed
- Update Go to 1.19.2.
- Update GLib to 2.74.0.
- Update libexpat to 2.4.9.
- Update libxml2 to 2.10.2.
- Update aom to 3.5.0.
- Update libheif to 1.13.0.
- Update harfbuzz to 5.2.0.
- Update pango to 1.50.11.
- Update librsvg to 2.55.1.
- Update vips to 8.13.2.

## [3.3.1] - 2022-08-19
### Changed
- Update Go to 1.19.
- Update GLib to 2.73.3.
- Update Quantizr to 1.4.1.
- Update libxml2 to 2.10.0.
- Update libjpegturbo to 2.1.4.
- Update libwebp to 1.2.4.
- Update gdkpixbuf to 2.42.9.
- Update harfbuzz to 5.1.0.
- Update pango to 1.50.9.
- Update librsvg to 2.55.0.
- Patch libvips to speed up GIF loading.

## [3.3.0] - 2022-07-25
### Add
- Add libspng 0.7.2.

### Changed
- Update Go to 1.18.4.
- Update GLib to 2.73.2.
- Update Quantizr to 1.3.0.
- Update libwebp to 1.2.3.
- Update libtiff to 4.4.0.
- Update aom to 3.4.0.
- Update harfbuzz to 4.4.1.
- Update pango to 1.50.8.
- Update librsvg to 2.54.4.
- Update vips to 8.13.0.
- Patch libheif.

## [3.2.4] - 2022-05-20
### Fix
- Fix dav1d plugin of libheif.

## [3.2.3] - 2022-05-15
### Changed
- Update Go to 1.18.2.
- Update GLib to 2.72.1.
- Update libxml2 to 2.9.14.
- Update cgif to 0.3.0.
- Update freetype to 2.12.1.
- Update harfbuzz to 4.2.1.
- Update fribidi to 1.0.12.
- Update pango to 1.50.7.
- Update librsvg to 2.54.3.

### Fix
- Patch libvips to not fail on PNGs with to many text chunks.

## [3.2.2] - 2022-04-13
### Changed
- Update Go to 1.18.
- Update GLib to 2.72.0.
- Update Quantizr to 1.2.0.
- Update libexpat to 2.4.8.
- Update libxml2 to 2.9.13.
- Update libjpegturbo to 2.1.3.
- Update cgif to 0.2.1.
- Update dav1d to 1.0.0.
- Update aom to 3.3.0.
- Update gdkpixbuf to 2.42.8.
- Update freetype to 2.12.0.
- Update fontconfig to 2.14.0.
- Update harfbuzz to 4.2.0.
- Update cairo to 1.17.6.
- Update pango to 1.50.6.
- Update librsvg to 2.54.0.

### Fix
- Patch nsgif in vips code to recover from LZW_EOI_CODE.

## [3.2.1] - 2022-02-11
### Fix
- Fix `CFLAGS` for amd64 build.

## [3.2.0] - 2022-02-07
### Added
- Add libaom 3.2.0.

### Changed
- Update lcms2 to 2.13.1.
- Update fontconfig to 2.13.96.
- Update harfbuzz to 3.3.2.

### Removed
- Remove rav1e.

## [3.1.0] - 2022-01-31
### Added
- Multiarch build.

### Changed
- Update Go to 1.17.6.
- Update GLib to 2.71.1.
- Update libexpat to 2.4.4.
- Update libexif to 0.6.24.
- Update lcms2 to 2.13.
- Update Quantizr to 1.1.0.
- Update libwebp to 1.2.2.
- Update rav1e to 0.5.1.
- Update freetype to 2.11.1.
- Update harfbuzz to 3.2.0.
- Update pango to 1.50.3.
- Update vips to 8.12.2.

## [3.0.1] - 2021-11-22
### Added
- Add cgif 0.0.2.

### Changed
- Update Go to 1.17.3.
- Update GLib to 2.70.1.
- Update libjpegturbo to 2.1.2.
- Update libpng to 1.6.37.
- Update Quantizr to 1.0.1.
- Update rav1e to 0.5.0.
- Update freetype to 2.11.0.
- Update harfbuzz to 3.1.1.
- Update pango to 1.49.3.
- Update vips to 8.12.0.

### Removed
- Remove ImageMagick.

## [3.0.0] - 2021-09-29
### Changed
- Update Go to 1.17.1.
- Update GLib to 2.70.0.
- Update libexif to 0.6.23.
- Update libjpegturbo to 2.1.1.
- Update libwebp to 1.2.1.
- Update dav1d to 0.9.2.
- Update fontconfig to 2.13.94.
- Update harfbuzz to 3.0.0.
- Update fribidi to 1.0.11.
- Update pango to 1.49.1.
- Update ImageMagick to 7.1.0-8.
- Update vips to 8.11.4.

## [1.4.0] - 2021-06-10
### Changed
- Use Debian Bullseye as a base.
- Reduce final image size by using multistage build.
- Update GLib to 2.68.2.
- Update libexpat to 2.4.1.
- Update libxml2 to 2.9.12.
- Update libjpegturbo to 2.1.0.
- Update libtiff to 4.3.0.
- Update dav1d to 0.9.0.
- Update rav1e to 0.4.1.
- Update libheif to 1.12.0.
- Update gdkpixbuf to 2.42.6.
- Update harfbuzz to 2.8.1.
- Update pango to 1.48.5.
- Update librsvg to 2.50.7.
- Update ImageMagick to 7.0.11-14.
- Update vips to 8.11.0.

### Fix
- Fix librsvg panics when processing some SVGs.

### Removed
- Remove giflib (libvips has builtin libnsgif now).

## [1.3.2] - 2021-03-04
### Changed
- Update GLib to 2.67.5.
- Update lcms2 to 2.12.
- Update libwebp to 1.2.0.
- Update libtiff to 4.2.0.
- Update dav1d to 0.8.2.
- Update rav1e to 0.4.0.
- Update libheif to 1.11.0.
- Update harfbuzz to 2.7.4.
- Update pango to 1.48.2.
- Update librsvg to 2.50.3.
- Update ImageMagick to 7.0.11-2.
- Update vips to 8.10.5.

## [1.3.1] - 2020-12-15
### Changed
- Update GLib to 2.67.0.
- Update libexpat to 2.2.10.
- Update libjpegturbo to 2.0.90.
- Update libde265 to 1.0.8.
- Update dav1d to 0.8.0.
- Update gdkpixbuf to 2.42.2.
- Update freetype to 2.10.4.
- Update fontconfig to 2.13.93.
- Update pango to 1.48.0.
- Update librsvg to 2.50.2.
- Update ImageMagick to 7.0.10-48.
- Update libvips to 8.10.4.

## [1.3.0] - 2020-09-15
### Added
- Add rav1e 0.3.4.
- Add dav1d 0.7.1.

# Removed
- Remove libaom.

## [1.2.0] - 2020-09-15
### Added
- Add libaom 2.0.0.

### Changed
- Update GLib to 2.66.0.
- Update harfbuzz to 2.7.2.
- Update librsvg to 2.50.0.
- Update ImageMagick to 7.0.10-29.
- Update libvips to 8.10.1.

## [1.0.4] - 2020-08-27
### Changed
- Update GLib to 2.65.2.
- Update libde265 to 1.0.6.
- Update libheif to 1.8.0.
- Update harfbuzz to 2.7.1.
- Update pango to 1.46.1.
- Update librsvg to 2.49.4.
- Update ImageMagick to 7.0.10-28.

## [1.0.3] - 2020-08-11
### Changed
- Update GLib version to 2.65.1.
- Update libjpegturbo version to 2.0.5.
- Update harfbuzz version to 2.7.0.
- Update fribidi version to 1.0.10.
- Update pango version to 1.46.0.
- Update librsvg version to 2.49.3.
- Update ImageMagick version to 7.0.10-26.
- Update libvips version to 8.10.0.

## [1.0.2] - 2020-07-09
### Fix
- Fix libde265 build

## [1.0.1] - 2020-06-22
### Changed
- Update GLib version to 2.65.0.
- Update lcms2 version to 2.11.
- Update ImageMagick version to 7.0.10-20.

## [1.0.0] - 2020-06-16
### Added
- First release.
