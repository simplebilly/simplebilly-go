# GroupFigure

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bilanzsumme** | Pointer to **string** | Bilanzsumme in EUR (§ 293 Abs. 1 Nr. 1 HGB). | [optional] 
**ExemptionClaimed** | Pointer to **bool** | § 291-Befreiung in Anspruch genommen. | [optional] 
**Mitarbeiter** | Pointer to **int64** | Durchschnittliche Arbeitnehmerzahl (§ 293 Abs. 1 Nr. 3 HGB). | [optional] 
**NettoUmsatz** | Pointer to **string** | Netto-Umsatzerlöse in EUR (§ 293 Abs. 1 Nr. 2 HGB). | [optional] 
**ParentName** | Pointer to **NullableString** | Name des Mutterunternehmens (§ 291 HGB, Zwischenholding). | [optional] 
**ParentSitus** | Pointer to **NullableString** | Sitz des Mutterunternehmens, z. B. \&quot;EU/EWR\&quot; (§ 291 HGB). | [optional] 
**Year** | **int32** |  | 

## Methods

### NewGroupFigure

`func NewGroupFigure(year int32, ) *GroupFigure`

NewGroupFigure instantiates a new GroupFigure object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupFigureWithDefaults

`func NewGroupFigureWithDefaults() *GroupFigure`

NewGroupFigureWithDefaults instantiates a new GroupFigure object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilanzsumme

`func (o *GroupFigure) GetBilanzsumme() string`

GetBilanzsumme returns the Bilanzsumme field if non-nil, zero value otherwise.

### GetBilanzsummeOk

`func (o *GroupFigure) GetBilanzsummeOk() (*string, bool)`

GetBilanzsummeOk returns a tuple with the Bilanzsumme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilanzsumme

`func (o *GroupFigure) SetBilanzsumme(v string)`

SetBilanzsumme sets Bilanzsumme field to given value.

### HasBilanzsumme

`func (o *GroupFigure) HasBilanzsumme() bool`

HasBilanzsumme returns a boolean if a field has been set.

### GetExemptionClaimed

`func (o *GroupFigure) GetExemptionClaimed() bool`

GetExemptionClaimed returns the ExemptionClaimed field if non-nil, zero value otherwise.

### GetExemptionClaimedOk

`func (o *GroupFigure) GetExemptionClaimedOk() (*bool, bool)`

GetExemptionClaimedOk returns a tuple with the ExemptionClaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExemptionClaimed

`func (o *GroupFigure) SetExemptionClaimed(v bool)`

SetExemptionClaimed sets ExemptionClaimed field to given value.

### HasExemptionClaimed

`func (o *GroupFigure) HasExemptionClaimed() bool`

HasExemptionClaimed returns a boolean if a field has been set.

### GetMitarbeiter

`func (o *GroupFigure) GetMitarbeiter() int64`

GetMitarbeiter returns the Mitarbeiter field if non-nil, zero value otherwise.

### GetMitarbeiterOk

`func (o *GroupFigure) GetMitarbeiterOk() (*int64, bool)`

GetMitarbeiterOk returns a tuple with the Mitarbeiter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMitarbeiter

`func (o *GroupFigure) SetMitarbeiter(v int64)`

SetMitarbeiter sets Mitarbeiter field to given value.

### HasMitarbeiter

`func (o *GroupFigure) HasMitarbeiter() bool`

HasMitarbeiter returns a boolean if a field has been set.

### GetNettoUmsatz

`func (o *GroupFigure) GetNettoUmsatz() string`

GetNettoUmsatz returns the NettoUmsatz field if non-nil, zero value otherwise.

### GetNettoUmsatzOk

`func (o *GroupFigure) GetNettoUmsatzOk() (*string, bool)`

GetNettoUmsatzOk returns a tuple with the NettoUmsatz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNettoUmsatz

`func (o *GroupFigure) SetNettoUmsatz(v string)`

SetNettoUmsatz sets NettoUmsatz field to given value.

### HasNettoUmsatz

`func (o *GroupFigure) HasNettoUmsatz() bool`

HasNettoUmsatz returns a boolean if a field has been set.

### GetParentName

`func (o *GroupFigure) GetParentName() string`

GetParentName returns the ParentName field if non-nil, zero value otherwise.

### GetParentNameOk

`func (o *GroupFigure) GetParentNameOk() (*string, bool)`

GetParentNameOk returns a tuple with the ParentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentName

`func (o *GroupFigure) SetParentName(v string)`

SetParentName sets ParentName field to given value.

### HasParentName

`func (o *GroupFigure) HasParentName() bool`

HasParentName returns a boolean if a field has been set.

### SetParentNameNil

`func (o *GroupFigure) SetParentNameNil(b bool)`

 SetParentNameNil sets the value for ParentName to be an explicit nil

### UnsetParentName
`func (o *GroupFigure) UnsetParentName()`

UnsetParentName ensures that no value is present for ParentName, not even an explicit nil
### GetParentSitus

`func (o *GroupFigure) GetParentSitus() string`

GetParentSitus returns the ParentSitus field if non-nil, zero value otherwise.

### GetParentSitusOk

`func (o *GroupFigure) GetParentSitusOk() (*string, bool)`

GetParentSitusOk returns a tuple with the ParentSitus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSitus

`func (o *GroupFigure) SetParentSitus(v string)`

SetParentSitus sets ParentSitus field to given value.

### HasParentSitus

`func (o *GroupFigure) HasParentSitus() bool`

HasParentSitus returns a boolean if a field has been set.

### SetParentSitusNil

`func (o *GroupFigure) SetParentSitusNil(b bool)`

 SetParentSitusNil sets the value for ParentSitus to be an explicit nil

### UnsetParentSitus
`func (o *GroupFigure) UnsetParentSitus()`

UnsetParentSitus ensures that no value is present for ParentSitus, not even an explicit nil
### GetYear

`func (o *GroupFigure) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *GroupFigure) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *GroupFigure) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


