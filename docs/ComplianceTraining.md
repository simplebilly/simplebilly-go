# ComplianceTraining

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assignable** | Pointer to **bool** | Whether HR can assign this training as required for employees. | [optional] 
**Code** | Pointer to **string** | Stable code used by plugins and frontend players (e.g. \&quot;data_privacy\&quot;). | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**PassScore** | Pointer to **int32** | Minimum score (0–100) required to pass. | [optional] 
**PluginPlatform** | Pointer to **NullableString** | Marketplace plugin platform id when source &#x3D; Plugin. | [optional] 
**Source** | Pointer to [**TrainingSource**](TrainingSource.md) |  | [optional] 
**TenantId** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**ValidityMonths** | Pointer to **NullableInt32** | Certificate validity in months; null &#x3D; no expiry. | [optional] 

## Methods

### NewComplianceTraining

`func NewComplianceTraining() *ComplianceTraining`

NewComplianceTraining instantiates a new ComplianceTraining object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComplianceTrainingWithDefaults

`func NewComplianceTrainingWithDefaults() *ComplianceTraining`

NewComplianceTrainingWithDefaults instantiates a new ComplianceTraining object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignable

`func (o *ComplianceTraining) GetAssignable() bool`

GetAssignable returns the Assignable field if non-nil, zero value otherwise.

### GetAssignableOk

`func (o *ComplianceTraining) GetAssignableOk() (*bool, bool)`

GetAssignableOk returns a tuple with the Assignable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignable

`func (o *ComplianceTraining) SetAssignable(v bool)`

SetAssignable sets Assignable field to given value.

### HasAssignable

`func (o *ComplianceTraining) HasAssignable() bool`

HasAssignable returns a boolean if a field has been set.

### GetCode

`func (o *ComplianceTraining) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ComplianceTraining) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ComplianceTraining) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ComplianceTraining) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ComplianceTraining) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ComplianceTraining) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ComplianceTraining) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ComplianceTraining) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDeletedAt

`func (o *ComplianceTraining) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *ComplianceTraining) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *ComplianceTraining) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *ComplianceTraining) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *ComplianceTraining) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *ComplianceTraining) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetDescription

`func (o *ComplianceTraining) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComplianceTraining) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComplianceTraining) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ComplianceTraining) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ComplianceTraining) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ComplianceTraining) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetId

`func (o *ComplianceTraining) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ComplianceTraining) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ComplianceTraining) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ComplianceTraining) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPassScore

`func (o *ComplianceTraining) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *ComplianceTraining) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *ComplianceTraining) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.

### HasPassScore

`func (o *ComplianceTraining) HasPassScore() bool`

HasPassScore returns a boolean if a field has been set.

### GetPluginPlatform

`func (o *ComplianceTraining) GetPluginPlatform() string`

GetPluginPlatform returns the PluginPlatform field if non-nil, zero value otherwise.

### GetPluginPlatformOk

`func (o *ComplianceTraining) GetPluginPlatformOk() (*string, bool)`

GetPluginPlatformOk returns a tuple with the PluginPlatform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginPlatform

`func (o *ComplianceTraining) SetPluginPlatform(v string)`

SetPluginPlatform sets PluginPlatform field to given value.

### HasPluginPlatform

`func (o *ComplianceTraining) HasPluginPlatform() bool`

HasPluginPlatform returns a boolean if a field has been set.

### SetPluginPlatformNil

`func (o *ComplianceTraining) SetPluginPlatformNil(b bool)`

 SetPluginPlatformNil sets the value for PluginPlatform to be an explicit nil

### UnsetPluginPlatform
`func (o *ComplianceTraining) UnsetPluginPlatform()`

UnsetPluginPlatform ensures that no value is present for PluginPlatform, not even an explicit nil
### GetSource

`func (o *ComplianceTraining) GetSource() TrainingSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ComplianceTraining) GetSourceOk() (*TrainingSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ComplianceTraining) SetSource(v TrainingSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *ComplianceTraining) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTenantId

`func (o *ComplianceTraining) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *ComplianceTraining) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *ComplianceTraining) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *ComplianceTraining) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetTitle

`func (o *ComplianceTraining) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ComplianceTraining) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ComplianceTraining) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ComplianceTraining) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ComplianceTraining) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ComplianceTraining) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ComplianceTraining) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ComplianceTraining) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ComplianceTraining) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ComplianceTraining) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetValidityMonths

`func (o *ComplianceTraining) GetValidityMonths() int32`

GetValidityMonths returns the ValidityMonths field if non-nil, zero value otherwise.

### GetValidityMonthsOk

`func (o *ComplianceTraining) GetValidityMonthsOk() (*int32, bool)`

GetValidityMonthsOk returns a tuple with the ValidityMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidityMonths

`func (o *ComplianceTraining) SetValidityMonths(v int32)`

SetValidityMonths sets ValidityMonths field to given value.

### HasValidityMonths

`func (o *ComplianceTraining) HasValidityMonths() bool`

HasValidityMonths returns a boolean if a field has been set.

### SetValidityMonthsNil

`func (o *ComplianceTraining) SetValidityMonthsNil(b bool)`

 SetValidityMonthsNil sets the value for ValidityMonths to be an explicit nil

### UnsetValidityMonths
`func (o *ComplianceTraining) UnsetValidityMonths()`

UnsetValidityMonths ensures that no value is present for ValidityMonths, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


