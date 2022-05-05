[![codecov](https://codecov.io/gh/withertech/steam-scraper-client/branch/master/graph/badge.svg?token=8HP7FHVMCS)](https://codecov.io/gh/withertech/steam-scraper-client)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/withertech/steam-scraper-client)

# steam-scraper-client

To install:

```bash
npm install steam-scraper-client
```

or

```bash
yarn add steam-scraper-client
```

To use:

```typescript
import { ScrapeApi } from 'steam-scraper-client'

const api = new ScrapeApi();
api.scrape("filename", "md5").then((result) => {
	...
})
```
