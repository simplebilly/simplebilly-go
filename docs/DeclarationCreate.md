# DeclarationCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeclarationType** | Pointer to [**DeclarationType**](DeclarationType.md) | Art der Erklärung: \&quot;dcgk\&quot; (Entsprechenserklärung § 161 AktG) oder \&quot;unternehmensfuehrung\&quot; (Erklärung zur Unternehmensführung § 289f HGB). | [optional] 
**IsCurrent** | Pointer to **bool** | Kennzeichnet die aktuell gültige Fassung (max. eine je Mandant). | [optional] 
**Text** | Pointer to **string** | Inhalt der Erklärung als Markdown. | [optional] 
**ValidFrom** | Pointer to **string** | Datum, ab dem die Erklärung gilt. | [optional] 
**Version** | Pointer to **string** | Versionsbezeichnung der Erklärung (z.B. \&quot;2025-01\&quot;). | [optional] 

## Methods

### NewDeclarationCreate

`func NewDeclarationCreate() *DeclarationCreate`

NewDeclarationCreate instantiates a new DeclarationCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeclarationCreateWithDefaults

`func NewDeclarationCreateWithDefaults() *DeclarationCreate`

NewDeclarationCreateWithDefaults instantiates a new DeclarationCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeclarationType

`func (o *DeclarationCreate) GetDeclarationType() DeclarationType`

GetDeclarationType returns the DeclarationType field if non-nil, zero value otherwise.

### GetDeclarationTypeOk

`func (o *DeclarationCreate) GetDeclarationTypeOk() (*DeclarationType, bool)`

GetDeclarationTypeOk returns a tuple with the DeclarationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclarationType

`func (o *DeclarationCreate) SetDeclarationType(v DeclarationType)`

SetDeclarationType sets DeclarationType field to given value.

### HasDeclarationType

`func (o *DeclarationCreate) HasDeclarationType() bool`

HasDeclarationType returns a boolean if a field has been set.

### GetIsCurrent

`func (o *DeclarationCreate) GetIsCurrent() bool`

GetIsCurrent returns the IsCurrent field if non-nil, zero value otherwise.

### GetIsCurrentOk

`func (o *DeclarationCreate) GetIsCurrentOk() (*bool, bool)`

GetIsCurrentOk returns a tuple with the IsCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCurrent

`func (o *DeclarationCreate) SetIsCurrent(v bool)`

SetIsCurrent sets IsCurrent field to given value.

### HasIsCurrent

`func (o *DeclarationCreate) HasIsCurrent() bool`

HasIsCurrent returns a boolean if a field has been set.

### GetText

`func (o *DeclarationCreate) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *DeclarationCreate) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *DeclarationCreate) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *DeclarationCreate) HasText() bool`

HasText returns a boolean if a field has been set.

### GetValidFrom

`func (o *DeclarationCreate) GetValidFrom() string`

GetValidFrom returns the ValidFrom field if non-nil, zero value otherwise.

### GetValidFromOk

`func (o *DeclarationCreate) GetValidFromOk() (*string, bool)`

GetValidFromOk returns a tuple with the ValidFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidFrom

`func (o *DeclarationCreate) SetValidFrom(v string)`

SetValidFrom sets ValidFrom field to given value.

### HasValidFrom

`func (o *DeclarationCreate) HasValidFrom() bool`

HasValidFrom returns a boolean if a field has been set.

### GetVersion

`func (o *DeclarationCreate) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DeclarationCreate) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DeclarationCreate) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *DeclarationCreate) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


