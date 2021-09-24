# COVID-19 Dashboard Source Data

This documentation is also available at `https://www.covid19.admin.ch/api/data/documentation` including detailed html versions of the model documentation.

## Data
Check the `data` folder for the data source files.

### Files
| File  | Model  |  Description |
|---|---|---|
| COVID19Cases_geoRegion.(json/csv) | DailyIncomingData | Daily record timelines by geoRegion for cases. |
| COVID19Cases_vaccpersons.(json/csv) | DailyCasesVaccPersonsIncomingData | Daily record timelines for cases of fully vaccinated persons by vaccine. Data only available for geoRegion CHFL. |
| COVID19Hosp_geoRegion.(json/csv) | DailyIncomingData | Daily record timelines by geoRegion for hospitalisations. |
| COVID19Hosp_vaccpersons.(json/csv) | DailyHospVaccPersonsIncomingData | Daily record timelines for hospitalisations of fully vaccinated persons by vaccine. Data only available for geoRegion CHFL. |
| COVID19Death_geoRegion.(json/csv) | DailyIncomingData | Daily record timelines by geoRegion for deaths. |
| COVID19Death_vaccpersons.(json/csv) | DailyDeathVaccPersonsIncomingData | Daily record timelines for deaths of fully vaccinated persons by vaccine. Data only available for geoRegion CHFL. |
| COVID19Test_geoRegion_all.(json/csv) | DailyIncomingData | Daily record timelines by geoRegion for tests (all test types). |
| COVID19Test_geoRegion_PCR_Antigen.(json/csv) | DailyIncomingData | Daily record timelines by geoRegion and test type (pcr/antigen) for tests. |
| COVID19Cases_geoRegion_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion for cases. |
| COVID19Hosp_geoRegion_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion for hospitalisations. |
| COVID19Death_geoRegion_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion for deaths. |
| COVID19Test_geoRegion_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion for tests. |
| COVID19Test_geoRegion_PCR_Antigen_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and test type (pcr/antigen) for tests. |
| COVID19Cases_geoRegion_AKL10_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and age brackets for cases. |
| COVID19Cases_vaccpersons_AKL10_w.(json/csv) | WeeklyCasesVaccPersonsAgeRangeIncomingData | Iso-Week record timelines for cases of fully vaccinated persons by vaccine and age brackets. Data only available for geoRegion CHFL. |
| COVID19Hosp_geoRegion_AKL10_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and age brackets for hospitalisations. |
| COVID19Hosp_vaccpersons_AKL10_w.(json/csv) | WeeklyHospVaccPersonsAgeRangeIncomingData | Iso-Week record timelines for hospitalisations of fully vaccinated persons by vaccine and age brackets. Data only available for geoRegion CHFL. |
| COVID19Death_geoRegion_AKL10_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and age brackets for deaths. |
| COVID19Death_vaccpersons_AKL10_w.(json/csv) | WeeklyDeathVaccPersonsAgeRangeIncomingData | Iso-Week record timelines for deaths of fully vaccinated persons by vaccine and age brackets. Data only available for geoRegion CHFL. |
| COVID19Test_geoRegion_AKL10_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and age brackets for tests (all test types). |
| COVID19Cases_geoRegion_sex_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and sex for cases. |
| COVID19Cases_vaccpersons_sex_w.(json/csv) | WeeklyCasesVaccPersonsSexIncomingData | Iso-Week record timelines for cases of fully vaccinated persons by vaccine and sex. Data only available for geoRegion CHFL. |
| COVID19Hosp_geoRegion_sex_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and sex for hospitalisations. |
| COVID19Hosp_vaccpersons_sex_w.(json/csv) | WeeklyHospVaccPersonsSexIncomingData | Iso-Week record timelines for hospitalisations of fully vaccinated persons by vaccine and sex. Data only available for geoRegion CHFL. |
| COVID19Death_geoRegion_sex_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and sex for deaths. |
| COVID19Death_vaccpersons_sex_w.(json/csv) | WeeklyDeathVaccPersonsSexIncomingData | Iso-Week record timelines for deaths of fully vaccinated persons by vaccine and sex. Data only available for geoRegion CHFL. |
| COVID19Test_geoRegion_sex_w.(json/csv) | WeeklyIncomingData | Iso-Week record timelines by geoRegion and sex for tests (all test types). |
| COVID19Cases_extraGeoRegions_d.(json/csv) | AdditionalGeoRegionDailyIncomingData | Daily record timelines by (additonal) geographical units for cases. Contains data for CH, cantons, greater regions & greater labor market regions. |
| COVID19Cases_extraGeoRegions_14d.(json/csv) | AdditionalGeoRegion14dPeriodIncomingData | 14d aggregated record timelines by (additional) geographical units for cases. Contains data for CH, labor market regions & districts. |
| COVID19WeeklyReportText.(json/csv) | WeeklyReportIncomingData | Weekly report texts by Iso-Week. |
| COVID19EvalTextDaily.(json/csv) | DailyReportIncomingData | Optional extra texts for daily report (PDF). |
| COVID19QuarantineIsolation_geoRegion_d.(json/csv) | ContactTracingIncomingData | Contact tracing data (current record by geoRegion where available). |
| COVID19HospCapacity_geoRegion.(json/csv) | HospCapacityDailyIncomingData | Daily hospital capacity data timelines by geoRegion. |
| COVID19IntQua.(json/csv) | InternationalQuarantineIncomingData | International quarantine data (mandatory quarantine requirement when entering Switzerland). |
| COVID19IntCases.(json/csv) | InternationalDailyIncomingData | International daily data (cases). |
| COVID19Re_geoRegion.(json/csv) | ReDailyIncomingData | Daily R<sub>e</sub> value data timelines by geoRegion. |
| COVID19VaccDosesDelivered.(json/csv) | VaccinationIncomingData | Vaccine doses delivered/received data by geoRegion. |
| COVID19VaccDosesDelivered_vaccine.(json/csv) | VaccinationDosesReceivedDeliveredVaccineIncomingData | Vaccine doses delivered/received data by geoRegion and vaccine (type). |
| COVID19VaccDosesAdministered.(json/csv) | VaccinationIncomingData | Vaccine doses administered data by geoRegion. |
| COVID19AdministeredDoses_vaccine.(json/csv) | VaccinationVaccineIncomingData | Vaccine doses administered data by geoRegion and vaccine (type). |
| COVID19VaccPersons_v2.(json/csv) | VaccPersonsIncomingData | Vaccinated persons data by geoRegion (aggregated by canton/country of residence). |
| COVID19FullyVaccPersons_vaccine_v2.(json/csv) | VaccPersonsVaccineIncomingData | Fully vaccinated persons data by geoRegion (aggregated by canton/country of residence) and vaccine (type). |
| COVID19VaccDosesAdministered_AKL10_w.(json/csv) | VaccinationWeeklyIncomingData | Iso-Week record timelines by geoRegion and age brackets for vaccine doses administered. |
| COVID19VaccPersons_AKL10_w_v2.(json/csv) | VaccPersonsWeeklyIncomingData | Iso-Week record timelines by geoRegion (aggregated by canton/country of residence) and age brackets for vaccinated persons. |
| COVID19VaccDosesAdministered_sex_w.(json/csv) VaccinationWeeklyIncomingData | Iso-Week record timelines by geoRegion and sex for vaccine doses administered. |
| COVID19VaccPersons_sex_w_v2.(json/csv) | VaccPersonsWeeklyIncomingData | Iso-Week record timelines by geoRegion (aggregated by canton/country of residence) and sex for vaccinated persons. |
| COVID19FullyVaccPersons_indication_w_v2.(json/csv) | VaccPersonsWeeklyIndicationIncomingData| Iso-Week record timelines by geoRegion (aggregated by canton/country of residence) and vacc indication (reason) for fully vaccinated persons. |
| COVID19VaccDosesAdministered_indication_w.(json/csv) | VaccinationWeeklyIndicationIncomingData | Iso-Week record timelines by geoRegion and vacc indication (reason) for vaccine doses administered. |
| COVID19VaccDosesAdministered_location_w.(json/csv) | VaccinationWeeklyLocationIncomingData | Iso-Week record timelines by geoRegion and location for vaccine doses administered. |
| COVID19VaccSymptoms.(json/csv) | VaccinationSymptomsIncomingData | Data for suspected cases of adverse vaccination reactions based on reports from Swissmedic. |
| COVID19VaccDosesContingent.(json/csv) | VaccinationContingentIncomingData | Allotted vaccination doses contingent data by geoRegion. |
| COVID19Variants_wgs.(json/csv) | VirusVariantsWgsDailyIncomingData |  Virus variant data by geoRegion (source WGS & MSys). |
| COVID19Certificates.(json/csv) | CovidCertificatesDailyIncomingData | Issued COVID certificates data. |

