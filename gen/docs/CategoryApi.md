# CofeGb.CategoryApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**categoriesGet**](CategoryApi.md#categoriesGet) | **GET** /categories | 



## categoriesGet

> [Category] categoriesGet()



Returns dish menu entries

### Example

```javascript
import CofeGb from 'cofe_gb';

let apiInstance = new CofeGb.CategoryApi();
apiInstance.categoriesGet((error, data, response) => {
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

[**[Category]**](Category.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

