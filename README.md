# GLAMI data analyst assignment.

You are given a series of tasks from one of the business development managers.

**Task 1:** use SQL to find ad-hoc answers to 2 questions below. You should use dataset `providers`. Leave comments in the code if necessary.
- Which country has the most and the least number of `active_items` for paid providers (column `is_paid` = 1)?
- What is the biggest group of providers by `status` and `status_label` in Hungary? How many providers are in that group?

**Task 2:** use SQL to properly combine `providers` and `exits_providers` and then use the resulting dataset in building a report. I would prefer to see the report in Tableau but you can use any similar tool of your choice as long as you can share the report with me. The report can look like a table with providers as rows and weeks as columns, or it can be a graph with trend lines. The form is up to you.
- The manager would like to see a report that would show top 5 (per number of `exits`) providers (`provider_name`) - the weekly development of their revenue during the whole available period.
- Report should have the following filters: `country`, `device`, `ecommerce_tracking_source`.
- Report should have the following parameter: `Currency`. Its values must be 'Local' or 'Euro' and it would control which kind of revenue is displayed: `revenue_local_currency` or `revenue_euro`.

Include the comments to present your solution and send it to vyacheslav.gatin@glami.cz.

Thanks and good luck.

## Assets:
In the repository you will find two CSV files - `providers` and `exits_providers` - that you can load them into SQL database of your choice (e.g. Google Big Query), or you can use Keboola project which was created for you (please find the invitation in your mailbox). For those of you who wants to work with Keboola, please create separate transformation and name it by your name.
