# ApiResponseGdprExport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**ApiResponseGdprExportData**](ApiResponseGdprExportData.md) |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewApiResponseGdprExport

`func NewApiResponseGdprExport(success bool, ) *ApiResponseGdprExport`

NewApiResponseGdprExport instantiates a new ApiResponseGdprExport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseGdprExportWithDefaults

`func NewApiResponseGdprExportWithDefaults() *ApiResponseGdprExport`

NewApiResponseGdprExportWithDefaults instantiates a new ApiResponseGdprExport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ApiResponseGdprExport) GetData() ApiResponseGdprExportData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ApiResponseGdprExport) GetDataOk() (*ApiResponseGdprExportData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ApiResponseGdprExport) SetData(v ApiResponseGdprExportData)`

SetData sets Data field to given value.

### HasData

`func (o *ApiResponseGdprExport) HasData() bool`

HasData returns a boolean if a field has been set.

### GetError

`func (o *ApiResponseGdprExport) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiResponseGdprExport) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiResponseGdprExport) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ApiResponseGdprExport) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ApiResponseGdprExport) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ApiResponseGdprExport) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetMessage

`func (o *ApiResponseGdprExport) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ApiResponseGdprExport) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ApiResponseGdprExport) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ApiResponseGdprExport) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *ApiResponseGdprExport) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *ApiResponseGdprExport) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetSuccess

`func (o *ApiResponseGdprExport) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ApiResponseGdprExport) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ApiResponseGdprExport) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


