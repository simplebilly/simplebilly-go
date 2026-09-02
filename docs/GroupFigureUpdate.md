# GroupFigureUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bilanzsumme** | Pointer to **NullableString** | Bilanzsumme in EUR (§ 293 Abs. 1 Nr. 1 HGB). | [optional] 
**ExemptionClaimed** | Pointer to **NullableBool** | § 291-Befreiung in Anspruch genommen. | [optional] 
**Mitarbeiter** | Pointer to **NullableInt64** | Durchschnittliche Arbeitnehmerzahl (§ 293 Abs. 1 Nr. 3 HGB). | [optional] 
**NettoUmsatz** | Pointer to **NullableString** | Netto-Umsatzerlöse in EUR (§ 293 Abs. 1 Nr. 2 HGB). | [optional] 
**ParentName** | Pointer to **NullableString** | Name des Mutterunternehmens (§ 291 HGB, Zwischenholding). | [optional] 
**ParentSitus** | Pointer to **NullableString** | Sitz des Mutterunternehmens, z. B. \&quot;EU/EWR\&quot; (§ 291 HGB). | [optional] 

## Methods

### NewGroupFigureUpdate

`func NewGroupFigureUpdate() *GroupFigureUpdate`

NewGroupFigureUpdate instantiates a new GroupFigureUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupFigureUpdateWithDefaults

`func NewGroupFigureUpdateWithDefaults() *GroupFigureUpdate`

NewGroupFigureUpdateWithDefaults instantiates a new GroupFigureUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilanzsumme

`func (o *GroupFigureUpdate) GetBilanzsumme() string`

GetBilanzsumme returns the Bilanzsumme field if non-nil, zero value otherwise.

### GetBilanzsummeOk

`func (o *GroupFigureUpdate) GetBilanzsummeOk() (*string, bool)`

GetBilanzsummeOk returns a tuple with the Bilanzsumme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilanzsumme

`func (o *GroupFigureUpdate) SetBilanzsumme(v string)`

SetBilanzsumme sets Bilanzsumme field to given value.

### HasBilanzsumme

`func (o *GroupFigureUpdate) HasBilanzsumme() bool`

HasBilanzsumme returns a boolean if a field has been set.

### SetBilanzsummeNil

`func (o *GroupFigureUpdate) SetBilanzsummeNil(b bool)`

 SetBilanzsummeNil sets the value for Bilanzsumme to be an explicit nil

### UnsetBilanzsumme
`func (o *GroupFigureUpdate) UnsetBilanzsumme()`

UnsetBilanzsumme ensures that no value is present for Bilanzsumme, not even an explicit nil
### GetExemptionClaimed

`func (o *GroupFigureUpdate) GetExemptionClaimed() bool`

GetExemptionClaimed returns the ExemptionClaimed field if non-nil, zero value otherwise.

### GetExemptionClaimedOk

`func (o *GroupFigureUpdate) GetExemptionClaimedOk() (*bool, bool)`

GetExemptionClaimedOk returns a tuple with the ExemptionClaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExemptionClaimed

`func (o *GroupFigureUpdate) SetExemptionClaimed(v bool)`

SetExemptionClaimed sets ExemptionClaimed field to given value.

### HasExemptionClaimed

`func (o *GroupFigureUpdate) HasExemptionClaimed() bool`

HasExemptionClaimed returns a boolean if a field has been set.

### SetExemptionClaimedNil

`func (o *GroupFigureUpdate) SetExemptionClaimedNil(b bool)`

 SetExemptionClaimedNil sets the value for ExemptionClaimed to be an explicit nil

### UnsetExemptionClaimed
`func (o *GroupFigureUpdate) UnsetExemptionClaimed()`

UnsetExemptionClaimed ensures that no value is present for ExemptionClaimed, not even an explicit nil
### GetMitarbeiter

`func (o *GroupFigureUpdate) GetMitarbeiter() int64`

GetMitarbeiter returns the Mitarbeiter field if non-nil, zero value otherwise.

