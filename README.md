# cyclonedx-property-taxonomy
Appknox CycloneDX Property Taxonomy


This is the official Appknox CycloneDX property namespace and name taxonomy. It documents all custom key/value `properties` that may be added to components in CycloneDX SBOMs created using the Appknox platform.

For more information about CycloneDX property taxonomies, refer to the [official documentation](https://github.com/CycloneDX/cyclonedx-property-taxonomy).

## `appknox` Namespace Taxonomy

| Namespace             | Description                                                                                                    |
| --------------------- | -------------------------------------------------------------------------------------------------------------- |
| `appknox:metadata`    | Namespace for all Appknox-specific properties dealing with top-level metadata values about bill of materials   |
| `appknox:component`   | Namespace for all Appknox-specific properties related to components.                                           |

## `appknox:metadata` Namespace Taxonomy

| Property Name                             | Description                                            |
| ----------------------------------------- | ------------------------------------------------------ |
| `appknox:metadata:mycroft_version`        | The version of Mycroft that is used to scan the App    |
| `appknox:metadata:sherlock_version`       | The version of Sherlock that is used to scan the App   |
| `appknox:metadata:enola_version`          | The version of Enola that is used to scan the App      |
| `appknox:metadata:scan_datetime`          | The date and time when the App was originally scanned  |
| `appknox:metadata:file_id`                | UUID of the App that scanned                           |
| `appknox:metadata:file_id`                | UUID of the Project that the App belongs to            |

## `appknox:component` Namespace Taxonomy

| Property Name                          | Description                             |
| -------------------------------------- | --------------------------------------- |
| `appknox:component:vulnerability_id;`  | UUID for vulnerability                  |
| `appknox:component:analysis_id`        | UUID for analysis/scan                  |

