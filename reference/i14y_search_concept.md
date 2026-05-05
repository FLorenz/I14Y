# Search for a Concept Summary

Search for a Concept Summary

## Usage

``` r
i14y_search_concept(
  query = NULL,
  language = "de",
  page = 1,
  pageSize = 1000,
  publishers = NULL,
  themes = NULL,
  conceptValueTypes = NULL,
  registrationStatuses = NULL
)
```

## Arguments

- query:

  string. Search query.

- language:

  string. The language of the response data.

- page:

  integer. The number of the result page to return.

- pageSize:

  integer. The size of each result page.

- publishers:

  vector of strings. Filter with Publishers identifiers.

- themes:

  vector of strings. Filter with theme codes.

- conceptValueTypes:

  character vector. One or more concept value types to filter by.

- registrationStatuses:

  character vector. One or more registration statuses to filter by.

## Value

a tibble

## Examples

``` r
i14y_search_concept(query = "noga", language = "en")
#> Error in httr2::req_perform(req): HTTP 404 Not Found.
```
