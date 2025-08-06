# ImageCreateImageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | Pointer to [**ImageImageSource**](ImageImageSource.md) |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Region** | Pointer to **string** |  | [optional] 

## Methods

### NewImageCreateImageRequest

`func NewImageCreateImageRequest() *ImageCreateImageRequest`

NewImageCreateImageRequest instantiates a new ImageCreateImageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageCreateImageRequestWithDefaults

`func NewImageCreateImageRequestWithDefaults() *ImageCreateImageRequest`

NewImageCreateImageRequestWithDefaults instantiates a new ImageCreateImageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *ImageCreateImageRequest) GetSource() ImageImageSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ImageCreateImageRequest) GetSourceOk() (*ImageImageSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ImageCreateImageRequest) SetSource(v ImageImageSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *ImageCreateImageRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetName

`func (o *ImageCreateImageRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImageCreateImageRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImageCreateImageRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ImageCreateImageRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRegion

`func (o *ImageCreateImageRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *ImageCreateImageRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *ImageCreateImageRequest) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *ImageCreateImageRequest) HasRegion() bool`

HasRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


