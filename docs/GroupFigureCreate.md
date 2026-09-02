# GroupFigureCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bilanzsumme** | Pointer to **string** | Bilanzsumme in EUR (§ 293 Abs. 1 Nr. 1 HGB). | [optional] 
**ExemptionClaimed** | Pointer to **bool** | § 291-Befreiung in Anspruch genommen. | [optional] 
**Mitarbeiter** | Pointer to **int64** | Durchschnittliche Arbeitnehmerzahl (§ 293 Abs. 1 Nr. 3 HGB). | [optional] 
**NettoUmsatz** | Pointer to **string** | Netto-Umsatzerlöse in EUR (§ 293 Abs. 1 Nr. 2 HGB). | [optional] 
**ParentName** | Pointer to **NullableString** | Name des Mutterunternehmens (§ 291 HGB, Zwischenholding). | [optional] 
**ParentSitus** | Pointer to **NullableString** | Sitz des Mutterunternehmens, z. B. \&quot;EU/EWR\&quot; (§ 291 HGB). | [optional] 

## Methods

### NewGroupFigureCreate

`func NewGroupFigureCreate() *GroupFigureCreate`

NewGroupFigureCreate instantiates a new GroupFigureCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupFigureCreateWithDefaults

`func NewGroupFigureCreateWithDefaults() *GroupFigureCreate`

NewGroupFigureCreateWithDefaults instantiates a new GroupFigureCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilanzsumme

`func (o *GroupFigureCreate) GetBilanzsumme() string`

GetBilanzsumme returns the Bilanzsumme field if non-nil, zero value otherwise.

### GetBilanzsummeOk

`func (o *GroupFigureCreate) GetBilanzsummeOk() (*string, bool)`

GetBilanzsummeOk returns a tuple with the Bilanzsumme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilanzsumme

`func (o *GroupFigureCreate) SetBilanzsumme(v string)`

SetBilanzsumme sets Bilanzsumme field to given value.

### HasBilanzsumme

`func (o *GroupFigureCreate) HasBilanzsumme() bool`

HasBilanzsumme returns a boolean if a field has been set.

### GetExemptionClaimed

`func (o *GroupFigureCreate) GetExemptionClaimed() bool`

GetExemptionClaimed returns the ExemptionClaimed field if non-nil, zero value otherwise.

### GetExemptionClaimedOk

`func (o *GroupFigureCreate) GetExemptionClaimedOk() (*bool, bool)`

GetExemptionClaimedOk returns a tuple with the ExemptionClaimed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExemptionClaimed

`func (o *GroupFigureCreate) SetExemptionClaimed(v bool)`

SetExemptionClaimed sets ExemptionClaimed field to given value.

### HasExemptionClaimed

`func (o *GroupFigureCreate) HasExemptionClaimed() bool`

HasExemptionClaimed returns a boolean if a field has been set.

### GetMitarbeiter

`func (o *GroupFigureCreate) GetMitarbeiter() int64`

GetMitarbeiter returns the Mitarbeiter field if non-nil, zero value otherwise.

### GetMitarbeiterOk

`func (o *GroupFigureCreate) GetMitarbeiterOk() (*int64, bool)`

GetMitarbeiterOk returns a tuple with the Mitarbeiter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMitarbeiter

`func (o *GroupFigureCreate) SetMitarbeiter(v int64)`

SetMitarbeiter sets Mitarbeiter field to given value.

### HasMitarbeiter

`func (o *GroupFigureCreate) HasMitarbeiter() bool`

HasMitarbeiter returns a boolean if a field has been set.

### GetNettoUmsatz

`func (o *GroupFigureCreate) GetNettoUmsatz() string`

GetNettoUmsatz returns the NettoUmsatz field if non-nil, zero value otherwise.

### GetNettoUmsatzOk

`func (o *GroupFigureCreate) GetNettoUmsatzOk() (*string, bool)`

GetNettoUmsatzOk returns a tuple with the NettoUmsatz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNettoUmsatz

`func (o *GroupFigureCreate) SetNettoUmsatz(v string)`

SetNettoUmsatz sets NettoUmsatz field to given value.

### HasNettoUmsatz

`func (o *GroupFigureCreate) HasNettoUmsatz() bool`

HasNettoUmsatz returns a boolean if a field has been set.

### GetParentName

`func (o *GroupFigureCreate) GetParentName() string`

GetParentName returns the ParentName field if non-nil, zero value otherwise.

### GetParentNameOk

`func (o *GroupFigureCreate) GetParentNameOk() (*string, bool)`

GetParentNameOk returns a tuple with the ParentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentName

`func (o *GroupFigureCreate) SetParentName(v string)`

SetParentName sets ParentName field to given value.

### HasParentName

`func (o *GroupFigureCreate) HasParentName() bool`

HasParentName returns a boolean if a field has been set.

### SetParentNameNil

`func (o *GroupFigureCreate) SetParentNameNil(b bool)`

 SetParentNameNil sets the value for ParentName to be an explicit nil

### UnsetParentName
`func (o *GroupFigureCreate) UnsetParentName()`

UnsetParentName ensures that no value is present for ParentName, not even an explicit nil
### GetParentSitus

`func (o *GroupFigureCreate) GetParentSitus() string`

GetParentSitus returns the ParentSitus field if non-nil, zero value otherwise.

### GetParentSitusOk

`func (o *GroupFigureCreate) GetParentSitusOk() (*string, bool)`

GetParentSitusOk returns a tuple with the ParentSitus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentSitus

`func (o *GroupFigureCreate) SetParentSitus(v string)`

SetParentSitus sets ParentSitus field to given value.

### HasParentSitus

`func (o *GroupFigureCreate) HasParentSitus() bool`

HasParentSitus returns a boolean if a field has been set.

### SetParentSitusNil

`func (o *GroupFigureCreate) SetParentSitusNil(b bool)`

 SetParentSitusNil sets the value for ParentSitus to be an explicit nil

### UnsetParentSitus
`func (o *GroupFigureCreate) UnsetParentSitus()`

UnsetParentSitus ensures that no value is present for ParentSitus, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


