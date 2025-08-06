# ImageRestoreImageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Restore** | Pointer to [**ImageRestore**](ImageRestore.md) |  | [optional] 
**Error** | Pointer to [**ImageRestoreImageResponseError**](ImageRestoreImageResponseError.md) |  | [optional] 

## Methods

### NewImageRestoreImageResponse

`func NewImageRestoreImageResponse() *ImageRestoreImageResponse`

NewImageRestoreImageResponse instantiates a new ImageRestoreImageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageRestoreImageResponseWithDefaults

`func NewImageRestoreImageResponseWithDefaults() *ImageRestoreImageResponse`

NewImageRestoreImageResponseWithDefaults instantiates a new ImageRestoreImageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRestore

`func (o *ImageRestoreImageResponse) GetRestore() ImageRestore`

GetRestore returns the Restore field if non-nil, zero value otherwise.

### GetRestoreOk

`func (o *ImageRestoreImageResponse) GetRestoreOk() (*ImageRestore, bool)`

GetRestoreOk returns a tuple with the Restore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestore

`func (o *ImageRestoreImageResponse) SetRestore(v ImageRestore)`

SetRestore sets Restore field to given value.

### HasRestore

`func (o *ImageRestoreImageResponse) HasRestore() bool`

HasRestore returns a boolean if a field has been set.

### GetError

`func (o *ImageRestoreImageResponse) GetError() ImageRestoreImageResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImageRestoreImageResponse) GetErrorOk() (*ImageRestoreImageResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImageRestoreImageResponse) SetError(v ImageRestoreImageResponseError)`

SetError sets Error field to given value.

### HasError

`func (o *ImageRestoreImageResponse) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


