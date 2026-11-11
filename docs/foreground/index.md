# Foreground Models

This section lists the various [Foreground Models](../index.md#definitions) within this Supermodel.

## Profiles

Many of the models here are [profiles](../index.md#definitions) of other models: subsets or extensions of well-known international models.

Any data created according to a profile of another model _MUST_ conform to that other model.

## List of Foreground Models

Several of the models listed here were defined when making this Supermodel. Others existed previously, are defined 
elsewhere and reused here. The table below lists the current Component Models.

| **Model**                                                     | **Domain(s)**                                        | **Persistent Identifier**             | **Notes**                                                        |
|---------------------------------------------------------------|------------------------------------------------------|---------------------------------------|------------------------------------------------------------------|
| [Bore Model](bore.md)                                            | bores, boreholes, wells etc                          | `https://linked.data.gov.au/def/bore` | Child model of [GeoF](geofh.md).    |
|  [Data Catalog Vocabulary (DCAT)](dcat.md) | catalogues and general properties of the things in them | `https://www.w3.org/TR/vocab-dcat-3/` | An international standard model, used directly |
| [Geo Features Hierarchy](geofh.md)                | geospatial features                                  | `https://linked.data.gov.au/def/geofh`  | Provides specialised types of resource sector features such as mines, bores, tenements                                                       |
| [Geosample Model](geosample.md)                                  | samples, sampling                                    | `https://linked.data.gov.au/def/xxx`  | Derivative of standard sample models such as [SOSA](../background.md#sosa) but for geological samples                                                       |
| [Mine Model](mine.md)                                            | mines                                                | `https://linked.data.gov.au/def/mine` | Child model of [GeoF](geofh.md).    |
| [Mining Authorisation Model](mining-authorisation.md) | tenements, permits, licences etc., to do with mining | `https://linked.data.gov.au/def/xxx`  | Child model of [GeoF](geofh.md).    |
| [Resource Occurrence Model](resource-occurrence.md)              | spatial position and values of resources             | `https://linked.data.gov.au/def/xxx`  | Child model of [GeoF](geofh.md)       |
