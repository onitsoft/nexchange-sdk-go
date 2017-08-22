# \DefaultApi

All URIs are relative to *https://nexchange.co.uk*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EnApiV1CurrencyGet**](DefaultApi.md#EnApiV1CurrencyGet) | **Get** /en/api/v1/currency/ | Get Currencies
[**EnApiV1OrdersGet**](DefaultApi.md#EnApiV1OrdersGet) | **Get** /en/api/v1/orders/ | Get Orders
[**EnApiV1OrdersPost**](DefaultApi.md#EnApiV1OrdersPost) | **Post** /en/api/v1/orders/ | Create Anonymous Order
[**EnApiV1OrdersUniqueReferenceGet**](DefaultApi.md#EnApiV1OrdersUniqueReferenceGet) | **Get** /en/api/v1/orders/{unique_reference}/ | Get Order
[**EnApiV1PairGet**](DefaultApi.md#EnApiV1PairGet) | **Get** /en/api/v1/pair/ | Get Pairs
[**EnApiV1PricePairNameHistoryGet**](DefaultApi.md#EnApiV1PricePairNameHistoryGet) | **Get** /en/api/v1/price/{pair_name}/history/ | Get Ticker History
[**EnApiV1PricePairNameLatestGet**](DefaultApi.md#EnApiV1PricePairNameLatestGet) | **Get** /en/api/v1/price/{pair_name}/latest/ | Get Latest Ticker
[**EnApiV1UsersMeOrdersGet**](DefaultApi.md#EnApiV1UsersMeOrdersGet) | **Get** /en/api/v1/users/me/orders/ | Get User Orders
[**EnApiV1UsersMeOrdersPost**](DefaultApi.md#EnApiV1UsersMeOrdersPost) | **Post** /en/api/v1/users/me/orders/ | Create User Order
[**EnApiV1UsersMeOrdersUniqueReferenceGet**](DefaultApi.md#EnApiV1UsersMeOrdersUniqueReferenceGet) | **Get** /en/api/v1/users/me/orders/{unique_reference}/ | Get User Order


# **EnApiV1CurrencyGet**
> EnApiV1CurrencyGet()
Get Currencies

Get pairs.

### Required Parameters
This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1OrdersGet**
> EnApiV1OrdersGet(page, pageSize)
Get Orders

Gets list of orders.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **page** | **string**|  | 
  **pageSize** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1OrdersPost**
> EnApiV1OrdersPost()
Create Anonymous Order

Create order.

### Required Parameters
This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1OrdersUniqueReferenceGet**
> EnApiV1OrdersUniqueReferenceGet(uniqueReference)
Get Order

Get order data.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **uniqueReference** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1PairGet**
> EnApiV1PairGet()
Get Pairs

Get pairs.

### Required Parameters
This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1PricePairNameHistoryGet**
> EnApiV1PricePairNameHistoryGet(pairName, hours, dataPoints)
Get Ticker History

Gets latests price of selected pair.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **pairName** | **string**|  | 
  **hours** | **string**|  | 
  **dataPoints** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1PricePairNameLatestGet**
> EnApiV1PricePairNameLatestGet(pairName)
Get Latest Ticker

Gets latests price of selected pair.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **pairName** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1UsersMeOrdersGet**
> EnApiV1UsersMeOrdersGet(page, pageSize)
Get User Orders

Get user orders.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **page** | **string**|  | 
  **pageSize** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1UsersMeOrdersPost**
> EnApiV1UsersMeOrdersPost()
Create User Order

Create order.

### Required Parameters
This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **EnApiV1UsersMeOrdersUniqueReferenceGet**
> EnApiV1UsersMeOrdersUniqueReferenceGet(uniqueReference)
Get User Order

Get user order.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
  **uniqueReference** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

