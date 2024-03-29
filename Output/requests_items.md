---
title: requests_items.sql
---
# Documentation: requests_items.sql

## Attributes:

|   Attribute # | Attribute                                 | Type   | Source - Schema   | Source - Table   | Source - Attribute   | Source - Type   | Source - Multiple values   | Aggregation   | Description   | Notes   |
|--------------:|:------------------------------------------|:-------|:------------------|:-----------------|:---------------------|:----------------|:---------------------------|:--------------|:--------------|:--------|
|             1 | request_id                                | uuid   |                   |                  |                      |                 |                            |               |               |         |
|             2 | item_id                                   | uuid   |                   |                  |                      |                 |                            |               |               |         |
|             3 | request_date                              | date   |                   |                  |                      |                 |                            |               |               |         |
|             4 | request_type                              | text   |                   |                  |                      |                 |                            |               |               |         |
|             5 | request_status                            | text   |                   |                  |                      |                 |                            |               |               |         |
|             6 | pickup_service_point_id                   | uuid   |                   |                  |                      |                 |                            |               |               |         |
|             7 | pickup_service_point_name                 | text   |                   |                  |                      |                 |                            |               |               |         |
|             8 | pickup_service_point_disc_disp_name       | text   |                   |                  |                      |                 |                            |               |               |         |
|             9 | in_transit_dest_serv_point_id             | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            10 | in_transit_dest_serv_point_name           | text   |                   |                  |                      |                 |                            |               |               |         |
|            11 | in_transit_dest_serv_point_disc_disp_name | text   |                   |                  |                      |                 |                            |               |               |         |
|            12 | requester_id                              | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            13 | fulfillment_preference                    | text   |                   |                  |                      |                 |                            |               |               |         |
|            14 | patron_group_id                           | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            15 | patron_group_name                         | text   |                   |                  |                      |                 |                            |               |               |         |
|            16 | item_level_call_number                    | text   |                   |                  |                      |                 |                            |               |               |         |
|            17 | barcode                                   | text   |                   |                  |                      |                 |                            |               |               |         |
|            18 | chronology                                | text   |                   |                  |                      |                 |                            |               |               |         |
|            19 | item_copy_number                          | text   |                   |                  |                      |                 |                            |               |               |         |
|            20 | item_permanent_location_id                | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            21 | item_temporary_location_id                | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            22 | enumeration                               | text   |                   |                  |                      |                 |                            |               |               |         |
|            23 | item_effective_location_id                | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            24 | item_effective_location_name              | text   |                   |                  |                      |                 |                            |               |               |         |
|            25 | item_permanent_location_name              | text   |                   |                  |                      |                 |                            |               |               |         |
|            26 | item_temporary_location_name              | text   |                   |                  |                      |                 |                            |               |               |         |
|            27 | holdings_record_id                        | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            28 | hrid                                      | text   |                   |                  |                      |                 |                            |               |               |         |
|            29 | item_identifier                           | text   |                   |                  |                      |                 |                            |               |               |         |
|            30 | material_type_id                          | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            31 | material_type_name                        | text   |                   |                  |                      |                 |                            |               |               |         |
|            32 | number_of_pieces                          | text   |                   |                  |                      |                 |                            |               |               |         |
|            33 | item_permanent_loan_type_id               | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            34 | item_permanent_loan_type_name             | text   |                   |                  |                      |                 |                            |               |               |         |
|            35 | item_temporary_loan_type_id               | uuid   |                   |                  |                      |                 |                            |               |               |         |
|            36 | item_temporary_loan_type_name             | text   |                   |                  |                      |                 |                            |               |               |         |