# ComplianceTrainingCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assignable** | Pointer to **bool** | Whether HR can assign this training as required for employees. | [optional] 
**Code** | Pointer to **string** | Stable code used by plugins and frontend players (e.g. \&quot;data_privacy\&quot;). | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**PassScore** | Pointer to **int32** | Minimum score (0–100) required to pass. | [optional] 
**PluginPlatform** | Pointer to **NullableString** | Marketplace plugin platform id when source &#x3D; Plugin. | [optional] 
**Source** | Pointer to [**TrainingSource**](TrainingSource.md) |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**ValidityMonths** | Pointer to **NullableInt32** | Certificate validity in months; null &#x3D; no expiry. | [optional] 

## Methods

### NewComplianceTrainingCreate

`func NewComplianceTrainingCreate() *ComplianceTrainingCreate`

NewComplianceTrainingCreate instantiates a new ComplianceTrainingCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComplianceTrainingCreateWithDefaults

`func NewComplianceTrainingCreateWithDefaults() *ComplianceTrainingCreate`

NewComplianceTrainingCreateWithDefaults instantiates a new ComplianceTrainingCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignable

`func (o *ComplianceTrainingCreate) GetAssignable() bool`

GetAssignable returns the Assignable field if non-nil, zero value otherwise.

### GetAssignableOk

`func (o *ComplianceTrainingCreate) GetAssignableOk() (*bool, bool)`

GetAssignableOk returns a tuple with the Assignable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignable

`func (o *ComplianceTrainingCreate) SetAssignable(v bool)`

SetAssignable sets Assignable field to given value.

### HasAssignable

`func (o *ComplianceTrainingCreate) HasAssignable() bool`

HasAssignable returns a boolean if a field has been set.

### GetCode

`func (o *ComplianceTrainingCreate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ComplianceTrainingCreate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ComplianceTrainingCreate) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ComplianceTrainingCreate) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *ComplianceTrainingCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComplianceTrainingCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComplianceTrainingCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ComplianceTrainingCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ComplianceTrainingCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ComplianceTrainingCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPassScore

`func (o *ComplianceTrainingCreate) GetPassScore() int32`

GetPassScore returns the PassScore field if non-nil, zero value otherwise.

### GetPassScoreOk

`func (o *ComplianceTrainingCreate) GetPassScoreOk() (*int32, bool)`

GetPassScoreOk returns a tuple with the PassScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassScore

`func (o *ComplianceTrainingCreate) SetPassScore(v int32)`

SetPassScore sets PassScore field to given value.

### HasPassScore

`func (o *ComplianceTrainingCreate) HasPassScore() bool`

HasPassScore returns a boolean if a field has been set.

### GetPluginPlatform

`func (o *ComplianceTrainingCreate) GetPluginPlatform() string`

GetPluginPlatform returns the PluginPlatform field if non-nil, zero value otherwise.

### GetPluginPlatformOk

`func (o *ComplianceTrainingCreate) GetPluginPlatformOk() (*string, bool)`

GetPluginPlatformOk returns a tuple with the PluginPlatform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginPlatform

`func (o *ComplianceTrainingCreate) SetPluginPlatform(v string)`

SetPluginPlatform sets PluginPlatform field to given value.

### HasPluginPlatform

`func (o *ComplianceTrainingCreate) HasPluginPlatform() bool`

HasPluginPlatform returns a boolean if a field has been set.

### SetPluginPlatformNil

`func (o *ComplianceTrainingCreate) SetPluginPlatformNil(b bool)`

 SetPluginPlatformNil sets the value for PluginPlatform to be an explicit nil

### UnsetPluginPlatform
`func (o *ComplianceTrainingCreate) UnsetPluginPlatform()`

UnsetPluginPlatform ensures that no value is present for PluginPlatform, not even an explicit nil
### GetSource

`func (o *ComplianceTrainingCreate) GetSource() TrainingSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ComplianceTrainingCreate) GetSourceOk() (*TrainingSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ComplianceTrainingCreate) SetSource(v TrainingSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *ComplianceTrainingCreate) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTitle

`func (o *ComplianceTrainingCreate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ComplianceTrainingCreate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ComplianceTrainingCreate) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ComplianceTrainingCreate) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetValidityMonths

`func (o *ComplianceTrainingCreate) GetValidityMonths() int32`

GetValidityMonths returns the ValidityMonths field if non-nil, zero value otherwise.

### GetValidityMonthsOk

`func (o *ComplianceTrainingCreate) GetValidityMonthsOk() (*int32, bool)`

GetValidityMonthsOk returns a tuple with the ValidityMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidityMonths

`func (o *ComplianceTrainingCreate) SetValidityMonths(v int32)`

SetValidityMonths sets ValidityMonths field to given value.

### HasValidityMonths

`func (o *ComplianceTrainingCreate) HasValidityMonths() bool`

HasValidityMonths returns a boolean if a field has been set.

### SetValidityMonthsNil

`func (o *ComplianceTrainingCreate) SetValidityMonthsNil(b bool)`

 SetValidityMonthsNil sets the value for ValidityMonths to be an explicit nil

### UnsetValidityMonths
`func (o *ComplianceTrainingCreate) UnsetValidityMonths()`

UnsetValidityMonths ensures that no value is present for ValidityMonths, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


