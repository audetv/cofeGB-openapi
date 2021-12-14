# CofeGb.MenuApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**navMenuGet**](MenuApi.md#navMenuGet) | **GET** /navMenu | 



## navMenuGet

> [NavMenuItem] navMenuGet()



Return app navigation menu entries

### Example

```javascript
import CofeGb from 'cofe_gb';

let apiInstance = new CofeGb.MenuApi();
apiInstance.navMenuGet((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**[NavMenuItem]**](NavMenuItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

