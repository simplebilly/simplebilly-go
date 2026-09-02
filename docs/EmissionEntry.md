# EmissionEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityValue** | **string** | Activity amount in &#x60;unit&#x60; (kWh, l, km, t, tkm, EUR). | 
**CategoryId** | **string** | GHG-Protocol category key, e.g. \&quot;purchased_goods\&quot;, \&quot;business_travel\&quot;. | 
**Description** | **string** |  | 
**EfSource** | **string** | Emission-factor source, e.g. \&quot;UBA-2024\&quot;, \&quot;DEFRA-2024\&quot;. | 
**EfVersion** | **string** |  | 
**Method** | [**EmissionMethod**](EmissionMethod.md) | \&quot;activity\&quot; | \&quot;spend\&quot; | \&quot;supplier\&quot;. | 
**Scope** | [**GhgScope**](GhgScope.md) | GHG scope: \&quot;1\&quot; | \&quot;2\&quot; | \&quot;3\&quot;. | 
**Tco2e** | **string** | Computed server-side: activity * factor / 1000, rounded to 4 dp. | 
**Unit** | **string** | Unit of the activity value. | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**Year** | **int32** | Reporting year. | 

## Methods

### NewEmissionEntry

`func NewEmissionEntry(activityValue string, categoryId string, description string, efSource string, efVersion string, method EmissionMethod, scope GhgScope, tco2e string, unit string, year int32, ) *EmissionEntry`

NewEmissionEntry instantiates a new EmissionEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmissionEntryWithDefaults

`func NewEmissionEntryWithDefaults() *EmissionEntry`

NewEmissionEntryWithDefaults instantiates a new EmissionEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityValue

`func (o *EmissionEntry) GetActivityValue() string`

GetActivityValue returns the ActivityValue field if non-nil, zero value otherwise.

### GetActivityValueOk

`func (o *EmissionEntry) GetActivityValueOk() (*string, bool)`

GetActivityValueOk returns a tuple with the ActivityValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityValue

`func (o *EmissionEntry) SetActivityValue(v string)`

SetActivityValue sets ActivityValue field to given value.


### GetCategoryId

`func (o *EmissionEntry) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *EmissionEntry) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *EmissionEntry) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.


### GetDescription

`func (o *EmissionEntry) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *EmissionEntry) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *EmissionEntry) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEfSource

`func (o *EmissionEntry) GetEfSource() string`

GetEfSource returns the EfSource field if non-nil, zero value otherwise.

### GetEfSourceOk

`func (o *EmissionEntry) GetEfSourceOk() (*string, bool)`

GetEfSourceOk returns a tuple with the EfSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEfSource

`func (o *EmissionEntry) SetEfSource(v string)`

SetEfSource sets EfSource field to given value.


### GetEfVersion

`func (o *EmissionEntry) GetEfVersion() string`

GetEfVersion returns the EfVersion field if non-nil, zero value otherwise.

### GetEfVersionOk

`func (o *EmissionEntry) GetEfVersionOk() (*string, bool)`

GetEfVersionOk returns a tuple with the EfVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEfVersion

`func (o *EmissionEntry) SetEfVersion(v string)`

SetEfVersion sets EfVersion field to given value.


### GetMethod

`func (o *EmissionEntry) GetMethod() EmissionMethod`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *EmissionEntry) GetMethodOk() (*EmissionMethod, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *EmissionEntry) SetMethod(v EmissionMethod)`

SetMethod sets Method field to given value.


### GetScope

`func (o *EmissionEntry) GetScope() GhgScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *EmissionEntry) GetScopeOk() (*GhgScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *EmissionEntry) SetScope(v GhgScope)`

SetScope sets Scope field to given value.


### GetTco2e

`func (o *EmissionEntry) GetTco2e() string`

GetTco2e returns the Tco2e field if non-nil, zero value otherwise.

### GetTco2eOk

`func (o *EmissionEntry) GetTco2eOk() (*string, bool)`

GetTco2eOk returns a tuple with the Tco2e field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTco2e

`func (o *EmissionEntry) SetTco2e(v string)`

SetTco2e sets Tco2e field to given value.


### GetUnit

`func (o *EmissionEntry) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *EmissionEntry) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *EmissionEntry) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUpdatedAt

`func (o *EmissionEntry) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EmissionEntry) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EmissionEntry) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *EmissionEntry) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *EmissionEntry) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *EmissionEntry) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetYear

`func (o *EmissionEntry) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *EmissionEntry) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *EmissionEntry) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