## Schema
Check the `sources.schema.json` file for schema information (only json-schema format for now).

Please note that the data schema can change in the future and be released in a new version. Changes will be tracked here and the current schema version can be read from the data context (see section Download Automation below).

### Upcoming Releases

There are currently no planned releases.

### Releases

### v.0.16.2
**Released**: `13.09.2021`
**Description**:
- added new timeframe phase 4 starting from 21.06.2021 to daily and weekly models

### v.0.16.1
**Released**: `20.08.2021`
**Description**:
- added new timeframe and totals to daily and weekly models for comparison of all cases, hosp & death records with vaccination breakthrough data (added in release v.0.16.0)
- added properties `timeframe_vacc_info`, `sumTotal_vacc_info` and `offset_vacc_info` to `DailyIncomingData`
- added properties `timeframe_vacc_info`, `sumTotal_vacc_info` and `offset_vacc_info` to `WeeklyIncomingData`
- added new virus variants `C.37` & `B.1.1.318` and updated the virus variant `B.1.617.2` records to also include the `AY.1-AY.12` variants (delta variant family): model: `VirusVariantsWgsDailyIncomingData`

### v.0.16.0
**Released**: `05.08.2021`
**Description**:
#### cases, hosp & death data of fully vaccinated persons
- added new source files for cases of fully vaccinated persons: `COVID19Cases_vaccpersons.(json/csv)` (model `DailyCasesVaccPersonsIncomingData`), `COVID19Cases_vaccpersons_AKL10_w.(json/csv)` (model `WeeklyCasesVaccPersonsAgeRangeIncomingData`) and `COVID19Cases_vaccpersons_sex_w.(json/csv)` (model `WeeklyCasesVaccPersonsSexIncomingData`)
- added new source files for hospitalisations of fully vaccinated persons: `COVID19Hosp_vaccpersons.(json/csv)` (model `DailyHospVaccPersonsIncomingData`), `COVID19Hosp_vaccpersons_AKL10_w.(json/csv)` (model `WeeklyHospVaccPersonsAgeRangeIncomingData`) and `COVID19Hosp_vaccpersons_sex_w.(json/csv)` (model `WeeklyHospVaccPersonsSexIncomingData`)
- added new source files for deaths of fully vaccinated persons: `COVID19Death_vaccpersons.(json/csv)` (model `DailyDeathVaccPersonsIncomingData`), `COVID19Death_vaccpersons_AKL10_w.(json/csv)` (model `WeeklyDeathVaccPersonsAgeRangeIncomingData`) and `COVID19Death_vaccpersons_sex_w.(json/csv)` (model `WeeklyDeathVaccPersonsSexIncomingData`)
- added mock data for `COVID19Cases_vaccpersons`, `COVID19Cases_vaccpersons_AKL10_w` and `COVID19Cases_vaccpersons_sex_w`. check online documentation to download data: `https://www.covid19.admin.ch/api/data/documentation#v0160`
- added mock data for `COVID19Hosp_vaccpersons`, `COVID19Hosp_vaccpersons_AKL10_w` and `COVID19Hosp_vaccpersons_sex_w`. check online documentation to download data: `https://www.covid19.admin.ch/api/data/documentation#v0160`
- added mock data for `COVID19Death_vaccpersons`, `COVID19Death_vaccpersons_AKL10_w` and `COVID19Death_vaccpersons_sex_w`. check online documentation to download data: `https://www.covid19.admin.ch/api/data/documentation#v0160`
- the data is incomplete because the reporting process is still being established and should be interpreted with caution. Consult the 'data_completeness' property for the current estimate of the completeness of the data.
- until the data completeness has improved, only the data for all vaccines combined will be published
- data is only available for geoRegion CHFL
#### difference to previous day
- only the data of the last 28d will be considered to calculate the difference to the previous day so it better reflects the current epidemiologic situation (changes to older data due to late reporting or data quality improvements efforts will not have any influence any more)
- updated the `entries_diff_last` property of the `DailyIncomingData` model accordingly
#### cleanup
- removed source files deprecated by the v.0.14.0 release

