## 2.0.2 (Unreleased)

ENHANCEMENTS:

* Check for errors when setting aggregate values on read [GH-8]

BUG FIXES:

* Fixes updates to content items not being recognized [GH-11]

## 2.0.1 (April 30, 2020)

FEATURES:

* **New Resource:** `sumologic_connection` ([#3](https://github.com/terraform-providers/terraform-provider-github/issues/3))

## 2.0.0 (April 09, 2020)

FEATURES:

* **New Resource:** `sumologic_partition` ([#79](https://github.com/terraform-providers/terraform-provider-github/issues/79))
* **New Resource:** `sumologic_field_extraction_rule` ([#83](https://github.com/terraform-providers/terraform-provider-github/issues/83))
* **New Resource:** `sumologic_content` ([#85](https://github.com/terraform-providers/terraform-provider-github/issues/85))

ENHANCEMENTS:

* Travis running acceptance tests ([#92](https://github.com/terraform-providers/terraform-provider-github/issues/92))

BUG FIXES:

* resource/sumologic_partition: Fixes decomissioning of partitions ([#86](https://github.com/terraform-providers/terraform-provider-github/issues/86))

DEPRECATIONS:

* resource/sumologic_collector_ingest_budget_assignment: Deprecated in favor of assigning ingest budgets through the _budget field attribute of collectors ([#135](https://github.com/terraform-providers/terraform-provider-github/issues/135))
* resource/sumologic_collector: Deprecated `lookup_by_name` and `destroy` attributes ([#136](https://github.com/terraform-providers/terraform-provider-github/issues/136))
* resource/sumologic_sources: Deprecated `lookup_by_name` and `destroy` attributes ([#137](https://github.com/terraform-providers/terraform-provider-github/issues/137))