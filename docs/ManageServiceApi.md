# \ManageServiceApi

All URIs are relative to *https://api.beget.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ManageServiceCreateImage**](ManageServiceApi.md#ManageServiceCreateImage) | **Post** /v1/image | 
[**ManageServiceDeleteImage**](ManageServiceApi.md#ManageServiceDeleteImage) | **Delete** /v1/image/{id} | 
[**ManageServiceGetCalculation**](ManageServiceApi.md#ManageServiceGetCalculation) | **Get** /v1/image/calculation | 
[**ManageServiceGetDownloadLink**](ManageServiceApi.md#ManageServiceGetDownloadLink) | **Get** /v1/image/{id}/link | 
[**ManageServiceGetList**](ManageServiceApi.md#ManageServiceGetList) | **Get** /v1/image | 
[**ManageServiceGetRegionList**](ManageServiceApi.md#ManageServiceGetRegionList) | **Get** /v1/image/region | 
[**ManageServiceRestoreImage**](ManageServiceApi.md#ManageServiceRestoreImage) | **Post** /v1/image/{id}/restore | 
[**ManageServiceUpdateImage**](ManageServiceApi.md#ManageServiceUpdateImage) | **Put** /v1/image/{id} | 



## ManageServiceCreateImage

> ImageCreateImageResponse ManageServiceCreateImage(ctx).ImageCreateImageRequest(imageCreateImageRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    imageCreateImageRequest := *openapiclient.NewImageCreateImageRequest() // ImageCreateImageRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceCreateImage(context.Background()).ImageCreateImageRequest(imageCreateImageRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceCreateImage``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceCreateImage`: ImageCreateImageResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceCreateImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceCreateImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imageCreateImageRequest** | [**ImageCreateImageRequest**](ImageCreateImageRequest.md) |  | 

### Return type

[**ImageCreateImageResponse**](ImageCreateImageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceDeleteImage

> ImageDeleteImageResponse ManageServiceDeleteImage(ctx, id).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    id := "id_example" // string | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceDeleteImage(context.Background(), id).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceDeleteImage``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceDeleteImage`: ImageDeleteImageResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceDeleteImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceDeleteImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageDeleteImageResponse**](ImageDeleteImageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceGetCalculation

> ImageGetCalculationResponse ManageServiceGetCalculation(ctx).FileSize(fileSize).Link(link).VpsId(vpsId).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    fileSize := "fileSize_example" // string |  (optional)
    link := "link_example" // string |  (optional)
    vpsId := "vpsId_example" // string |  (optional)

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceGetCalculation(context.Background()).FileSize(fileSize).Link(link).VpsId(vpsId).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceGetCalculation``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceGetCalculation`: ImageGetCalculationResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceGetCalculation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceGetCalculationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fileSize** | **string** |  | 
 **link** | **string** |  | 
 **vpsId** | **string** |  | 

### Return type

[**ImageGetCalculationResponse**](ImageGetCalculationResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceGetDownloadLink

> ImageGetDownloadLinkResponse ManageServiceGetDownloadLink(ctx, id).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    id := "id_example" // string | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceGetDownloadLink(context.Background(), id).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceGetDownloadLink``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceGetDownloadLink`: ImageGetDownloadLinkResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceGetDownloadLink`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceGetDownloadLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageGetDownloadLinkResponse**](ImageGetDownloadLinkResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceGetList

> ImageGetListResponse ManageServiceGetList(ctx).Offset(offset).Limit(limit).Filter(filter).Sort(sort).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    offset := int32(56) // int32 |  (optional)
    limit := int32(56) // int32 |  (optional)
    filter := "filter_example" // string |  (optional)
    sort := "sort_example" // string |  (optional)

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceGetList(context.Background()).Offset(offset).Limit(limit).Filter(filter).Sort(sort).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceGetList``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceGetList`: ImageGetListResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceGetList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceGetListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** |  | 
 **limit** | **int32** |  | 
 **filter** | **string** |  | 
 **sort** | **string** |  | 

### Return type

[**ImageGetListResponse**](ImageGetListResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceGetRegionList

> ImageGetRegionListResponse ManageServiceGetRegionList(ctx).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceGetRegionList(context.Background()).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceGetRegionList``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceGetRegionList`: ImageGetRegionListResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceGetRegionList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceGetRegionListRequest struct via the builder pattern


### Return type

[**ImageGetRegionListResponse**](ImageGetRegionListResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceRestoreImage

> ImageRestoreImageResponse ManageServiceRestoreImage(ctx, id).ImageRestoreImageRequest(imageRestoreImageRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    id := "id_example" // string | 
    imageRestoreImageRequest := *openapiclient.NewImageRestoreImageRequest() // ImageRestoreImageRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceRestoreImage(context.Background(), id).ImageRestoreImageRequest(imageRestoreImageRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceRestoreImage``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceRestoreImage`: ImageRestoreImageResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceRestoreImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceRestoreImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageRestoreImageRequest** | [**ImageRestoreImageRequest**](ImageRestoreImageRequest.md) |  | 

### Return type

[**ImageRestoreImageResponse**](ImageRestoreImageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageServiceUpdateImage

> ImageUpdateImageResponse ManageServiceUpdateImage(ctx, id).ImageUpdateImageRequest(imageUpdateImageRequest).Execute()



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "github.com/LTD-Beget/openapi-vps-image-go"
)

func main() {
    id := "id_example" // string | 
    imageUpdateImageRequest := *openapiclient.NewImageUpdateImageRequest() // ImageUpdateImageRequest | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ManageServiceApi.ManageServiceUpdateImage(context.Background(), id).ImageUpdateImageRequest(imageUpdateImageRequest).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ManageServiceApi.ManageServiceUpdateImage``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `ManageServiceUpdateImage`: ImageUpdateImageResponse
    fmt.Fprintf(os.Stdout, "Response from `ManageServiceApi.ManageServiceUpdateImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManageServiceUpdateImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageUpdateImageRequest** | [**ImageUpdateImageRequest**](ImageUpdateImageRequest.md) |  | 

### Return type

[**ImageUpdateImageResponse**](ImageUpdateImageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

