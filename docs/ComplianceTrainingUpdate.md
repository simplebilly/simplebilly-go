# ComplianceTrainingUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assignable** | Pointer to **NullableBool** | Whether HR can assign this training as required for employees. | [optional] 
**Code** | Pointer to **NullableString** | Stable code used by plugins and frontend players (e.g. \&quot;data_privacy\&quot;). | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**PassScore** | Pointer to **NullableInt32** | Minimum score (0–100) required to pass. | [optional] 
**PluginPlatform** | Pointer to **NullableString** | Marketplace plugin platform id when source &#x3D; Plugin. | [optional] 
**Source** | Pointer to [**NullableTrainingSource**](TrainingSource.md) |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**ValidityMonths** | Pointer to **NullableInt32** | Certificate validity in months; null &#x3D; no expiry. | [optional] 

## Methods

### NewComplianceTrainingUpdate

`func NewComplianceTrainingUpdate() *ComplianceTrainingUpdate`

NewComplianceTrainingUpdate instantiates a new ComplianceTrainingUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComplianceTrainingUpdateWithDefaults

`func NewComplianceTrainingUpdateWithDefaults() *ComplianceTrainingUpdate`

NewComplianceTrainingUpdateWithDefaults instantiates a new ComplianceTrainingUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignable

`func (o *ComplianceTrainingUpdate) GetAssignable() bool`

GetAssignable returns the Assignable field if non-nil, zero value otherwise.

### GetAssignableOk

`func (o *ComplianceTrainingUpdate) GetAssignableOk() (*bool, bool)`

GetAssignableOk returns a tuple with the Assignable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignable

`func (o *ComplianceTrainingUpdate) SetAssignable(v bool)`

SetAssignable sets Assignable field to given value.

### HasAssignable

`func (o *ComplianceTrainingUpdate) HasAssignable() bool`

HasAssignable returns a boolean if a field has been set.

### SetAssignableNil

`func (o *ComplianceTrainingUpdate) SetAssignableNil(b bool)`

 SetAssignableNil sets the value for Assignable to be an explicit nil

### UnsetAssignable
`func (o *ComplianceTrainingUpdate) UnsetAssignable()`

UnsetAssignable ensures that no value is present for Assignable, not even an explicit nil
### GetCode

`func (o *ComplianceTrainingUpdate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ComplianceTrainingUpdate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ComplianceTrainingUpdate) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ComplianceTrainingUpdate) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *ComplianceTrainingUpdate) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *ComplianceTrainingUpdate) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetDescription

`func (o *ComplianceTrainingUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComplianceTrainingUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComplianceTrainingUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ComplianceTrainingUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ComplianceTrainingUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ComplianceTrainingUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPassScore

`func (o *ComplianceTrainingUpdate) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *ComplianceTrainingUpdate) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *ComplianceTrainingUpdate) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.

### HasPassScore

`func (o *ComplianceTrainingUpdate) HasPassScore() bool`

HasPassScore returns a boolean if a field has been set.

### SetPassScoreNil

`func (o *ComplianceTrainingUpdate) SetPassScoreNil(b bool)`

 SetPassScoreNil sets the value for PassScore to be an explicit nil

### UnsetPassScore
`func (o *ComplianceTrainingUpdate) UnsetPassScore()`

UnsetPassScore ensures that no value is present for PassScore, not even an explicit nil
### GetPluginPlatform

`func (o *ComplianceTrainingUpdate) GetPluginPlatform() string`

GetPluginPlatform returns the PluginPlatform field if non-nil, zero value otherwise.

### GetPluginPlatformOk

`func (o *ComplianceTrainingUpdate) GetPluginPlatformOk() (*string, bool)`

GetPluginPlatformOk returns a tuple with the PluginPlatform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginPlatform

`func (o *ComplianceTrainingUpdate) SetPluginPlatform(v string)`

SetPluginPlatform sets PluginPlatform field to given value.

### HasPluginPlatform

`func (o *ComplianceTrainingUpdate) HasPluginPlatform() bool`

HasPluginPlatform returns a boolean if a field has been set.

### SetPluginPlatformNil

`func (o *ComplianceTrainingUpdate) SetPluginPlatformNil(b bool)`

 SetPluginPlatformNil sets the value for PluginPlatform to be an explicit nil

### UnsetPluginPlatform
`func (o *ComplianceTrainingUpdate) UnsetPluginPlatform()`

UnsetPluginPlatform ensures that no value is present for PluginPlatform, not even an explicit nil
### GetSource

`func (o *ComplianceTrainingUpdate) GetSource() TrainingSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ComplianceTrainingUpdate) GetSourceOk() (*TrainingSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ComplianceTrainingUpdate) SetSource(v TrainingSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *ComplianceTrainingUpdate) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *ComplianceTrainingUpdate) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *ComplianceTrainingUpdate) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetTitle

`func (o *ComplianceTrainingUpdate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ComplianceTrainingUpdate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ComplianceTrainingUpdate) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ComplianceTrainingUpdate) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *ComplianceTrainingUpdate) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ComplianceTrainingUpdate) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetValidityMonths

`func (o *ComplianceTrainingUpdate) GetValidityMonths() int32`

GetValidityMonths returns the ValidityMonths field if non-nil, zero value otherwise.

### GetValidityMonthsOk

`func (o *ComplianceTrainingUpdate) GetValidityMonthsOk() (*int32, bool)`

GetValidityMonthsOk returns a tuple with the ValidityMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidityMonths

`func (o *ComplianceTrainingUpdate) SetValidityMonths(v int32)`

SetValidityMonths sets ValidityMonths field to given value.

### HasValidityMonths

`func (o *ComplianceTrainingUpdate) HasValidityMonths() bool`

HasValidityMonths returns a boolean if a field has been set.

### SetValidityMonthsNil

`func (o *ComplianceTrainingUpdate) SetValidityMonthsNil(b bool)`

 SetValidityMonthsNil sets the value for ValidityMonths to be an explicit nil

### UnsetValidityMonths
`func (o *ComplianceTrainingUpdate) UnsetValidityMonths()`

UnsetValidityMonths ensures that no value is present for ValidityMonths, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


