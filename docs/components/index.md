# Component Models

This section lists the various Component Models within this Supermodel.

These [Component Models](../index.md#definitions) describe data from major GSWA datasets and systems.

All data created according to any of the Component Models, to be used in this Supermodel's context, _MUST_ also conform to this Supermodel's [Backbone Model](../backbone.md). 

Note that useful data may be created that is valid according to individual Component Models and not this Supermodel's
Backbone Model for use outside this Supermodel's context.

## Profiles

Many of the Component Models here are defined as a _profile_, by which we mean that it is a model that draws from other
standards’ models and constrains and extends their elements, rather than creating its own elements.

Profiles are used to specialise general-purpose models while remaining conformant with them.
 
Formally, any data created according to a _profile_ _MUST_ conform to all the models it profiles, as per the [Profiles Vocabulary](../background.md#profiles-vocabulary-prof) rules.

Profiles may profile multiple Standards, bringing together all the parts needed for a particular task

## List of Component Models

Each page describes the source dataset or system and links to further information. The Persistent Identifier namespace is `https://linked.data.gov.au/`

| Model | Dataset or system | Persistent identifier |
| --- | --- | --- | 
| [CIMS](cims.md) | Core library holdings and sample inventory. | [`def/wa-cims`](https://linked.data.gov.au/def/wa-cim) |
| [DRILLHOLES](drillholes.md) | Drillhole and surface sample data extracted from open-file exploration reports. | [`def/wa-drillholes`](https://linked.data.gov.au/def/wa-drillholes)|
| [ENS](ens.md) | Explanatory notes for rock units, tectonic units and geological events. | [`def/wa-ens`](https://linked.data.gov.au/def/wa-ens)|
| [MAGIX](magix.md) | Geophysical survey register and data repository. | [`def/wa-magix`](https://linked.data.gov.au/def/wa-magix)|
| [MINEDEX](minedex.md) | Mining and exploration sites, deposits, prospects and projects. | [`def/wa-mindex`](https://linked.data.gov.au/def/wa-mindex)|
| [WACHEM](wachem.md) | Geochemical analyses of GSWA rock, regolith and drill core samples. | [`def/wa-wachem`](https://linked.data.gov.au/def/wa-wachem)|
| [WAGIMS](wagims.md) | GSWA geochronological, isotopic and metamorphic data. | [`def/wa-wagims`](https://linked.data.gov.au/def/wa-wagims)|
| [WAMEX](wamex.md) | Public company mineral exploration reports. | [`def/wa-wamex`](https://linked.data.gov.au/def/wa-wamex)|
| [WAPIMS](wapims.md) | Public energy exploration and production records, including wells and surveys. | [`def/wa-wapims`](https://linked.data.gov.au/def/wa-wapims)|
| [WAROX](warox.md) | GSWA geological field observations, measurements and samples. | [`def/wa-warox`](https://linked.data.gov.au/def/wa-warox)|
