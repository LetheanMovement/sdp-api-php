# OpenAPI\Client\VpnApi

All URIs are relative to http://localhost.

Method | HTTP request | Description
------------- | ------------- | -------------
[**startLetheand()**](VpnApi.md#startLetheand) | **GET** /letheand/start | 


## `startLetheand()`

```php
startLetheand($data_dir, $version)
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\VpnApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$data_dir = 'data_dir_example'; // string | Returns the binary version
$version = True; // bool | Returns the binary version

try {
    $apiInstance->startLetheand($data_dir, $version);
} catch (Exception $e) {
    echo 'Exception when calling VpnApi->startLetheand: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **data_dir** | **string**| Returns the binary version |
 **version** | **bool**| Returns the binary version | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
