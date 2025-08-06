# ImageGetListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Images** | Pointer to [**[]ImageImage**](ImageImage.md) |  | [optional] 

## Methods

### NewImageGetListResponse

`func NewImageGetListResponse() *ImageGetListResponse`

NewImageGetListResponse instantiates a new ImageGetListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGetListResponseWithDefaults

`func NewImageGetListResponseWithDefaults() *ImageGetListResponse`

NewImageGetListResponseWithDefaults instantiates a new ImageGetListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImages

`func (o *ImageGetListResponse) GetImages() []ImageImage`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ImageGetListResponse) GetImagesOk() (*[]ImageImage, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ImageGetListResponse) SetImages(v []ImageImage)`

SetImages sets Images field to given value.

### HasImages

`func (o *ImageGetListResponse) HasImages() bool`

HasImages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


