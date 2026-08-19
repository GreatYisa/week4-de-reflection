 * Ingestion: We load the raw data as it is.. It is same as its found in the sources systems
 * Standardize: We fix inconsistent data ( ex- date `06/01/2024` → `2024-06-01`)
 * Handle missing values: We recover missing customer_name or customer_email.
 * Deduplicate: We remove rows that represent the same real-wprld order logged more than once.
 * Validate: We check every product and customer in our data has a matching record in the reference tables.
 * Load: We write final clean dataset to a differnt sheet of the excel.
   