### v.0.15.0
**Released**: `27.07.2021`
**Description**:
- added new source file `COVID19VaccDosesDelivered_vaccine.(json/csv)` contains data by vaccine for both received (`COVID19VaccDosesReceived`) and delivered (`COVID19VaccDosesDelivered`) vaccination doses
- added model `VaccinationDosesReceivedDeliveredVaccineIncomingData`
- added mock data for `COVID19VaccDosesDelivered_vaccine`, check online documentation: `https://www.covid19.admin.ch/api/data/documentation#v0150`
- data is only available for geoRegion CHFL

### v.0.14.0
**Released**: `21.07.2021`
**Description**:
- once all cantons report detailed vaccination data, the data on vaccinated person (types `COVID19FullyVaccPersons`, `COVID19AtLeastOneDosePersons` and `COVID19PartiallyVaccPersons`) will be updated to be aggregated geographically by the residence of the person and no longer by the location of the administered doses.
- the following files (aggregation based on location of administered doses) will be DEPRECATED and will not be updated anymore after 16.07.2021 and removed after 30.07.2021: `COVID19VaccPersons.(json/csv)`, `COVID19FullyVaccPersons_vaccine.(json/csv)`, `COVID19FullyVaccPersons_indication_w`, ` COVID19VaccPersons_AKL10_w.(json/csv)` and `COVID19VaccPersons_sex_w.(json/csv)`
- added new source files `COVID19VaccPersons_v2.(json/csv)`, `COVID19FullyVaccPersons_vaccine_v2.(json/csv)`, `COVID19VaccPersons_AKL10_w_v2.(json/csv)`, `COVID19VaccPersons_sex_w_v2.(json/csv)` and `COVID19FullyVaccPersons_indication_w_v2.(json/csv)`
- added models  `VaccPersonsIncomingData`, `VaccPersonsVaccineIncomingData`, `VaccPersonsWeeklyIncomingData` and `VaccPersonsWeeklyIndicationIncomingData`
- mock data added for files `COVID19VaccPersons_v2`, `COVID19FullyVaccPersons_vaccine_v2`, `COVID19VaccPersons_AKL10_w_v2`, `COVID19VaccPersons_sex_w_v2` and `COVID19FullyVaccPersons_indication_w_v2`. Visit the online documentation to download the mock data files: `https://www.covid19.admin.ch/api/data/documentation#upcoming-releases`

