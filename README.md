





QUIZ:
-----------------------------

Question - 1:
    134.5 MiB

Question - 2:
    green_tripdata_2020-04.csv

Question - 3:
    24,648,499

            select count(*) from (
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_01`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_02`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_03`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_04`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_05`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_06`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_07`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_08`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_09`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_10`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_11`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2020_12`
            )
            ;

Question - 4:
    1,734,051

            select count(*) from (
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_01`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_02`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_03`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_04`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_05`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_06`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_07`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_08`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_09`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_10`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_11`
                union all
                select VendorID from `datazoomcamp-484706.NYCTaxiDataset.green_tripdata_2020_12`
            )
            ;

Question - 5:
    1,925,152

            select count(*) from `datazoomcamp-484706.NYCTaxiDataset.yellow_tripdata_2021_03`; 

Question - 6:
    Add a timezone property set to America/New_York in the Schedule trigger configuration.
