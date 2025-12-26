---
name: Acoustics
topic: Acoustics including bioacoustics and ecoacoustics
maintainer: R Bioacoustics Group
email: r-bioacoustics@googlegroups.com
source: https://github.com/r-bioacoustics/bioacoustics-ctv
url: https://r-bioacoustics.github.io/bioacoustics-ctv/Acoustics.html
version: 2025-12-26
---

::: {}
### Importing audio data

- `r pkg("tuneR", priority = "core")` allows the import of wave files as Wave objects.
- The readAudio function of `r pkg("sonicscrewdriver")` allows reading multiple file types.
- `r pkg("audio")` can record from system sound devices.

### Linking to other tools

- `r pkg("ReVAMP")` allows the use of [Vamp Plugins](https://vamp-plugins.org/) for audio analysis in R.
- `r pkg("Rraven")` allows exchanging data with Raven software and R (in particular `r pkg("warbleR")`).
- `r pkg("sonicscrewdriver")` allows reading and creating Audacity label files (examples: [Interacting with other tools](https://sonicscrewdriver.ebaker.me.uk/articles/other-apps.html))

### Packages to add

`r pkg("warbleR")`
`r pkg("av")`
`r pkg("sonicscrewdriver")`
`r pkg("SoundShape")`
`r pkg("baRulho")`
`r pkg("dynaSpec")``
`r pkg("soundClass")`
`r pkg("soundecology")`
`r pkg("soundgen")`
`r pkg("phonTools")`
`r pkg("ohun")`
`r pkg("NatureSounds")`
:::

### Links
- [gibbonR (GitHub)](https://github.com/DenaJGibbon/gibbonR-package)