### v.0.13.0
**Released**: `21.06.2021`
**Description**:
- added new source file for allotted contigent of vaccination doses: `COVID19VaccDosesContingent.(json/csv)`
- added model `VaccinationContingentIncomingData`

### v.0.12.0
**Released**: `17.06.2021`
**Description**:
- the data for virus variant B.1.617 (Kappa/Delta) will be removed and replaced by individual entries for B.1.617.1 (Kappa) and B.1.617.2 (Delta)
- udpated model `VirusVariantsWgsDailyIncomingData`
- the file `COVID19Variants.(json/csv)` has become DEPRECATED and will not be updated anymore after 17.06.2021 and will be removed after 30.06.2021
- the data for the following variants sourced from MSys (formerly available in the file `COVID19Variants.(json/csv)`) have been added to the `COVID19Variants_wgs.(json/csv)` file: P.1, B.1.617.1  B.1.617.2, B.1.525 (newly reported from 17.06.2021 onward), B.1.351, B.1.1.7 and B.1.1.7 & E484K. Check the `data_source` property to distinguish between the different sources.
- removed DEPRECATED files from version `v.0.8.0`

### v.0.11.0
**Released**: `14.06.2021`
**Description**:
- added new source files for additional geographical unit (greater regions, labor market regions, greater labor market regions and districts) breakdown for cases data: `COVID19Cases_extraGeoRegions_d.(json/csv)` and `COVID19Cases_extraGeoRegions_14d`
- added model documentation for `AdditionalGeoRegionDailyIncomingData`

