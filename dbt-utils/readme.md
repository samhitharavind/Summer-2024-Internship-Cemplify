# What is it?
&nbsp; dbt-utils is a collection of SQL scripts and macros which are used to assist the data validation and testing process within dbt (data build tool). In order to use dbt, you must first add it to your package file, and then install the function.

# Common Macros
&nbsp; Two examples of useful macros within the dbt-utils package are:
- 'assert_*' macros: Used to apply certain conditions within the data, ex: 'assert_column_count', 'assert_has_rows', 'assert_distinct'.
- 'test_*' macros: Used to create customized tests within the data, ex: 'test_non_null', 'test_unique', 'test_schema'.

# Additional Information
&nbsp; dbt-utils gives users the option to write tests directly within dbt models or within seprarate test files, and after writing your tests, they can be run using the 'dbt test' command. Overall, the dbt-utils package provides users with SQL scripts and macros that allow for more efficient data customization and testing, which in turn improve the data validation and testing process.
