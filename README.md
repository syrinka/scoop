# Syr's Scoop Bucket

[![Tests](https://github.com/syrinka/scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/syrinka/scoop/actions/workflows/ci.yml) [![Excavator](https://github.com/syrinka/scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/syrinka/scoop/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add syr https://github.com/syrinka/scoop`. To install, do `scoop install <manifest>`.

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

## Featured APPs

Manifest | Description
-- | --
cygwin-alter | A fork of cygwin, made some minor changes:</br>use mirror to improve install speed in main land, link `/home/${env:username}` to `${env:userprofile}`
mask | A special task runner, use markdown to define its recipe
minify | light-weight minifier, HTML5, CSS3, JS, JSON, SVG and XML
