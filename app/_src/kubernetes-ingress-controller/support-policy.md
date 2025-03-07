---
title: Support Policy
badge: enterprise
type: reference
purpose: |
  What versions of KIC are supported, and until when?
---

Learn about the support for {{site.kic_product_name}} software versions.

## Version support for {{site.kic_product_name}}

Kong primarily follows [semantic versioning](https://semver.org/) (SemVer) for its products.

At Kong’s discretion a specific minor version can be marked as a LTS version. The LTS version is supported on a given distribution for the duration of the distribution’s lifecycle, or for 3 years from LTS release whichever comes sooner. LTS only receives security fixes or certain critical patches at the discretion of Kong. Kong guarantees that at any given time, there will be at least 1 active LTS Kong version.

LTS versions of {{site.kic_product_name}} are supported for 3 years after release. Standard versions are supported for 1 year after release.

## Supported versions

{% include_cached md/kic/support.md show_kic=true %}

## {{site.kic_product_name}} versions

{:.note}
> LTS releases are marked **bold**, and are supported for 3 years from release

|  Version   |   Release Date   | End of Support |
|------------|------------------|----------------|
|   3.0.x    |    2023-11-03    |   2024-11-03   |
| **2.12.x** |  **2023-09-25**  | **2026-09-25** |
|   2.11.x   |    2023-08-09    |   2024-08-09   |
|   2.10.x   |    2023-06-02    |   2024-06-02   |
|   2.9.x    |    2023-03-09    |   2024-03-09   |
|   2.8.x    |    2022-12-19    |   2023-12-19   |
|   2.7.x    |    2022-09-27    |   2023-09-27   |
|   2.6.x    |    2022-09-15    |   2023-09-15   |
| **2.5.x**  |  **2022-07-11**  | **2025-03-01** |
|   2.4.x    |    2022-06-15    |   2023-06-15   |
|   2.3.x    |    2022-04-05    |   2023-04-05   |
|   2.2.x    |    2022-02-04    |   2023-02-04   |
|   2.1.x    |    2022-01-05    |   2023-01-05   |
|   2.0.x    |    2021-10-07    |   2022-10-07   |
|   1.3.x    |    2021-05-27    |   2022-05-27   |
|   1.2.x    |    2021-03-24    |   2022-03-24   |
|   1.1.x    |    2020-12-09    |   2021-12-09   |
|   1.0.x    |    2020-10-05    |   2021-10-05   |
|   0.x.x    |    2018-06-02    |   2019-06-02   |

> *Table 1: Version Support for {{site.kic_product_name}}*

{% include /md/support-policy.md %}

## See also
* [Version support policy for {{site.base_gateway}}](/gateway/latest/support-policy/)
* [Version support policy for {{site.mesh_product_name}}](/mesh/latest/support-policy/)
