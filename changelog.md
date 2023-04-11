## Changelog NETN-Physical

### Changes for v3.0
* Added `Status` attribute to extend `BaseEntity` objectClass 
* Added `SymbolId` attribute to extend `BaseEntity` objectClass 
* Moved attributes from `NETN_Human` and `NETN_NonHuman` to `Lifeform`
* Moved attributes from `NETN_Munition` to `Munition`
* Moved attributes from `NETN_CulturalFeature` to `CulturalFeature`
* Moved attributes from all NETN platforms subclasses to `Platform`
* Moved attribute `SourceUnit`from Platform and Lifeform object classes to the same classes in NETN-MRM
* Changed datatype of FixedRecord SensorStruct field SensorID to UUID

* Renamed attribute `EmbeddedUnitList` for `Platform` and `CulturalFeature` to `MountedEntities`.
* Added attribute `MountedOn` to `Platform` object class
* Added attribute `MountedOn` to `Lifeform` object class


### Changes for v2.0

* Added attribute `SourceUnit` to all NETN-Physical platform and lifeform object classes.
* Added attribute `Route` to all NETN-Physical platform, munition and lifeform object classes.
* Added attribute `Destination` to all NETN-Physical platform, munition and lifeform object classes.
* Renamed attribute `UniqueID` to `UniqueId` for compliance with naming convensions.
* Added attribute `SymbolId` to all NETN-Physical platform, lifeform, cultural feature and munition object classes.
* Renamed object class `SubmersibleVehicle` to `SubmersibleVessel`.

### Changes for v1.2.0
NETN-MRM FOM Module v1.2.0 was developed by MSG-106 and MSG-134 and released as part of NETN-FOM v2.0 in AMSP-04 Ed A.

* Added object classes and datatypes from FOM modules in NETN FOM v1
* Added object class `NETN_CulturalFeature`
* Added  object class `NETN_Munition`

* Added attribute Symbol to all object classes
* Changed from Reliable to BestEffort on some attributes to get a common transport type