# SPDX operations profile

- [1. Property `SPDX operations profile > title`](#title)
- [2. Property `SPDX operations profile > exportControl`](#exportControl)
  - [2.1. Property `SPDX operations profile > exportControl > classifications`](#exportControl_classifications)
    - [2.1.1. SPDX operations profile > exportControl > classifications > export control classification](#autogenerated_heading_2)
      - [2.1.1.1. Property `SPDX operations profile > exportControl > classifications > export control classification > classificationSystem`](#exportControl_classifications_items_classificationSystem)
      - [2.1.1.2. Property `SPDX operations profile > exportControl > classifications > export control classification > classificationValue`](#exportControl_classifications_items_classificationValue)
      - [2.1.1.3. Property `SPDX operations profile > exportControl > classifications > export control classification > comment`](#exportControl_classifications_items_comment)
  - [2.2. Property `SPDX operations profile > exportControl > notRequired`](#exportControl_notRequired)
  - [2.3. Property `SPDX operations profile > exportControl > qaQuestions`](#exportControl_qaQuestions)
    - [2.3.1. SPDX operations profile > exportControl > qaQuestions > exportControlQuestion](#autogenerated_heading_3)
      - [2.3.1.1. Property `SPDX operations profile > exportControl > qaQuestions > exportControlQuestion > question`](#exportControl_qaQuestions_items_question)
      - [2.3.1.2. Property `SPDX operations profile > exportControl > qaQuestions > exportControlQuestion > clarification`](#exportControl_qaQuestions_items_clarification)
  - [2.4. Property `SPDX operations profile > exportControl > specialTechnology`](#exportControl_specialTechnology)
    - [2.4.1. Property `SPDX operations profile > exportControl > specialTechnology > includesCrypto?`](#exportControl_specialTechnology_includesCrypto)
    - [2.4.2. Property `SPDX operations profile > exportControl > specialTechnology > cryptoDetail`](#exportControl_specialTechnology_cryptoDetail)
    - [2.4.3. Property `SPDX operations profile > exportControl > specialTechnology > externalServerCommunication?`](#exportControl_specialTechnology_externalServerCommunication)
    - [2.4.4. Property `SPDX operations profile > exportControl > specialTechnology > includesArtificialIntelligence?`](#exportControl_specialTechnology_includesArtificialIntelligence)
  - [2.5. Property `SPDX operations profile > exportControl > purpose`](#exportControl_purpose)
  - [2.6. Property `SPDX operations profile > exportControl > countryOfOrigin`](#exportControl_countryOfOrigin)
    - [2.6.1. SPDX operations profile > exportControl > countryOfOrigin > countryOfOrigin items](#autogenerated_heading_4)
  - [2.7. Property `SPDX operations profile > exportControl > manufacturer`](#exportControl_manufacturer)
  - [2.8. Property `SPDX operations profile > exportControl > manufacturerID`](#exportControl_manufacturerID)
  - [2.9. Property `SPDX operations profile > exportControl > address`](#exportControl_address)
  - [2.10. Property `SPDX operations profile > exportControl > website`](#exportControl_website)
- [3. Property `SPDX operations profile > otherBusiness`](#otherBusiness)
  - [3.1. Property `SPDX operations profile > otherBusiness > sourceCodeProvision`](#otherBusiness_sourceCodeProvision)
    - [3.1.1. SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation](#autogenerated_heading_5)
      - [3.1.1.1. Property `SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation > sourceLink`](#otherBusiness_sourceCodeProvision_items_sourceLink)
      - [3.1.1.2. Property `SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation > relatedSpdxElement`](#otherBusiness_sourceCodeProvision_items_relatedSpdxElement)
- [4. Property `SPDX operations profile > obligations`](#obligations)
  - [4.1. SPDX operations profile > obligations > Obligation](#autogenerated_heading_6)
    - [4.1.1. Property `SPDX operations profile > obligations > Obligation > obligation`](#obligations_items_obligation)
    - [4.1.2. Property `SPDX operations profile > obligations > Obligation > source`](#obligations_items_source)
- [5. Property `SPDX operations profile > annotations`](#annotations)
  - [5.1. SPDX operations profile > annotations > Annotation](#autogenerated_heading_7)

**Title:** SPDX operations profile

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                           | Pattern | Type            | Deprecated | Definition | Title/Description                                                |
| ---------------------------------- | ------- | --------------- | ---------- | ---------- | ---------------------------------------------------------------- |
| - [title](#title )                 | No      | string          | No         | -          | -                                                                |
| - [exportControl](#exportControl ) | No      | object          | No         | -          | This is for export control data.                                 |
| - [otherBusiness](#otherBusiness ) | No      | object          | No         | -          | Other information, that might impact business use.               |
| - [obligations](#obligations )     | No      | array of object | No         | -          | Obligations that impact and/or confine the use of the component. |
| - [annotations](#annotations )     | No      | array of string | No         | -          | Any remarks that are not covered by provided fields.             |

## <a name="title"></a>1. Property `SPDX operations profile > title`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

## <a name="exportControl"></a>2. Property `SPDX operations profile > exportControl`

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

**Description:** This is for export control data.

| Property                                                 | Pattern | Type            | Deprecated | Definition | Title/Description                                                |
| -------------------------------------------------------- | ------- | --------------- | ---------- | ---------- | ---------------------------------------------------------------- |
| - [classifications](#exportControl_classifications )     | No      | array of object | No         | -          | export control classifications.                                  |
| - [notRequired](#exportControl_notRequired )             | No      | boolean         | No         | -          | Set this true, if no export control context is given.            |
| - [qaQuestions](#exportControl_qaQuestions )             | No      | array of object | No         | -          | Individual, Q&A style queries not covered by any standard field. |
| - [specialTechnology](#exportControl_specialTechnology ) | No      | object          | No         | -          | -                                                                |
| - [purpose](#exportControl_purpose )                     | No      | string          | No         | -          | Main purpose of this component.                                  |
| - [countryOfOrigin](#exportControl_countryOfOrigin )     | No      | array of string | No         | -          | country / countries of origin                                    |
| - [manufacturer](#exportControl_manufacturer )           | No      | string          | No         | -          | -                                                                |
| - [manufacturerID](#exportControl_manufacturerID )       | No      | string          | No         | -          | ID/reference for original manufacturer dataset                   |
| - [address](#exportControl_address )                     | No      | string          | No         | -          | Manufacturer Address                                             |
| - [website](#exportControl_website )                     | No      | string          | No         | -          | -                                                                |

### <a name="exportControl_classifications"></a>2.1. Property `SPDX operations profile > exportControl > classifications`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of object` |
| **Required** | No                |

**Description:** export control classifications.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                       | Description                   |
| --------------------------------------------------------------------- | ----------------------------- |
| [export control classification](#exportControl_classifications_items) | export control classification |

#### <a name="autogenerated_heading_2"></a>2.1.1. SPDX operations profile > exportControl > classifications > export control classification

**Title:** export control classification

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

**Description:** export control classification

| Property                                                                             | Pattern | Type   | Deprecated | Definition | Title/Description                                                                                                      |
| ------------------------------------------------------------------------------------ | ------- | ------ | ---------- | ---------- | ---------------------------------------------------------------------------------------------------------------------- |
| - [classificationSystem](#exportControl_classifications_items_classificationSystem ) | No      | string | No         | -          | referenced export control classification system (e.g. 'ECCN' or 'EAR' for US, 'Ausfuhrlistennummer' for Germany ,...). |
| - [classificationValue](#exportControl_classifications_items_classificationValue )   | No      | string | No         | -          | e.g. EAR99                                                                                                             |
| - [comment](#exportControl_classifications_items_comment )                           | No      | string | No         | -          | -                                                                                                                      |

##### <a name="exportControl_classifications_items_classificationSystem"></a>2.1.1.1. Property `SPDX operations profile > exportControl > classifications > export control classification > classificationSystem`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** referenced export control classification system (e.g. 'ECCN' or 'EAR' for US, 'Ausfuhrlistennummer' for Germany ,...).

##### <a name="exportControl_classifications_items_classificationValue"></a>2.1.1.2. Property `SPDX operations profile > exportControl > classifications > export control classification > classificationValue`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** e.g. EAR99 

##### <a name="exportControl_classifications_items_comment"></a>2.1.1.3. Property `SPDX operations profile > exportControl > classifications > export control classification > comment`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="exportControl_notRequired"></a>2.2. Property `SPDX operations profile > exportControl > notRequired`

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

**Description:** Set this true, if no export control context is given.

### <a name="exportControl_qaQuestions"></a>2.3. Property `SPDX operations profile > exportControl > qaQuestions`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of object` |
| **Required** | No                |

**Description:** Individual, Q&A style queries not covered by any standard field.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                           | Description |
| --------------------------------------------------------- | ----------- |
| [exportControlQuestion](#exportControl_qaQuestions_items) | -           |

#### <a name="autogenerated_heading_3"></a>2.3.1. SPDX operations profile > exportControl > qaQuestions > exportControlQuestion

**Title:** exportControlQuestion

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

| Property                                                           | Pattern | Type   | Deprecated | Definition | Title/Description                                                                        |
| ------------------------------------------------------------------ | ------- | ------ | ---------- | ---------- | ---------------------------------------------------------------------------------------- |
| - [question](#exportControl_qaQuestions_items_question )           | No      | string | No         | -          | e.g. 'Was the software developed for specific (military) application and product areas?' |
| - [clarification](#exportControl_qaQuestions_items_clarification ) | No      | string | No         | -          | -                                                                                        |

##### <a name="exportControl_qaQuestions_items_question"></a>2.3.1.1. Property `SPDX operations profile > exportControl > qaQuestions > exportControlQuestion > question`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** e.g. 'Was the software developed for specific (military) application and product areas?'

##### <a name="exportControl_qaQuestions_items_clarification"></a>2.3.1.2. Property `SPDX operations profile > exportControl > qaQuestions > exportControlQuestion > clarification`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="exportControl_specialTechnology"></a>2.4. Property `SPDX operations profile > exportControl > specialTechnology`

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

| Property                                                                                              | Pattern | Type             | Deprecated | Definition | Title/Description                                                          |
| ----------------------------------------------------------------------------------------------------- | ------- | ---------------- | ---------- | ---------- | -------------------------------------------------------------------------- |
| - [includesCrypto?](#exportControl_specialTechnology_includesCrypto )                                 | No      | enum (of string) | No         | -          | -                                                                          |
| - [cryptoDetail](#exportControl_specialTechnology_cryptoDetail )                                      | No      | string           | No         | -          | Cryptography/encryption technology used / encryption algorithm's strength. |
| - [externalServerCommunication?](#exportControl_specialTechnology_externalServerCommunication )       | No      | enum (of string) | No         | -          | -                                                                          |
| - [includesArtificialIntelligence?](#exportControl_specialTechnology_includesArtificialIntelligence ) | No      | enum (of string) | No         | -          | -                                                                          |

#### <a name="exportControl_specialTechnology_includesCrypto"></a>2.4.1. Property `SPDX operations profile > exportControl > specialTechnology > includesCrypto?`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "Yes"
* "No"
* "NOASSERTION"

#### <a name="exportControl_specialTechnology_cryptoDetail"></a>2.4.2. Property `SPDX operations profile > exportControl > specialTechnology > cryptoDetail`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Cryptography/encryption technology used / encryption algorithm's strength.

#### <a name="exportControl_specialTechnology_externalServerCommunication"></a>2.4.3. Property `SPDX operations profile > exportControl > specialTechnology > externalServerCommunication?`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "Yes"
* "No"
* "NOASSERTION"

#### <a name="exportControl_specialTechnology_includesArtificialIntelligence"></a>2.4.4. Property `SPDX operations profile > exportControl > specialTechnology > includesArtificialIntelligence?`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "Yes"
* "No"
* "NOASSERTION"

### <a name="exportControl_purpose"></a>2.5. Property `SPDX operations profile > exportControl > purpose`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Main purpose of this component.

### <a name="exportControl_countryOfOrigin"></a>2.6. Property `SPDX operations profile > exportControl > countryOfOrigin`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |

**Description:** country / countries of origin

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                               | Description |
| ------------------------------------------------------------- | ----------- |
| [countryOfOrigin items](#exportControl_countryOfOrigin_items) | -           |

#### <a name="autogenerated_heading_4"></a>2.6.1. SPDX operations profile > exportControl > countryOfOrigin > countryOfOrigin items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="exportControl_manufacturer"></a>2.7. Property `SPDX operations profile > exportControl > manufacturer`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

### <a name="exportControl_manufacturerID"></a>2.8. Property `SPDX operations profile > exportControl > manufacturerID`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** ID/reference for original manufacturer dataset

### <a name="exportControl_address"></a>2.9. Property `SPDX operations profile > exportControl > address`

|              |            |
| ------------ | ---------- |
| **Type**     | `string`   |
| **Required** | No         |
| **Format**   | `textarea` |

**Description:** Manufacturer Address

### <a name="exportControl_website"></a>2.10. Property `SPDX operations profile > exportControl > website`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

## <a name="otherBusiness"></a>3. Property `SPDX operations profile > otherBusiness`

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

**Description:** Other information, that might impact business use.

| Property                                                     | Pattern | Type            | Deprecated | Definition | Title/Description                                                      |
| ------------------------------------------------------------ | ------- | --------------- | ---------- | ---------- | ---------------------------------------------------------------------- |
| - [sourceCodeProvision](#otherBusiness_sourceCodeProvision ) | No      | array of object | No         | -          | Links for source provision for distribution. Links must be persistent! |

### <a name="otherBusiness_sourceCodeProvision"></a>3.1. Property `SPDX operations profile > otherBusiness > sourceCodeProvision`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of object` |
| **Required** | No                |

**Description:** Links for source provision for distribution. Links must be persistent!

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                        | Description |
| ------------------------------------------------------ | ----------- |
| [Annotation](#otherBusiness_sourceCodeProvision_items) | -           |

#### <a name="autogenerated_heading_5"></a>3.1.1. SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation

**Title:** Annotation

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

| Property                                                                             | Pattern | Type   | Deprecated | Definition | Title/Description                                         |
| ------------------------------------------------------------------------------------ | ------- | ------ | ---------- | ---------- | --------------------------------------------------------- |
| - [sourceLink](#otherBusiness_sourceCodeProvision_items_sourceLink )                 | No      | string | No         | -          | -                                                         |
| - [relatedSpdxElement](#otherBusiness_sourceCodeProvision_items_relatedSpdxElement ) | No      | string | No         | -          | Reference to the respctive component in the SPDX document |

##### <a name="otherBusiness_sourceCodeProvision_items_sourceLink"></a>3.1.1.1. Property `SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation > sourceLink`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

##### <a name="otherBusiness_sourceCodeProvision_items_relatedSpdxElement"></a>3.1.1.2. Property `SPDX operations profile > otherBusiness > sourceCodeProvision > Annotation > relatedSpdxElement`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Reference to the respctive component in the SPDX document

## <a name="obligations"></a>4. Property `SPDX operations profile > obligations`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of object` |
| **Required** | No                |

**Description:** Obligations that impact and/or confine the use of the component.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be  | Description |
| -------------------------------- | ----------- |
| [Obligation](#obligations_items) | -           |

### <a name="autogenerated_heading_6"></a>4.1. SPDX operations profile > obligations > Obligation

**Title:** Obligation

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

| Property                                       | Pattern | Type   | Deprecated | Definition | Title/Description         |
| ---------------------------------------------- | ------- | ------ | ---------- | ---------- | ------------------------- |
| - [obligation](#obligations_items_obligation ) | No      | string | No         | -          | Conditions to follow.     |
| - [source](#obligations_items_source )         | No      | string | No         | -          | Origin of the obligation. |

#### <a name="obligations_items_obligation"></a>4.1.1. Property `SPDX operations profile > obligations > Obligation > obligation`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Conditions to follow.

#### <a name="obligations_items_source"></a>4.1.2. Property `SPDX operations profile > obligations > Obligation > source`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Origin of the obligation.

## <a name="annotations"></a>5. Property `SPDX operations profile > annotations`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |

**Description:** Any remarks that are not covered by provided fields.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be  | Description |
| -------------------------------- | ----------- |
| [Annotation](#annotations_items) | -           |

### <a name="autogenerated_heading_7"></a>5.1. SPDX operations profile > annotations > Annotation

**Title:** Annotation

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2024-03-06 at 10:46:03 +0100
