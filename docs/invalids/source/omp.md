# omp

This document details the invalid local unique identifiers used in CURIEs
for node, synonym, and definition cross-references in `omp`. See the [GitHub repository](https://github.com/microbialphenotypes/OMP-ontology).


## `APO`: Ascomycete phenotype ontology

Overall, there were 1 invalid
xrefs to external prefixed with `APO` (standardized to Bioregistry
prefix [`apo`](https://bioregistry.io/apo)) that
did not match the standard pattern `^\d{7}$`.

| external_xref   |   usages_count | usages                                                    |
|-----------------|----------------|-----------------------------------------------------------|
| `APO::0000051`  |              1 | [OMP:0007101](http://purl.obolibrary.org/obo/OMP_0007101) |

## `CHEBI`: Chemical Entities of Biological Interest

Overall, there were 2 invalid
xrefs to external prefixed with `CHEBI` (standardized to Bioregistry
prefix [`chebi`](https://bioregistry.io/chebi)) that
did not match the standard pattern `^\d+$`.

| external_xref       |   usages_count | usages                                                    |
|---------------------|----------------|-----------------------------------------------------------|
| `CHEBI:CHEBI:87649` |              1 | [OMP:0007481](http://purl.obolibrary.org/obo/OMP_0007481) |
| `CHEBI::4806`       |              1 | [OMP:0007848](http://purl.obolibrary.org/obo/OMP_0007848) |

## `FYPO`: Fission Yeast Phenotype Ontology

Overall, there were 3 invalid
xrefs to external prefixed with `FYPO` (standardized to Bioregistry
prefix [`fypo`](https://bioregistry.io/fypo)) that
did not match the standard pattern `^\d{7}$`.

| external_xref       |   usages_count | usages                                                    |
|---------------------|----------------|-----------------------------------------------------------|
| `FYPO:FYPO:0003755` |              1 | [OMP:0007746](http://purl.obolibrary.org/obo/OMP_0007746) |
| `FYPO:1178`         |              1 | [OMP:0007808](http://purl.obolibrary.org/obo/OMP_0007808) |
| `FYPO:000064`       |              1 | [OMP:0007701](http://purl.obolibrary.org/obo/OMP_0007701) |

## `GO`: Gene Ontology

Overall, there were 8 invalid
xrefs to external prefixed with `GO` (standardized to Bioregistry
prefix [`go`](https://bioregistry.io/go)) that
did not match the standard pattern `^\d{7}$`.

| external_xref   |   usages_count | usages                                                                                                               |
|-----------------|----------------|----------------------------------------------------------------------------------------------------------------------|
| `GO:JG`         |              2 | [OMP:0005181](http://purl.obolibrary.org/obo/OMP_0005181), [OMP:0005200](http://purl.obolibrary.org/obo/OMP_0005200) |
| `GO::0019835`   |              1 | [OMP:0005336](http://purl.obolibrary.org/obo/OMP_0005336)                                                            |
| `GO:00140013`   |              1 | [OMP:0007562](http://purl.obolibrary.org/obo/OMP_0007562)                                                            |
| `GO::0032179`   |              1 | [OMP:0007738](http://purl.obolibrary.org/obo/OMP_0007738)                                                            |
| `GO:`           |              1 | [OMP:0008035](http://purl.obolibrary.org/obo/OMP_0008035)                                                            |
| `GO::0007059`   |              1 | [OMP:0005047](http://purl.obolibrary.org/obo/OMP_0005047)                                                            |
| `GO:00015629`   |              1 | [OMP:0005182](http://purl.obolibrary.org/obo/OMP_0005182)                                                            |

## `OMP`: Ontology of Microbial Phenotypes

Overall, there were 1,807 invalid
xrefs to external prefixed with `OMP` (standardized to Bioregistry
prefix [`omp`](https://bioregistry.io/omp)) that
did not match the standard pattern `^\d{7}$`.

| external_xref   |   usages_count | usages                                                                                                                                                                                                                                                                                                     |
|-----------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `OMP:DAS`       |            665 | [OMP:0000023](http://purl.obolibrary.org/obo/OMP_0000023), [OMP:0000036](http://purl.obolibrary.org/obo/OMP_0000036), [OMP:0000042](http://purl.obolibrary.org/obo/OMP_0000042), [OMP:0000050](http://purl.obolibrary.org/obo/OMP_0000050), [OMP:0000089](http://purl.obolibrary.org/obo/OMP_0000089), ... |
| `OMP:JG`        |            272 | [OMP:0005000](http://purl.obolibrary.org/obo/OMP_0005000), [OMP:0005019](http://purl.obolibrary.org/obo/OMP_0005019), [OMP:0005026](http://purl.obolibrary.org/obo/OMP_0005026), [OMP:0005028](http://purl.obolibrary.org/obo/OMP_0005028), [OMP:0005062](http://purl.obolibrary.org/obo/OMP_0005062), ... |
| `OMP:WAM`       |            247 | [OMP:0000039](http://purl.obolibrary.org/obo/OMP_0000039), [OMP:0000043](http://purl.obolibrary.org/obo/OMP_0000043), [OMP:0000087](http://purl.obolibrary.org/obo/OMP_0000087), [OMP:0000088](http://purl.obolibrary.org/obo/OMP_0000088), [OMP:0000090](http://purl.obolibrary.org/obo/OMP_0000090), ... |
| `OMP:das`       |            231 | [OMP:0000044](http://purl.obolibrary.org/obo/OMP_0000044), [OMP:0000193](http://purl.obolibrary.org/obo/OMP_0000193), [OMP:0000223](http://purl.obolibrary.org/obo/OMP_0000223), [OMP:0000226](http://purl.obolibrary.org/obo/OMP_0000226), [OMP:0000250](http://purl.obolibrary.org/obo/OMP_0000250), ... |
| `OMP:JCH`       |            216 | [OMP:0000013](http://purl.obolibrary.org/obo/OMP_0000013), [OMP:0000014](http://purl.obolibrary.org/obo/OMP_0000014), [OMP:0000026](http://purl.obolibrary.org/obo/OMP_0000026), [OMP:0000101](http://purl.obolibrary.org/obo/OMP_0000101), [OMP:0000106](http://purl.obolibrary.org/obo/OMP_0000106), ... |
| `OMP:MCC`       |             93 | [OMP:0000000](http://purl.obolibrary.org/obo/OMP_0000000), [OMP:0000001](http://purl.obolibrary.org/obo/OMP_0000001), [OMP:0000002](http://purl.obolibrary.org/obo/OMP_0000002), [OMP:0000003](http://purl.obolibrary.org/obo/OMP_0000003), [OMP:0000004](http://purl.obolibrary.org/obo/OMP_0000004), ... |
| `OMP:KDA`       |             35 | [OMP:0007224](http://purl.obolibrary.org/obo/OMP_0007224), [OMP:0008000](http://purl.obolibrary.org/obo/OMP_0008000), [OMP:0008001](http://purl.obolibrary.org/obo/OMP_0008001), [OMP:0008002](http://purl.obolibrary.org/obo/OMP_0008002), [OMP:0008003](http://purl.obolibrary.org/obo/OMP_0008003), ... |
| `OMP:AEZ`       |              9 | [OMP:0000077](http://purl.obolibrary.org/obo/OMP_0000077), [OMP:0000117](http://purl.obolibrary.org/obo/OMP_0000117), [OMP:0000118](http://purl.obolibrary.org/obo/OMP_0000118), [OMP:0000119](http://purl.obolibrary.org/obo/OMP_0000119), [OMP:0000120](http://purl.obolibrary.org/obo/OMP_0000120), ... |
| `OMP:TZ`        |              9 | [OMP:0008037](http://purl.obolibrary.org/obo/OMP_0008037), [OMP:0008039](http://purl.obolibrary.org/obo/OMP_0008039), [OMP:0008040](http://purl.obolibrary.org/obo/OMP_0008040), [OMP:0008041](http://purl.obolibrary.org/obo/OMP_0008041), [OMP:0008043](http://purl.obolibrary.org/obo/OMP_0008043), ... |
| `OMP:TCK`       |              8 | [OMP:0006000](http://purl.obolibrary.org/obo/OMP_0006000), [OMP:0006105](http://purl.obolibrary.org/obo/OMP_0006105), [OMP:0006106](http://purl.obolibrary.org/obo/OMP_0006106), [OMP:0006118](http://purl.obolibrary.org/obo/OMP_0006118), [OMP:0006172](http://purl.obolibrary.org/obo/OMP_0006172), ... |
| `OMP:AZ`        |              6 | [OMP:0000140](http://purl.obolibrary.org/obo/OMP_0000140), [OMP:0000141](http://purl.obolibrary.org/obo/OMP_0000141), [OMP:0000142](http://purl.obolibrary.org/obo/OMP_0000142), [OMP:0000148](http://purl.obolibrary.org/obo/OMP_0000148), [OMP:0000256](http://purl.obolibrary.org/obo/OMP_0000256), ... |
| `OMP:tz`        |              5 | [OMP:0008035](http://purl.obolibrary.org/obo/OMP_0008035), [OMP:0008036](http://purl.obolibrary.org/obo/OMP_0008036), [OMP:0008038](http://purl.obolibrary.org/obo/OMP_0008038), [OMP:0008052](http://purl.obolibrary.org/obo/OMP_0008052), [OMP:0008060](http://purl.obolibrary.org/obo/OMP_0008060)      |
| `OMP:dr`        |              4 | [OMP:0005382](http://purl.obolibrary.org/obo/OMP_0005382), [OMP:0005393](http://purl.obolibrary.org/obo/OMP_0005393), [OMP:0005395](http://purl.obolibrary.org/obo/OMP_0005395), [OMP:0005398](http://purl.obolibrary.org/obo/OMP_0005398)                                                                 |
| `OMP:JHU`       |              2 | [OMP:0005035](http://purl.obolibrary.org/obo/OMP_0005035), [OMP:0005036](http://purl.obolibrary.org/obo/OMP_0005036)                                                                                                                                                                                       |
| `OMP:JCh`       |              2 | [OMP:0006141](http://purl.obolibrary.org/obo/OMP_0006141), [OMP:0006143](http://purl.obolibrary.org/obo/OMP_0006143)                                                                                                                                                                                       |
| `OMP:DR`        |              2 | [OMP:0007540](http://purl.obolibrary.org/obo/OMP_0007540), [OMP:0007541](http://purl.obolibrary.org/obo/OMP_0007541)                                                                                                                                                                                       |
| `OMP:REF`       |              1 | [OMP:0007267](http://purl.obolibrary.org/obo/OMP_0007267)                                                                                                                                                                                                                                                  |

## `OMp`: Ontology of Microbial Phenotypes

Overall, there were 2 invalid
xrefs to external prefixed with `OMp` (standardized to Bioregistry
prefix [`omp`](https://bioregistry.io/omp)) that
did not match the standard pattern `^\d{7}$`.

| external_xref   |   usages_count | usages                                                                                                               |
|-----------------|----------------|----------------------------------------------------------------------------------------------------------------------|
| `OMp:JCH`       |              2 | [OMP:0006019](http://purl.obolibrary.org/obo/OMP_0006019), [OMP:0006042](http://purl.obolibrary.org/obo/OMP_0006042) |

## `SNOMED`: SNOMED CT (International Edition)

Overall, there were 6 invalid
xrefs to external prefixed with `SNOMED` (standardized to Bioregistry
prefix [`snomedct`](https://bioregistry.io/snomedct)) that
did not match the standard pattern `^(\w+)?\d+$`.

| external_xref      |   usages_count | usages                                                    |
|--------------------|----------------|-----------------------------------------------------------|
| `SNOMED:P3-51350`  |              1 | [OMP:0000110](http://purl.obolibrary.org/obo/OMP_0000110) |
| `SNOMED:P3-51370`  |              1 | [OMP:0000114](http://purl.obolibrary.org/obo/OMP_0000114) |
| `SNOMED:P3-51360`  |              1 | [OMP:0000115](http://purl.obolibrary.org/obo/OMP_0000115) |
| `SNOMED:P3-513150` |              1 | [OMP:0000139](http://purl.obolibrary.org/obo/OMP_0000139) |
| `SNOMED:P3-51130`  |              1 | [OMP:0000160](http://purl.obolibrary.org/obo/OMP_0000160) |
| `SNOMED:P3-51140`  |              1 | [OMP:0000161](http://purl.obolibrary.org/obo/OMP_0000161) |

