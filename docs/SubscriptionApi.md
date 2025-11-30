# SubscriptionApi

All URIs are relative to *http://localhost*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**appleNotifications**](#applenotifications) | **POST** /api/app/subscription/apple-notifications | 苹果订阅 Callback 地址|
|[**createOrder**](#createorder) | **POST** /api/app/subscription/order | |
|[**getSubscriptionById**](#getsubscriptionbyid) | **GET** /api/app/subscription | |
|[**verifyReceipt**](#verifyreceipt) | **POST** /api/app/subscription/verify-receipt | |

# **appleNotifications**
> appleNotifications()


### Example

```typescript
import {
    SubscriptionApi,
    Configuration,
    AppleNotificaionDto
} from 'puupee-api-axios';

const configuration = new Configuration();
const apiInstance = new SubscriptionApi(configuration);

let appleNotificaionDto: AppleNotificaionDto; // (optional)

const { status, data } = await apiInstance.appleNotifications(
    appleNotificaionDto
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **appleNotificaionDto** | **AppleNotificaionDto**|  | |


### Return type

void (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/*+json
 - **Accept**: text/plain, application/json, text/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Success |  -  |
|**403** | Forbidden |  -  |
|**401** | Unauthorized |  -  |
|**400** | Bad Request |  -  |
|**404** | Not Found |  -  |
|**501** | Server Error |  -  |
|**500** | Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createOrder**
> SubscriptionOrderDto createOrder()


### Example

```typescript
import {
    SubscriptionApi,
    Configuration,
    CreateOrGetSubscriptionOrderDto
} from 'puupee-api-axios';

const configuration = new Configuration();
const apiInstance = new SubscriptionApi(configuration);

let createOrGetSubscriptionOrderDto: CreateOrGetSubscriptionOrderDto; // (optional)

const { status, data } = await apiInstance.createOrder(
    createOrGetSubscriptionOrderDto
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createOrGetSubscriptionOrderDto** | **CreateOrGetSubscriptionOrderDto**|  | |


### Return type

**SubscriptionOrderDto**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/*+json
 - **Accept**: text/plain, application/json, text/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Success |  -  |
|**403** | Forbidden |  -  |
|**401** | Unauthorized |  -  |
|**400** | Bad Request |  -  |
|**404** | Not Found |  -  |
|**501** | Server Error |  -  |
|**500** | Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSubscriptionById**
> SubscriptionDto getSubscriptionById()


### Example

```typescript
import {
    SubscriptionApi,
    Configuration
} from 'puupee-api-axios';

const configuration = new Configuration();
const apiInstance = new SubscriptionApi(configuration);

let appId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSubscriptionById(
    appId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **appId** | [**string**] |  | (optional) defaults to undefined|


### Return type

**SubscriptionDto**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain, application/json, text/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Success |  -  |
|**403** | Forbidden |  -  |
|**401** | Unauthorized |  -  |
|**400** | Bad Request |  -  |
|**404** | Not Found |  -  |
|**501** | Server Error |  -  |
|**500** | Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verifyReceipt**
> VerifyReceiptResult verifyReceipt()


### Example

```typescript
import {
    SubscriptionApi,
    Configuration,
    VerifyReceiptDto
} from 'puupee-api-axios';

const configuration = new Configuration();
const apiInstance = new SubscriptionApi(configuration);

let verifyReceiptDto: VerifyReceiptDto; // (optional)

const { status, data } = await apiInstance.verifyReceipt(
    verifyReceiptDto
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **verifyReceiptDto** | **VerifyReceiptDto**|  | |


### Return type

**VerifyReceiptResult**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/*+json
 - **Accept**: text/plain, application/json, text/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Success |  -  |
|**403** | Forbidden |  -  |
|**401** | Unauthorized |  -  |
|**400** | Bad Request |  -  |
|**404** | Not Found |  -  |
|**501** | Server Error |  -  |
|**500** | Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

