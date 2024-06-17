# SPDX 3 Operations profile
SPDX 3 Operations profile discussion.

The Operations profile idea came up after the LF Europe in Bilboa – September 2023. 

The proposal aims to add fields relating to operations, like
* Application facts
* Deliverable facts
* Export control
* Special technology – including AI
* Country of origin
* Obligations


## contribution / commenting
In the JSON schema "$comment" keyword is used for annotations for the purpose of the ongoing discussions. The "$comment" keys and their values will be removed at some point.

## hints
To try out and/or visualize the JSON schema, you could use [https://json-editor.github.io/json-editor/](https://json-editor.github.io/json-editor/).

## license
This work is licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)

# Changes
## Meeting 2024-02-23
* Move 3.10 (exportControl > classifications)to the top of the list
* Remove 3.11 (exportControl > comments)
* Remove 4.1 (otherBusiness > patentInformation)

## 2024-03-06 spontaneous cleanup
* Rename to "SPDX operations profile"
* Remove "dataVersion" (No value during draft phase. Versioning is done by Git.)

## 2024-04-12
* Add json schema data from Marcel Kurzmann

## 2024-06-17
* Rename files und update description to fit "SPDX Operations profile"