# Foreground Models

This section lists the various [Foreground Models](index.md#definitions) within this Supermodel.

## Profiles

Many of the models here are [profiles](index.md#definitions) of other models: subsets or extensions of well-known international models.

Any data created according to a profile of another model _MUST_ conform to that other model

## List of Foreground Models

Several of the Component Models within this Supermodel are fully defined here. Others are defined elsewhere and just
referred to from here. The table below lists the current Component Models.

| **Model**                                                     | **Domain(s)**                                        | **Persistent Identifier**             | **Notes**                                                        |
|---------------------------------------------------------------|------------------------------------------------------|---------------------------------------|------------------------------------------------------------------|
| [Geo Features Hierarchy](foreground/geofh.md)                | geospatial features                                  | `https://linked.data.gov.au/def/geofh`  |                                                        |
| [Bore Model](foreground/bore.md)                                            | bores, boreholes, wells etc                          | `https://linked.data.gov.au/def/bore` | child model of [GeoF](foreground/geofh.md).    |
| [Mine Model](foreground/mine.md)                                            | mines                                                | `https://linked.data.gov.au/def/mine` | child model of [GeoF](foreground/geofh.md).    |
| [Mining Authorisation Model](foreground/mining-authorisation.md) | tenements, permits, licences etc., to do with mining | `https://linked.data.gov.au/def/xxx`  | child model of [GeoF](foreground/geofh.md).    |
| [Geosample Model](foreground/geosample.md)                                  | samples, sampling                                    | `https://linked.data.gov.au/def/xxx`  | Coming...                                                        |
| [Resource Occurrence Model](foreground/resource-occurrence.md)              | spatial position and values of resources             | `https://linked.data.gov.au/def/xxx`  | child model of [GeoF](foreground/geofh.md)       |
