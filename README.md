# Rastikerdar Persian Fonts for Debian

A collection of Persian and Arabic fonts packaged for Debian-based Linux distributions.

This repository provides a Debian package containing nine font families, originally developed and published as open-source projects.

## Included Font Families

| Font Family | Description |
|---|---|
| Gandom | Persian typeface |
| Nahid | Persian typeface |
| Parastoo | Persian typeface |
| Sahel | Persian typeface |
| Samim | Persian typeface |
| Shabnam | Persian typeface |
| Tanha | Persian typeface |
| Vazir Code | Monospaced typeface for programming |
| Vazirmatn | Persian and Arabic typeface |

The package includes the available TrueType (`.ttf`) font files across the included families and their variants.

## Package Information

| Property | Value |
|---|---|
| Package name | `fonts-rastikerdar` |
| Version | `1.0.0-1` |
| Architecture | `all` |
| Section | `fonts` |
| Maintainer | Amin Mahmudian |
| License | Multiple open-source licenses |

## Installation

Download the latest `.deb` package from the [GitHub Releases](https://github.com/aminone/fonts-rastikerdar/releases) page.

Install it using:

```bash
sudo apt install ./fonts-rastikerdar_1.0.0-1_all.deb
```

Alternatively, install it with `dpkg`:

```bash
sudo dpkg -i fonts-rastikerdar_1.0.0-1_all.deb
```

If dependencies are missing, run:

```bash
sudo apt --fix-broken install
```

After installation, the fonts are available system-wide.

## Package Contents

The Debian package includes:

- TrueType (`.ttf`) font files from all nine font families.
- Original README and changelog files, where available.
- Upstream license files.
- Author information and documentation.

Web-specific font formats such as WOFF, WOFF2 and EOT, as well as CSS files and sample images, are not included in the Debian package.

## Licenses

The included font families are distributed under their respective upstream licenses.

Depending on the font family and its included components, these include:

- SIL Open Font License 1.1
- Apache License 2.0
- Bitstream Vera license
- Public domain contributions

Some font families incorporate glyphs or other components from third-party projects. Their respective copyright and license notices are preserved.

For complete license information, see the `docs/licenses/` directory and the Debian copyright file included in the package.

## Upstream Projects

The original font projects and their documentation are available on the author's project website:

[Rastikerdar Font Projects](https://rastikerdar.github.io/)

## In Memory of Saber Rastikerdar

This package is dedicated to the memory of **Saber Rastikerdar (1986–2023)**.

His work made a lasting contribution to Persian digital typography and helped make high-quality Persian fonts freely accessible to developers, designers, and users.

His contributions continue to be used and appreciated.

## Repository

Source code and package development:

[github.com/aminone/fonts-rastikerdar](https://github.com/aminone/fonts-rastikerdar)