### v.0.10.0
**Released**: `08.06.2021`
**Description**:
- added new source file for covid certificate data: `COVID19Certificates.(json/csv)`
- added model documentation `CovidCertificatesDailyIncomingData`

### v.0.9.0
**Released**: `25.05.2021`
**Description**:
- added new source files for suspected cases of adverse vaccination reactions based on reports from Swissmedic: `COVID19VaccSymptoms.(json/csv)`
- added model documentation `VaccinationSymptomsIncomingData`

### v.0.8.0
**Released**: `18.05.2021`
**Description**:
- added new source files for virus variant data from WGS: `COVID19Variants_wgs`
- added model documentation `VirusVariantsWgsDailyIncomingData`
- added new source files for vaccinated person data (including fully vaccinated persons, persons with at least one dose and partially vaccinated persons): `COVID19VaccPersons.(json/csv)`, `COVID19VaccPersons_AKL10_w.(json/csv)` and `COVID19VaccPersons_sex_w.(json/csv)`
- the following files are being DEPRECATED and will be removed after 15.06.2021: `COVID19FullyVaccPersons.(json/csv)`, `COVID19FullyVaccPersons_AKL10_w.(json/csv)` and `COVID19FullyVaccPersons_sex_w.(json/csv)`. The information about fully vaccinated persons is included in the files mentioned above (COVID19VaccPersons*)

### v.0.7.0
**Released**: `11.05.2021`
**Description**:
- added new source files for daily vaccination by vaccine (type) data: `COVID19FullyVaccPersons_vaccine.(json/csv)` and `COVID19VaccDosesAdministered_vaccine.(json/csv)`
- added model documentation `VaccinationVaccineIncomingData`

### v.0.6.0
**Released**: `04.05.2021`
**Description**:
- added new source files for weekly vaccination by indication (reason) data: `COVID19FullyVaccPersons_indication_w.(json/csv)` and `COVID19VaccDosesAdministered_indication_w.(json/csv)`
- added model documentation `VaccinationWeeklyIndicationIncomingData`
- added new source file for weekly vaccination by location data: `COVID19VaccDosesAdministered_location_w.(json/csv)`
- added model documentation `VaccinationWeeklyLocationIncomingData`

### v.0.5.0
**Released**: `29.04.2021`
**Description**:
- added new source file for weekly report text data: `COVID19WeeklyReportText.(json/csv)`
- added new source file for weekly test data by test type: `COVID19Test_geoRegion_PCR_Antigen_w.(json/csv)`
- extended the `WeeklyIncomingData` model with data regarding differences to the previous week & extension for test types

### v.0.4.6
**Released**: `26.04.2021`
**Description**:
  - added property `timeframe_phase3` to `HospCapacityDailyIncomingData` model

### v.0.4.5
**Released**: `19.04.2021`
**Description**:
- added new timeframe phase 3 starting from 15.02
  - added properties `offset_Phase3`, `sumTotal_Phase3`, `inzsumTotal_Phase3`, `anteil_pos_phase3` and `timeframe_phase3` to `DailyIncomingData` model
  - added properties `timeframe_phase3` to  `WeeklyIncomingData` model
  - added properties `sumTotal_Phase3` and `timeframe_phase3` to `VirusVariantsDailyIncomingData` model
  - added property `timeframe_phase3` to `ReDailyIncomingData` model

### v.0.4.4
**Released**: `25.03.2021`
**Description**:
- added `granularity` value `partial` to  `VaccinationWeeklyIncomingData` model

