# Swagger\Client\DefaultApi

All URIs are relative to *https://dev-api.chorck.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**organisationCapabilityDelete**](DefaultApi.md#organisationCapabilityDelete) | **DELETE** /organisation/capability | 
[**organisationCapabilityGet**](DefaultApi.md#organisationCapabilityGet) | **GET** /organisation/capability | 
[**organisationCapabilityPut**](DefaultApi.md#organisationCapabilityPut) | **PUT** /organisation/capability | 
[**organisationGet**](DefaultApi.md#organisationGet) | **GET** /organisation | 
[**organisationStaffDelete**](DefaultApi.md#organisationStaffDelete) | **DELETE** /organisation/staff | 
[**organisationStaffGet**](DefaultApi.md#organisationStaffGet) | **GET** /organisation/staff | 
[**organisationStaffPut**](DefaultApi.md#organisationStaffPut) | **PUT** /organisation/staff | 
[**rootGet**](DefaultApi.md#rootGet) | **GET** / | 


# **organisationCapabilityDelete**
> \Swagger\Client\Model\ModelEmpty organisationCapabilityDelete($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->organisationCapabilityDelete($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationCapabilityDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationCapabilityGet**
> \Swagger\Client\Model\ModelEmpty organisationCapabilityGet($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->organisationCapabilityGet($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationCapabilityGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationCapabilityPut**
> \Swagger\Client\Model\AddCapabilityResponse organisationCapabilityPut($secret, $x_api_key, $add_capability)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 
$add_capability = new \Swagger\Client\Model\AddCapability(); // \Swagger\Client\Model\AddCapability | 

try {
    $result = $api_instance->organisationCapabilityPut($secret, $x_api_key, $add_capability);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationCapabilityPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |
 **add_capability** | [**\Swagger\Client\Model\AddCapability**](../Model/AddCapability.md)|  |

### Return type

[**\Swagger\Client\Model\AddCapabilityResponse**](../Model/AddCapabilityResponse.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationGet**
> \Swagger\Client\Model\ModelEmpty organisationGet($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->organisationGet($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationStaffDelete**
> \Swagger\Client\Model\ModelEmpty organisationStaffDelete($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->organisationStaffDelete($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationStaffDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationStaffGet**
> \Swagger\Client\Model\ModelEmpty organisationStaffGet($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->organisationStaffGet($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationStaffGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **organisationStaffPut**
> \Swagger\Client\Model\ModelEmpty organisationStaffPut($secret, $x_api_key, $invite_staff)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 
$invite_staff = new \Swagger\Client\Model\InviteStaff(); // \Swagger\Client\Model\InviteStaff | 

try {
    $result = $api_instance->organisationStaffPut($secret, $x_api_key, $invite_staff);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->organisationStaffPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |
 **invite_staff** | [**\Swagger\Client\Model\InviteStaff**](../Model/InviteStaff.md)|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootGet**
> \Swagger\Client\Model\ModelEmpty rootGet($secret, $x_api_key)



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure API key authorization: DevChorckAPIAuthorizor
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');
// Configure API key authorization: api_key
Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('x-api-key', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('x-api-key', 'Bearer');

$api_instance = new Swagger\Client\Api\DefaultApi();
$secret = "secret_example"; // string | 
$x_api_key = "x_api_key_example"; // string | 

try {
    $result = $api_instance->rootGet($secret, $x_api_key);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->rootGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **secret** | **string**|  |
 **x_api_key** | **string**|  |

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

[DevChorckAPIAuthorizor](../../README.md#DevChorckAPIAuthorizor), [api_key](../../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

