# Search the catalog for datasets, data services and public services.

Search the catalog for datasets, data services and public services.

## Usage

``` r
i14y_search_catalog(
  query = NULL,
  language = "de",
  accessRights = NULL,
  formats = NULL,
  publishers = NULL,
  statuses = NULL,
  themes = NULL,
  types = NULL,
  page = NULL,
  pageSize = NULL
)
```

## Arguments

- query:

  string. The search query

- language:

  string. The language to use for the search

- accessRights:

  vector of strings. Only results with one of the specified access
  rights (PUBLIC, NON_PUBLIC, RESTRICTED) are returned

- formats:

  vector of strings. Only results with at least one distribution
  providing one of the specified formats are returned

- publishers:

  vector of strings. Only results with one of the specified publishers
  are returned

- statuses:

  vector of strings. Only results with one of the specified registration
  statuses are returned

- themes:

  vector of strings. Only results corresponding to one of the specified
  themes are returned

- types:

  vector of strings. Only results with one of the specified types
  (Dataset, DataService, PublicService) are returned

- page:

  integer. The number of the result page to return

- pageSize:

  integer. The size of each result page

## Value

a tibble

## Examples

``` r
i14y_search_catalog(query = "noga")
#> Error in httr2::req_perform(req): HTTP 404 Not Found.
```
