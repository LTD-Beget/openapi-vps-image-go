# ImageDeleteImageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Image** | Pointer to [**ImageImage**](ImageImage.md) |  | [optional] 
**Error** | Pointer to [**ImageDeleteImageResponseError**](ImageDeleteImageResponseError.md) |  | [optional] 

## Methods

### NewImageDeleteImageResponse

`func NewImageDeleteImageResponse() *ImageDeleteImageResponse`

NewImageDeleteImageResponse instantiates a new ImageDeleteImageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageDeleteImageResponseWithDefaults

`func NewImageDeleteImageResponseWithDefaults() *ImageDeleteImageResponse`

NewImageDeleteImageResponseWithDefaults instantiates a new ImageDeleteImageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImage

`func (o *ImageDeleteImageResponse) GetImage() ImageImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ImageDeleteImageResponse) GetImageOk() (*ImageImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ImageDeleteImageResponse) SetImage(v ImageImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ImageDeleteImageResponse) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetError

`func (o *ImageDeleteImageResponse) GetError() ImageDeleteImageResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImageDeleteImageResponse) GetErrorOk() (*ImageDeleteImageResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImageDeleteImageResponse) SetError(v ImageDeleteImageResponseError)`

SetError sets Error field to given value.

### HasError

`func (o *ImageDeleteImageResponse) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


