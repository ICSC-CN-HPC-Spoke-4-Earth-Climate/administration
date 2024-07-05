# administration

Repository to collect the code used for the Organization's administrative tasks.
Under **Issues**, there is a template to request the creation of new repositories.

- `issue2dataframe` downloads the list of issues from this repository, reads their description, extracts relevant fields, compiles them into a table, and saves it.
- `dataframe2project_table` loads the table created by `issue2dataframe` and adds the items to the GitHub project *Repository List*.
