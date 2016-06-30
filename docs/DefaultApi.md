# \DefaultApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProjectsGet**](DefaultApi.md#ProjectsGet) | **Get** /projects | 
[**SamplesGet**](DefaultApi.md#SamplesGet) | **Get** /samples | 
[**UsersGet**](DefaultApi.md#UsersGet) | **Get** /users | 


# **ProjectsGet**
> []Project ProjectsGet($fields, $tax, $order, $zip, $envelope, $pretty)



Gets `Project` objects. Optional query param **fields** determines which fields to return


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fields** | **string**| Fields to return | [optional] 
 **tax** | **string**| Taxonomy tags to include | [optional] 
 **order** | **string**| Fields to order by | [optional] 
 **zip** | **bool**| Use gzip compression on response | [optional] 
 **envelope** | **bool**| Use envelope on response | [optional] 
 **pretty** | **bool**| Use pretty print on response | [optional] 

### Return type

[**[]Project**](Project.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **SamplesGet**
> []Sample SamplesGet($fields, $tax, $tokens, $order, $zip, $envelope, $pretty)



Gets `Sample` objects. Optional query param **fields** determines which fields to return


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fields** | **string**| Fields to return | [optional] 
 **tax** | **string**| Taxonomy tags to include | [optional] 
 **tokens** | **string**| Tokens for full text search | [optional] 
 **order** | **string**| Fields to order by | [optional] 
 **zip** | **bool**| Use gzip compression on response | [optional] 
 **envelope** | **bool**| Use envelope on response | [optional] 
 **pretty** | **bool**| Use pretty print on response | [optional] 

### Return type

[**[]Sample**](Sample.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UsersGet**
> []User UsersGet($fields, $order, $zip, $envelope, $pretty)



Gets `User` objects. Optional query param **fields** determines which fields to return


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fields** | **string**| Fields to return | [optional] 
 **order** | **string**| Fields to order by | [optional] 
 **zip** | **bool**| Use gzip compression on response | [optional] 
 **envelope** | **bool**| Use envelope on response | [optional] 
 **pretty** | **bool**| Use pretty print on response | [optional] 

### Return type

[**[]User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