### GetMitarbeiterOk

`func (o *GroupFigureUpdate) GetMitarbeiterOk() (*int64, bool)`

GetMitarbeiterOk returns a tuple with the Mitarbeiter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMitarbeiter

`func (o *GroupFigureUpdate) SetMitarbeiter(v int64)`

SetMitarbeiter sets Mitarbeiter field to given value.

### HasMitarbeiter

`func (o *GroupFigureUpdate) HasMitarbeiter() bool`

HasMitarbeiter returns a boolean if a field has been set.

### SetMitarbeiterNil

`func (o *GroupFigureUpdate) SetMitarbeiterNil(b bool)`

 SetMitarbeiterNil sets the value for Mitarbeiter to be an explicit nil

### UnsetMitarbeiter
`func (o *GroupFigureUpdate) UnsetMitarbeiter()`

UnsetMitarbeiter ensures that no value is present for Mitarbeiter, not even an explicit nil
### GetNettoUmsatz

`func (o *GroupFigureUpdate) GetNettoUmsatz() string`

GetNettoUmsatz returns the NettoUmsatz field if non-nil, zero value otherwise.

### GetNettoUmsatzOk

`func (o *GroupFigureUpdate) GetNettoUmsatzOk() (*string, bool)`

GetNettoUmsatzOk returns a tuple with the NettoUmsatz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNettoUmsatz

`func (o *GroupFigureUpdate) SetNettoUmsatz(v string)`

SetNettoUmsatz sets NettoUmsatz field to given value.

### HasNettoUmsatz

`func (o *GroupFigureUpdate) HasNettoUmsatz() bool`

HasNettoUmsatz returns a boolean if a field has been set.

### SetNettoUmsatzNil

`func (o *GroupFigureUpdate) SetNettoUmsatzNil(b bool)`

 SetNettoUmsatzNil sets the value for NettoUmsatz to be an explicit nil

### UnsetNettoUmsatz
`func (o *GroupFigureUpdate) UnsetNettoUmsatz()`

UnsetNettoUmsatz ensures that no value is present for NettoUmsatz, not even an explicit nil
### GetParentName

`func (o *GroupFigureUpdate) GetParentName() string`

GetParentName returns the ParentName field if non-nil, zero value otherwise.

### GetParentNameOk

`func (o *GroupFigureUpdate) GetParentNameOk() (*string, bool)`

GetParentNameOk returns a tuple with the ParentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentName

`func (o *GroupFigureUpdate) SetParentName(v string)`

SetParentName sets ParentName field to given value.

### HasParentName

`func (o *GroupFigureUpdate) HasParentName() bool`

HasParentName returns a boolean if a field has been set.

### SetParentNameNil

`func (o *GroupFigureUpdate) SetParentNameNil(b bool)`

 SetParentNameNil sets the value for ParentName to be an explicit nil

### UnsetParentName
`func (o *GroupFigureUpdate) UnsetParentName()`

UnsetParentName ensures that no value is present for ParentName, not even an explicit nil
### GetParentSitus

`func (o *GroupFigureUpdate) GetParentSitus() string`

GetParentSitus returns the ParentSitus field if non-nil, zero value otherwise.

### GetParentSitusOk

`func (o *GroupFigureUpdate) GetParentSitusOk() (*string, bool)`

GetParentSitusOk returns a tuple with the ParentSitus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSitus

`func (o *GroupFigureUpdate) SetParentSitus(v string)`

SetParentSitus sets ParentSitus field to given value.

### HasParentSitus

`func (o *GroupFigureUpdate) HasParentSitus() bool`

HasParentSitus returns a boolean if a field has been set.

### SetParentSitusNil

`func (o *GroupFigureUpdate) SetParentSitusNil(b bool)`

 SetParentSitusNil sets the value for ParentSitus to be an explicit nil

### UnsetParentSitus
`func (o *GroupFigureUpdate) UnsetParentSitus()`

UnsetParentSitus ensures that no value is present for ParentSitus, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


