# UseFetch Hook

```
    import useFetch from 'path';

    const url = 'endpoint api';
    const { data, loading, error } = useFetch(url);
```
- useFetch(url)  // Recibe url, return promise.
- data   // Response del endpoint.
- loading  // State de la peticion( boolean )
- error   // Catch error.
