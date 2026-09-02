# DatevImportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Filename** | **string** |  | 
**Rows** | [**[]DatevImportRow**](DatevImportRow.md) |  | 

## Methods

### NewDatevImportResponse

`func NewDatevImportResponse(count int32, filename string, rows []DatevImportRow, ) *DatevImportResponse`

NewDatevImportResponse instantiates a new DatevImportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatevImportResponseWithDefaults

`func NewDatevImportResponseWithDefaults() *DatevImportResponse`

NewDatevImportResponseWithDefaults instantiates a new DatevImportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *DatevImportResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *DatevImportResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *DatevImportResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetFilename

`func (o *DatevImportResponse) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *DatevImportResponse) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *DatevImportResponse) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetRows

`func (o *DatevImportResponse) GetRows() []DatevImportRow`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *DatevImportResponse) GetRowsOk() (*[]DatevImportRow, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *DatevImportResponse) SetRows(v []DatevImportRow)`

SetRows sets Rows field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


