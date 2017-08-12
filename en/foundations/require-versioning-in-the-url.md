#### Require Versioning in the URL

There are mixed opinions around whether an API version should be included in the
URL or in a header. Academically speaking, it should probably be in a header.
However, including the version URL ensures browser explorability of the resources
across versions and is simpler to work with (remember our need for developer friendliness).


```
api.telnyx.com/v2/resource/{id}
```
