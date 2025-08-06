# ImageGetCalculationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PriceCalculationInfo** | Pointer to [**ImagePriceCalculationInfo**](ImagePriceCalculationInfo.md) |  | [optional] 
**Error** | Pointer to [**ImageGetCalculationResponseError**](ImageGetCalculationResponseError.md) |  | [optional] 

## Methods

### NewImageGetCalculationResponse

`func NewImageGetCalculationResponse() *ImageGetCalculationResponse`

NewImageGetCalculationResponse instantiates a new ImageGetCalculationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGetCalculationResponseWithDefaults

`func NewImageGetCalculationResponseWithDefaults() *ImageGetCalculationResponse`

NewImageGetCalculationResponseWithDefaults instantiates a new ImageGetCalculationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPriceCalculationInfo

`func (o *ImageGetCalculationResponse) GetPriceCalculationInfo() ImagePriceCalculationInfo`

GetPriceCalculationInfo returns the PriceCalculationInfo field if non-nil, zero value otherwise.

### GetPriceCalculationInfoOk

`func (o *ImageGetCalculationResponse) GetPriceCalculationInfoOk() (*ImagePriceCalculationInfo, bool)`

GetPriceCalculationInfoOk returns a tuple with the PriceCalculationInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceCalculationInfo

`func (o *ImageGetCalculationResponse) SetPriceCalculationInfo(v ImagePriceCalculationInfo)`

SetPriceCalculationInfo sets PriceCalculationInfo field to given value.

### HasPriceCalculationInfo

`func (o *ImageGetCalculationResponse) HasPriceCalculationInfo() bool`

HasPriceCalculationInfo returns a boolean if a field has been set.

### GetError

`func (o *ImageGetCalculationResponse) GetError() ImageGetCalculationResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImageGetCalculationResponse) GetErrorOk() (*ImageGetCalculationResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImageGetCalculationResponse) SetError(v ImageGetCalculationResponseError)`

SetError sets Error field to given value.

### HasError

`func (o *ImageGetCalculationResponse) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


