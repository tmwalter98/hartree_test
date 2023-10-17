# Sample test

Timothy Walter

Email: [inbox@timothywalter.dev](mailto:inbox@timothywalter.dev)

Mobile number: [215-933-9093](tel:2159339093)

## Solution

Solutions can be found in `sample_test.ipynb`.  A PDF version is available under `sample_test.pdf`.

Output datasets are under `result_dataset_pandas.csv` and `result_dataset_beam.csv`.

## Prompt

Please do same exercise using two different framework.

Framework 1. pandas
framework 2. apache beam python https://beam.apache.org/documentation/sdks/python/


using two input files dataset1 and dataset2 

join dataset1 with dataset2 and get tier

generate below output file

legal_entity, counterparty, tier, max(rating by counterparty), sum(value where status=ARAP), sum(value where status=ACCR)

Also create new record to add total for each of legal entity, counterparty & tier.

Sample data:
legal_entity, counterparty, tier, max(rating by counterparty), sum(value where status=ARAP), sum(value where status=ACCR)
L1,Total, Total, calculated_value, calculated_value,calculated_value
L1, C1, Total,calculated_value, calculated_value,calculated_value
Total,C1,Total,calculated_value, calculated_value,calculated_value
Total,Total,1,calculated_value, calculated_value,calculated_value
L2,Total,Total,calculated_value, calculated_value,calculated_value
....
like all other values.

where caluclated_value in sample data needs to be calculated using above method.
