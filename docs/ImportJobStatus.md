# ImportJobStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **NullableString** | Set only when the job failed. | [optional] 
**JobId** | **string** |  | 
**Processed** | **int64** |  | 
**Progress** | **int32** | 0–100 | 
**Provider** | Pointer to **NullableString** | Which competitor the import came from (lexoffice | billbee); the frontend uses it to label the job. Absent for legacy jobs. | [optional] 
**Stage** | **string** | queued | fetching | downloading | importing | done | 
**Status** | **string** | pending | running | done | failed | 
**Total** | **int64** |  | 

## Methods

### NewImportJobStatus

`func NewImportJobStatus(jobId string, processed int64, progress int32, stage string, status string, total int64, ) *ImportJobStatus`

NewImportJobStatus instantiates a new ImportJobStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportJobStatusWithDefaults

`func NewImportJobStatusWithDefaults() *ImportJobStatus`

NewImportJobStatusWithDefaults instantiates a new ImportJobStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ImportJobStatus) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImportJobStatus) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImportJobStatus) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ImportJobStatus) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ImportJobStatus) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ImportJobStatus) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetJobId

`func (o *ImportJobStatus) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *ImportJobStatus) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *ImportJobStatus) SetJobId(v string)`

SetJobId sets JobId field to given value.


### GetProcessed

`func (o *ImportJobStatus) GetProcessed() int64`

GetProcessed returns the Processed field if non-nil, zero value otherwise.

### GetProcessedOk

`func (o *ImportJobStatus) GetProcessedOk() (*int64, bool)`

GetProcessedOk returns a tuple with the Processed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessed

`func (o *ImportJobStatus) SetProcessed(v int64)`

SetProcessed sets Processed field to given value.


### GetProgress

`func (o *ImportJobStatus) GetProgress() int32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *ImportJobStatus) GetProgressOk() (*int32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *ImportJobStatus) SetProgress(v int32)`

SetProgress sets Progress field to given value.


### GetProvider

`func (o *ImportJobStatus) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ImportJobStatus) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ImportJobStatus) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ImportJobStatus) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ImportJobStatus) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ImportJobStatus) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetStage

`func (o *ImportJobStatus) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *ImportJobStatus) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *ImportJobStatus) SetStage(v string)`

SetStage sets Stage field to given value.


### GetStatus

`func (o *ImportJobStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ImportJobStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ImportJobStatus) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTotal

`func (o *ImportJobStatus) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ImportJobStatus) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ImportJobStatus) SetTotal(v int64)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


