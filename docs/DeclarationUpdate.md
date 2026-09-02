# DeclarationUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeclarationType** | Pointer to [**NullableDeclarationType**](DeclarationType.md) | Art der Erklärung: \&quot;dcgk\&quot; (Entsprechenserklärung § 161 AktG) oder \&quot;unternehmensfuehrung\&quot; (Erklärung zur Unternehmensführung § 289f HGB). | [optional] 
**IsCurrent** | Pointer to **NullableBool** | Kennzeichnet die aktuell gültige Fassung (max. eine je Mandant). | [optional] 
**Text** | Pointer to **NullableString** | Inhalt der Erklärung als Markdown. | [optional] 
**ValidFrom** | Pointer to **NullableString** | Datum, ab dem die Erklärung gilt. | [optional] 
**Version** | Pointer to **NullableString** | Versionsbezeichnung der Erklärung (z.B. \&quot;2025-01\&quot;). | [optional] 

## Methods

### NewDeclarationUpdate

`func NewDeclarationUpdate() *DeclarationUpdate`

NewDeclarationUpdate instantiates a new DeclarationUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeclarationUpdateWithDefaults

`func NewDeclarationUpdateWithDefaults() *DeclarationUpdate`

NewDeclarationUpdateWithDefaults instantiates a new DeclarationUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeclarationType

`func (o *DeclarationUpdate) GetDeclarationType() DeclarationType`

GetDeclarationType returns the DeclarationType field if non-nil, zero value otherwise.

### GetDeclarationTypeOk

`func (o *DeclarationUpdate) GetDeclarationTypeOk() (*DeclarationType, bool)`

GetDeclarationTypeOk returns a tuple with the DeclarationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclarationType

`func (o *DeclarationUpdate) SetDeclarationType(v DeclarationType)`

SetDeclarationType sets DeclarationType field to given value.

### HasDeclarationType

`func (o *DeclarationUpdate) HasDeclarationType() bool`

HasDeclarationType returns a boolean if a field has been set.

### SetDeclarationTypeNil

`func (o *DeclarationUpdate) SetDeclarationTypeNil(b bool)`

 SetDeclarationTypeNil sets the value for DeclarationType to be an explicit nil

### UnsetDeclarationType
`func (o *DeclarationUpdate) UnsetDeclarationType()`

UnsetDeclarationType ensures that no value is present for DeclarationType, not even an explicit nil
### GetIsCurrent

`func (o *DeclarationUpdate) GetIsCurrent() bool`

GetIsCurrent returns the IsCurrent field if non-nil, zero value otherwise.

### GetIsCurrentOk

`func (o *DeclarationUpdate) GetIsCurrentOk() (*bool, bool)`

GetIsCurrentOk returns a tuple with the IsCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCurrent

`func (o *DeclarationUpdate) SetIsCurrent(v bool)`

SetIsCurrent sets IsCurrent field to given value.

### HasIsCurrent

`func (o *DeclarationUpdate) HasIsCurrent() bool`

HasIsCurrent returns a boolean if a field has been set.

### SetIsCurrentNil

`func (o *DeclarationUpdate) SetIsCurrentNil(b bool)`

 SetIsCurrentNil sets the value for IsCurrent to be an explicit nil

### UnsetIsCurrent
`func (o *DeclarationUpdate) UnsetIsCurrent()`

UnsetIsCurrent ensures that no value is present for IsCurrent, not even an explicit nil
### GetText

`func (o *DeclarationUpdate) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *DeclarationUpdate) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *DeclarationUpdate) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *DeclarationUpdate) HasText() bool`

HasText returns a boolean if a field has been set.

### SetTextNil

`func (o *DeclarationUpdate) SetTextNil(b bool)`

 SetTextNil sets the value for Text to be an explicit nil

### UnsetText
`func (o *DeclarationUpdate) UnsetText()`

UnsetText ensures that no value is present for Text, not even an explicit nil
### GetValidFrom

`func (o *DeclarationUpdate) GetValidFrom() string`

GetValidFrom returns the ValidFrom field if non-nil, zero value otherwise.

### GetValidFromOk

`func (o *DeclarationUpdate) GetValidFromOk() (*string, bool)`

GetValidFromOk returns a tuple with the ValidFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidFrom

`func (o *DeclarationUpdate) SetValidFrom(v string)`

SetValidFrom sets ValidFrom field to given value.

### HasValidFrom

`func (o *DeclarationUpdate) HasValidFrom() bool`

HasValidFrom returns a boolean if a field has been set.

### SetValidFromNil

`func (o *DeclarationUpdate) SetValidFromNil(b bool)`

 SetValidFromNil sets the value for ValidFrom to be an explicit nil

### UnsetValidFrom
`func (o *DeclarationUpdate) UnsetValidFrom()`

UnsetValidFrom ensures that no value is present for ValidFrom, not even an explicit nil
### GetVersion

`func (o *DeclarationUpdate) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DeclarationUpdate) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DeclarationUpdate) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *DeclarationUpdate) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *DeclarationUpdate) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *DeclarationUpdate) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


