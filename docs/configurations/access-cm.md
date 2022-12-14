# ACCESS-CM {{ supported }}

{% include "call_contribute.md" %}


ACCESS-CM stands for ACCESS **C**oupled **M**odel. This means it is a fully-coupled climate model.

ACCESS-NRI will release an ACCESS-CM model configuration. The first release of ACCESS-CM will be derived from the [CSIRO ACCESS-CM2 configuration](#access-cm2) and will include [atmosphere], [land], [ocean] and [sea ice] components.

## [ACCESS-CM2] {{ recommended }}

[**Citation** [@Bi2020-vj]][ACCESS-CM2-cite] |
[**Tutorial**][ACCESS-CM2-tute]

ACCESS-CM2 [@Bi2020-vj] is one of Australia’s contributions to the World Climate Research Programme’s Coupled Model Intercomparison Project Phase 6 (CMIP6). The component models are: UM10.6 GA7.1 for the atmosphere, CABLE2.5 for the land surface, MOM5 for the ocean, and CICE5.1.2 for the sea ice. Compared to previous model versions ACCESS-CM2 shows better global hydrological balance, more realistic ocean water properties (in terms of spatial distribution) and meridional overturning circulation in the Southern Ocean but a poorer simulation of the Antarctic sea ice and a larger energy imbalance at the top of atmosphere. This energy imbalance reflects a noticeable warming trend of the global ocean over the spin-up period.

[atmosphere]: ../model_components/atmosphere.md
[land]: ../model_components/land.md
[ocean]: ../model_components/ocean.md
[sea ice]: ../model_components/sea-ice.md

[ACCESS-CM2]: https://research.csiro.au/access/about/cm2/
[ACCESS-CM2-cite]: https://www.publish.csiro.au/es/ES19040
[ACCESS-CM2-tute]: https://nespclimate.com.au/wp-content/uploads/2020/10/Instruction-document-Getting_started_with_ACCESS.pdf

