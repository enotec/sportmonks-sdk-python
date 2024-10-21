# Shared Types

```python
from sportmonks.types import Pagination, RateLimit, Subscription, Timezone
```

# Core

## Continents

Types:

```python
from sportmonks.types.core import ContinentRetrieveResponse, ContinentListResponse
```

Methods:

- <code title="get /{version}/core/continents/{continentId}">client.core.continents.<a href="./src/sportmonks/resources/core/continents.py">retrieve</a>(continent_id, \*, version) -> <a href="./src/sportmonks/types/core/continent_retrieve_response.py">ContinentRetrieveResponse</a></code>
- <code title="get /{version}/core/continents">client.core.continents.<a href="./src/sportmonks/resources/core/continents.py">list</a>(version, \*\*<a href="src/sportmonks/types/core/continent_list_params.py">params</a>) -> <a href="./src/sportmonks/types/core/continent_list_response.py">SyncPaginatedAPICall[ContinentListResponse]</a></code>

## Countries

Types:

```python
from sportmonks.types.core import (
    CountryRetrieveResponse,
    CountryListResponse,
    CountrySearchResponse,
)
```

Methods:

- <code title="get /{version}/core/countries/{countryId}">client.core.countries.<a href="./src/sportmonks/resources/core/countries.py">retrieve</a>(country_id, \*, version) -> <a href="./src/sportmonks/types/core/country_retrieve_response.py">CountryRetrieveResponse</a></code>
- <code title="get /{version}/core/countries">client.core.countries.<a href="./src/sportmonks/resources/core/countries.py">list</a>(version, \*\*<a href="src/sportmonks/types/core/country_list_params.py">params</a>) -> <a href="./src/sportmonks/types/core/country_list_response.py">SyncPaginatedAPICall[CountryListResponse]</a></code>
- <code title="get /{version}/core/countries/search/{name}">client.core.countries.<a href="./src/sportmonks/resources/core/countries.py">search</a>(name, \*, version) -> <a href="./src/sportmonks/types/core/country_search_response.py">CountrySearchResponse</a></code>

## Regions

Types:

```python
from sportmonks.types.core import RegionRetrieveResponse, RegionListResponse, RegionSearchResponse
```

Methods:

- <code title="get /{version}/core/regions/{regionId}">client.core.regions.<a href="./src/sportmonks/resources/core/regions.py">retrieve</a>(region_id, \*, version) -> <a href="./src/sportmonks/types/core/region_retrieve_response.py">RegionRetrieveResponse</a></code>
- <code title="get /{version}/core/regions">client.core.regions.<a href="./src/sportmonks/resources/core/regions.py">list</a>(version, \*\*<a href="src/sportmonks/types/core/region_list_params.py">params</a>) -> <a href="./src/sportmonks/types/core/region_list_response.py">SyncPaginatedAPICall[RegionListResponse]</a></code>
- <code title="get /{version}/core/regions/search/{name}">client.core.regions.<a href="./src/sportmonks/resources/core/regions.py">search</a>(name, \*, version) -> <a href="./src/sportmonks/types/core/region_search_response.py">RegionSearchResponse</a></code>

## Types

Types:

```python
from sportmonks.types.core import TypeRetrieveResponse, TypeListResponse
```

Methods:

- <code title="get /{version}/core/types/{typeId}">client.core.types.<a href="./src/sportmonks/resources/core/types.py">retrieve</a>(type_id, \*, version) -> <a href="./src/sportmonks/types/core/type_retrieve_response.py">TypeRetrieveResponse</a></code>
- <code title="get /{version}/core/types">client.core.types.<a href="./src/sportmonks/resources/core/types.py">list</a>(version, \*\*<a href="src/sportmonks/types/core/type_list_params.py">params</a>) -> <a href="./src/sportmonks/types/core/type_list_response.py">SyncPaginatedAPICall[TypeListResponse]</a></code>

## Timezones

Types:

```python
from sportmonks.types.core import TimezoneListResponse
```

Methods:

- <code title="get /{version}/core/timezones">client.core.timezones.<a href="./src/sportmonks/resources/core/timezones.py">list</a>(version, \*\*<a href="src/sportmonks/types/core/timezone_list_params.py">params</a>) -> <a href="./src/sportmonks/types/core/timezone_list_response.py">SyncPaginatedAPICall[TimezoneListResponse]</a></code>
