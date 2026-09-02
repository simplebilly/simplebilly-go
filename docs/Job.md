# Job

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attempts** | Pointer to **int32** |  | [optional] 
**JobType** | **string** | Discriminator the worker dispatches on (e.g. \&quot;webhook.deliver\&quot;). | 
**MaxAttempts** | **int32** |  | 
**Payload** | Pointer to **interface{}** |  | [optional] 
**RunAt** | Pointer to **NullableTime** | Earliest execution time; None &#x3D; run now. | [optional] 
**Status** | [**JobStatus**](JobStatus.md) | pending | running | done | failed | 

## Methods

### NewJob

`func NewJob(jobType string, maxAttempts int32, status JobStatus, ) *Job`

NewJob instantiates a new Job object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobWithDefaults

`func NewJobWithDefaults() *Job`

NewJobWithDefaults instantiates a new Job object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttempts

`func (o *Job) GetAttempts() int32`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *Job) GetAttemptsOk() (*int32, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *Job) SetAttempts(v int32)`

SetAttempts sets Attempts field to given value.

### HasAttempts

`func (o *Job) HasAttempts() bool`

HasAttempts returns a boolean if a field has been set.

### GetJobType

`func (o *Job) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *Job) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *Job) SetJobType(v string)`

SetJobType sets JobType field to given value.


### GetMaxAttempts

`func (o *Job) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *Job) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *Job) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetPayload

`func (o *Job) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *Job) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *Job) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *Job) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *Job) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *Job) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetRunAt

`func (o *Job) GetRunAt() time.Time`

GetRunAt returns the RunAt field if non-nil, zero value otherwise.

### GetRunAtOk

`func (o *Job) GetRunAtOk() (*time.Time, bool)`

GetRunAtOk returns a tuple with the RunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAt

`func (o *Job) SetRunAt(v time.Time)`

SetRunAt sets RunAt field to given value.

### HasRunAt

`func (o *Job) HasRunAt() bool`

HasRunAt returns a boolean if a field has been set.

### SetRunAtNil

`func (o *Job) SetRunAtNil(b bool)`

 SetRunAtNil sets the value for RunAt to be an explicit nil

### UnsetRunAt
`func (o *Job) UnsetRunAt()`

UnsetRunAt ensures that no value is present for RunAt, not even an explicit nil
### GetStatus

`func (o *Job) GetStatus() JobStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Job) GetStatusOk() (*JobStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Job) SetStatus(v JobStatus)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


