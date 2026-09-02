# AbsenceCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AbsenceType** | Pointer to [**AbsenceType**](AbsenceType.md) | One of \&quot;vacation\&quot;, \&quot;sick\&quot;, \&quot;sabbatical\&quot;, \&quot;parental\&quot;, \&quot;other\&quot;. | [optional] 
**ApprovedAt** | Pointer to **NullableTime** |  | [optional] 
**ApprovedBy** | Pointer to **NullableString** | References the user entity. | [optional] 
**EmployeeId** | Pointer to **string** | References the employee entity. | [optional] 
**EndDate** | Pointer to **string** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**StartDate** | Pointer to **string** |  | [optional] 
**Status** | Pointer to [**AbsenceStatus**](AbsenceStatus.md) | One of \&quot;pending\&quot;, \&quot;approved\&quot;, \&quot;rejected\&quot;, \&quot;cancelled\&quot;. | [optional] 

## Methods

### NewAbsenceCreate

`func NewAbsenceCreate() *AbsenceCreate`

NewAbsenceCreate instantiates a new AbsenceCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAbsenceCreateWithDefaults

`func NewAbsenceCreateWithDefaults() *AbsenceCreate`

NewAbsenceCreateWithDefaults instantiates a new AbsenceCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbsenceType

`func (o *AbsenceCreate) GetAbsenceType() AbsenceType`

GetAbsenceType returns the AbsenceType field if non-nil, zero value otherwise.

### GetAbsenceTypeOk

`func (o *AbsenceCreate) GetAbsenceTypeOk() (*AbsenceType, bool)`

GetAbsenceTypeOk returns a tuple with the AbsenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbsenceType

`func (o *AbsenceCreate) SetAbsenceType(v AbsenceType)`

SetAbsenceType sets AbsenceType field to given value.

### HasAbsenceType

`func (o *AbsenceCreate) HasAbsenceType() bool`

HasAbsenceType returns a boolean if a field has been set.

### GetApprovedAt

`func (o *AbsenceCreate) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *AbsenceCreate) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *AbsenceCreate) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *AbsenceCreate) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### SetApprovedAtNil

`func (o *AbsenceCreate) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *AbsenceCreate) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedBy

`func (o *AbsenceCreate) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *AbsenceCreate) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *AbsenceCreate) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *AbsenceCreate) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### SetApprovedByNil

`func (o *AbsenceCreate) SetApprovedByNil(b bool)`

 SetApprovedByNil sets the value for ApprovedBy to be an explicit nil

### UnsetApprovedBy
`func (o *AbsenceCreate) UnsetApprovedBy()`

UnsetApprovedBy ensures that no value is present for ApprovedBy, not even an explicit nil
### GetEmployeeId

`func (o *AbsenceCreate) GetEmployeeId() string`

GetEmployeeId returns the EmployeeId field if non-nil, zero value otherwise.

### GetEmployeeIdOk

`func (o *AbsenceCreate) GetEmployeeIdOk() (*string, bool)`

GetEmployeeIdOk returns a tuple with the EmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeId

`func (o *AbsenceCreate) SetEmployeeId(v string)`

SetEmployeeId sets EmployeeId field to given value.

### HasEmployeeId

`func (o *AbsenceCreate) HasEmployeeId() bool`

HasEmployeeId returns a boolean if a field has been set.

### GetEndDate

`func (o *AbsenceCreate) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *AbsenceCreate) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *AbsenceCreate) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *AbsenceCreate) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetNotes

`func (o *AbsenceCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *AbsenceCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *AbsenceCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *AbsenceCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *AbsenceCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *AbsenceCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetStartDate

`func (o *AbsenceCreate) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *AbsenceCreate) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *AbsenceCreate) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *AbsenceCreate) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetStatus

`func (o *AbsenceCreate) GetStatus() AbsenceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AbsenceCreate) GetStatusOk() (*AbsenceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AbsenceCreate) SetStatus(v AbsenceStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AbsenceCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