### v.0.4.3
**Released**: `19.03.2021`
**Description**:
- added data context history API, see documentation below for details
- added new properties `anteil_pos`, `lower_ci_day` and `upper_ci_day` to the `VirusVariantsDailyIncomingData` model

### v.0.4.2
**Released**: `26.02.2021`
**Description**:
- added new property `mean7d` to the `VaccinationIncomingData` model

### v.0.4.1
**Released**: `23.02.2021`
**Description**:
- added new weekly source files for fully vaccinated persons: `COVID19FullyVaccPerson_AKL10_ws.(json/csv)`, `COVID19FullyVaccPerson_sex_ws.(json/csv)`
- added new weekly source files for vaccination doses administered: `COVID19VaccDosesAdministered_AKL10_w.(json/csv)`, `COVID19VaccDosesAdministered_sex_w.(json/csv)`
- added model documentation `VaccinationWeeklyIncomingData`
- added new property `median_R_mean_mean7d` to R<sub>e</sub> data file `COVID19Re_geoRegion.(json/csv)`
- updated model documentation `ReDailyIncomingData`

### v.0.4.0
**Released**: `18.02.2021`
**Description**:
- added new source file for virus variant data: `COVID19Variants.(json/csv)`
- added model documentation `VirusVariantsDailyIncomingData`

### v.0.3.3
**Released**: `16.02.2021`
**Description**:
- added new source file for fully vaccinated persons: `COVID19FullyVaccPersons.(json/csv)`
- updated model documentation `VaccinationIncomingData`

#### v.0.3.2
**Released**: `05.02.2021`
**Description**:
- added type `COVID19VaccDosesReceived` data for CHFL to `COVID19VaccDosesDelivered.(json/csv)` (doses received by manufacturers)
- updated model documentation `VaccinationIncomingData`

#### v.0.3.1
**Released**: `28.01.2021`
**Description**:
- added new source files for vaccination data: `COVID19VaccDosesDelivered.(json/csv)`, `COVID19VaccDosesAdministered.(json/csv)`
- added new model documentation `VaccinationIncomingData`

#### v.0.3.0
**Released**: `13.01.2021`
**Description**:
- added new daily source file for international cases data `COVID19IntCases.(json/csv)`
- added new model documentation `InternationalDailyIncomingData`

#### v.0.2.0
**Released**: `17.12.2020`
**Description**:
- added new daily source file for R<sub>e</sub> Value by Cantons, CH and FL `COVID19Re_geoRegion.(json/csv)`
- added new source file for mandatory quarantine requirement when entering Switzerland `COVID19IntQua.(json/csv)`

#### v0.1.2

**Released**: `15.12.2020`

**Description**:
 - added new weekly source files for cases, hospitalisations, deaths and tests by geoRegion only
   - `COVID19Cases_geoRegion_w.(json/csv)`
   - `COVID19Hosp_geoRegion_w.(json/csv)`
   - `COVID19Death_geoRegion_w.(json/csv)`
   - `COVID19Test_geoRegion_w.(json/csv)`
 - added `default` weekly source file location group to `sources` of the data context for weekly data by geoRegion only
 - added new source file for daily hospital capacity data timelines by geoRegion `COVID19HospCapacity_geoRegion.(json/csv)`
 - added new model documentation for `HospCapacityDailyIncomingData`, check `https://www.covid19.admin.ch/api/data/documentation` for html version of model documentations
 - added `hospCapacity` file source location to `sources` of the data context
 - added fields `offset_Phase2b`, `sumTotal_Phase2b`, `inzsumTotal_Phase2b` and `anteil_pos_phase2b`to `DailyIncomingData`

#### v0.1.1
**Released**: `20.11.2020`

**Description**:
 - added new source file for test data by test type (pcr/antigen) `COVID19Test_geoRegion_PCR_Antigen.(json/csv)`
 - added `testPcrAntigen` file source location to `sources` of the data context
 - added fields `entries_pos` and `entries_neg` to DailyIncomingData

#### v0.1.0

**Released**: `05.11.2020`

