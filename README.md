# STEM Service unavailable page

This site provides a service unavaialble page, issueing a 503 response, to any request. It also returns a `Retry-After` header set to 900 seconds by default and a `noindex` header as well.

It is designed to be deployed to Netlify and uses `_redirects` and `_headers`. It could be moved to other platforms with changes to these two redirect/header setting mechanisms
