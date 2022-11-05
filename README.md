# TRGT: Tandem Repeat Genotyper

TRGT is a tool for targeted genotyping of tandem repeats from PacBio HiFi data.
In addition to the basic size genotyping, TRGT profiles sequence composition,
mosaicism, and CpG methylation of each analyzed repeat. TRGT comes with a
companion tool TRVZ for visualization of reads overlapping the repeats.

## Early version warning

Please note that TRGT is still in early development. We are still tweaking the
input / output file formats and making changes that can affect the behavior of
the program.

## Availability

- TRGT and TRVZ Linux binaries are [available here](https://github.com/PacificBiosciences/trgt/releases)
- Repeat definition files are [available here](repeats/)

## Documentation

- [Introductory tutorial](docs/tutorial.md)
- Reference
  - [Command-line interface](docs/cli.md)
  - [Repeat definition file](docs/repeat_files.md)
  - [VCF files generated by TRGT](docs/vcf_files.md)

## Need help?

If you notice any missing features, bugs, or need assistance with analyzing the
output of TRGT, please don't hesitate to [reach out by email](mailto:edolzhenko@pacificbiosciences.com)
or open a GitHub issue.

## Support information

TRGT is a pre-release software intended for research use only and not for use
in diagnostic procedures. While efforts have been made to ensure that TRGT
lives up to the quality that PacBio strives for, we make no warranty regarding
this software.

As TRGT is not covered by any service level agreement or the like, please do
not contact a PacBio Field Applications Scientists or PacBio Customer Service
for assistance with any TRGT release. Please report all issues through GitHub
instead. We make no warranty that any such issue will be addressed, to any
extent or within any time frame.

## Full Changelog

- 0.3.4
  - Improved label spacing in TRVZ plots