**Description**: Initial version

## Data Context API

### Current Data Context
The current data context can be queried at a static location and provides information about the source date of the current data and source file locations.

```
GET https://www.covid19.admin.ch/api/data/context
```

### Data Model
`sourceDate` contains the overall source date of the data. Multiple publications per day are possible with the same `sourceDate`. Check the `dataVersion` to decide if you need to update your data.

`dataVersion` contains the current data version. Download links may be generated directly using the `dataVersion` but using the pre-generated urls in the `sources` field (see documentation below) is recommended.

`sources` contains information about the source location of all currently available raw source data (zip and individual files) to download as well as the schema version/content. OpenData DCAT-AP-CH metadata information will be published in the future in addition to this API to further facilitate automation of data downloads.

```
{
  "sources": {
    "schema": {
      "version": "{current-schema-version}",
      "jsonSchema": "{current-schema-location-url}"
    },
    "readme": "{current-readme-location-url}",
    "zip": {
      "json": "{current-source-location-url}",
      "csv": "{current-source-location-url}"
    },
    "individual": {
      "json": {
        "daily": {
          "cases": "{current-source-location-url}",
          "hosp": "{current-source-location-url}",
          "death": "{current-source-location-url}",
          "test": "{current-source-location-url}",
          "testPcrAntigen": "{current-source-location-url}",
          "hospCapacity": "{current-source-location-url}",
          "re": "{current-source-location-url}",
          "intCases": "{current-source-location-url}"
        },
        "weekly": {
          "byAge": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
          "bySex": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
          "default": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
        },
        "dailyReport": "{current-source-location-url}",
        "contactTracing": "{current-source-location-url}",
        "intQua": "{current-source-location-url}"
      },
      "csv": {
        "daily": {
          "cases": "{current-source-location-url}",
          "hosp": "{current-source-location-url}",
          "death": "{current-source-location-url}",
          "test": "{current-source-location-url}",
          "testPcrAntigen": "{current-source-location-url}",
          "hospCapacity": "{current-source-location-url}",
          "re": "{current-source-location-url}",
          "intCases": "{current-source-location-url}"
        },
        "weekly": {
          "byAge": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
          "bySex": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
          "default": {
            "cases": "{current-source-location-url}",
            "hosp": "{current-source-location-url}",
            "death": "{current-source-location-url}",
            "test": "{current-source-location-url}"
          },
        },
        "dailyReport": "{current-source-location-url}",
        "contactTracing": "{current-source-location-url}",
        "intQua": "{current-source-location-urxl}"
      }
    }
  }
}
```

### Data Context History

The data context history can be queried at a static location and provides a list of previously published data contexts.

```
GET https://www.covid19.admin.ch/api/data/context/history
```
Multiple publications per day are possible due to delays or data corrections etc. By default only the latest data context per day is returned from the API. Query `https://www.covid19.admin.ch/api/data/context/history/full` for all previously published data contexts (multiple per day returned).

### Data Model
`current` Url pointing to the current data context.

`documentation` Url of this documentation

`dataContexts` List of the individual data context history items

### Data Model (individual data context history item)
`date` Day of the publication, formatted as YYYY-MM-DD (e.g. 2021-03-18)

`latest` Multiple publications per day are possible due to delays or data corrections etc. This property indicates if the current data context is the latest one published for this day.

`published` Date and time of publication formatted as ISO 8601 string (e.g. 2021-03-18T13:30:35+01:00)

`dataVersion` Data version of thsi dataContext (see documentation above for details)

`dataContextUrl` Url pointing to the full data context object.

```
{
    "current": "https://www.covid19.admin.ch/api/data/context",
    "documentation": "https://www.covid19.admin.ch/api/data/documentation#data-context-history",
    "dataContexts: [
        {
            "date": "2021-03-18",
            "published": "2021-03-18T13:30:35+01:00",
            "latest": true,
            "dataVersion": "20210318-dec0fnrh",
            "dataContextUrl": "https://www.covid19.admin.ch/api/data/20210318-dec0fnrh/context"
        }
    ]
}
```
