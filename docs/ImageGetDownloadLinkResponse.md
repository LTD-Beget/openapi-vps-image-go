# ImageGetDownloadLinkResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DownloadLinkInfo** | Pointer to [**ImageDownloadLinkInfo**](ImageDownloadLinkInfo.md) |  | [optional] 
**Error** | Pointer to [**ImageGetDownloadLinkResponseError**](ImageGetDownloadLinkResponseError.md) |  | [optional] 

## Methods

### NewImageGetDownloadLinkResponse

`func NewImageGetDownloadLinkResponse() *ImageGetDownloadLinkResponse`

NewImageGetDownloadLinkResponse instantiates a new ImageGetDownloadLinkResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGetDownloadLinkResponseWithDefaults

`func NewImageGetDownloadLinkResponseWithDefaults() *ImageGetDownloadLinkResponse`

NewImageGetDownloadLinkResponseWithDefaults instantiates a new ImageGetDownloadLinkResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDownloadLinkInfo

`func (o *ImageGetDownloadLinkResponse) GetDownloadLinkInfo() ImageDownloadLinkInfo`

GetDownloadLinkInfo returns the DownloadLinkInfo field if non-nil, zero value otherwise.

### GetDownloadLinkInfoOk

`func (o *ImageGetDownloadLinkResponse) GetDownloadLinkInfoOk() (*ImageDownloadLinkInfo, bool)`

GetDownloadLinkInfoOk returns a tuple with the DownloadLinkInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadLinkInfo

`func (o *ImageGetDownloadLinkResponse) SetDownloadLinkInfo(v ImageDownloadLinkInfo)`

SetDownloadLinkInfo sets DownloadLinkInfo field to given value.

### HasDownloadLinkInfo

`func (o *ImageGetDownloadLinkResponse) HasDownloadLinkInfo() bool`

HasDownloadLinkInfo returns a boolean if a field has been set.

### GetError

`func (o *ImageGetDownloadLinkResponse) GetError() ImageGetDownloadLinkResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImageGetDownloadLinkResponse) GetErrorOk() (*ImageGetDownloadLinkResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImageGetDownloadLinkResponse) SetError(v ImageGetDownloadLinkResponseError)`

SetError sets Error field to given value.

### HasError

`func (o *ImageGetDownloadLinkResponse) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


