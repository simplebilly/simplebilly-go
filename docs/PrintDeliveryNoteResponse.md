# PrintDeliveryNoteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**PdfUrl** | Pointer to **NullableString** |  | [optional] 
**Success** | **bool** |  | 

## Methods

### NewPrintDeliveryNoteResponse

`func NewPrintDeliveryNoteResponse(message string, success bool, ) *PrintDeliveryNoteResponse`

NewPrintDeliveryNoteResponse instantiates a new PrintDeliveryNoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrintDeliveryNoteResponseWithDefaults

`func NewPrintDeliveryNoteResponseWithDefaults() *PrintDeliveryNoteResponse`

NewPrintDeliveryNoteResponseWithDefaults instantiates a new PrintDeliveryNoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *PrintDeliveryNoteResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PrintDeliveryNoteResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PrintDeliveryNoteResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetPdfUrl

`func (o *PrintDeliveryNoteResponse) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *PrintDeliveryNoteResponse) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *PrintDeliveryNoteResponse) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.

### HasPdfUrl

`func (o *PrintDeliveryNoteResponse) HasPdfUrl() bool`

HasPdfUrl returns a boolean if a field has been set.

### SetPdfUrlNil

`func (o *PrintDeliveryNoteResponse) SetPdfUrlNil(b bool)`

 SetPdfUrlNil sets the value for PdfUrl to be an explicit nil

### UnsetPdfUrl
`func (o *PrintDeliveryNoteResponse) UnsetPdfUrl()`

UnsetPdfUrl ensures that no value is present for PdfUrl, not even an explicit nil
### GetSuccess

`func (o *PrintDeliveryNoteResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PrintDeliveryNoteResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PrintDeliveryNoteResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


