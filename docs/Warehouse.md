# Warehouse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressCity** | Pointer to **NullableString** |  | [optional] 
**AddressCountry** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**AddressStreet** | Pointer to **NullableString** |  | [optional] 
**AddressZip** | Pointer to **NullableString** |  | [optional] 
**BinLocations** | Pointer to **interface{}** | JSON array of bin locations, e.g. &#x60;[\&quot;A-01-01\&quot;, \&quot;A-01-02\&quot;]&#x60;. | [optional] 
**Code** | **string** |  | 
**IsActive** | Pointer to **bool** |  | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] 
**Name** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWarehouse

`func NewWarehouse(code string, name string, ) *Warehouse`

NewWarehouse instantiates a new Warehouse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarehouseWithDefaults

`func NewWarehouseWithDefaults() *Warehouse`

NewWarehouseWithDefaults instantiates a new Warehouse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressCity

`func (o *Warehouse) GetAddressCity() string`

GetAddressCity returns the AddressCity field if non-nil, zero value otherwise.

### GetAddressCityOk

`func (o *Warehouse) GetAddressCityOk() (*string, bool)`

GetAddressCityOk returns a tuple with the AddressCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCity

`func (o *Warehouse) SetAddressCity(v string)`

SetAddressCity sets AddressCity field to given value.

### HasAddressCity

`func (o *Warehouse) HasAddressCity() bool`

HasAddressCity returns a boolean if a field has been set.

### SetAddressCityNil

`func (o *Warehouse) SetAddressCityNil(b bool)`

 SetAddressCityNil sets the value for AddressCity to be an explicit nil

### UnsetAddressCity
`func (o *Warehouse) UnsetAddressCity()`

UnsetAddressCity ensures that no value is present for AddressCity, not even an explicit nil
### GetAddressCountry

`func (o *Warehouse) GetAddressCountry() CountryCode`

GetAddressCountry returns the AddressCountry field if non-nil, zero value otherwise.

### GetAddressCountryOk

`func (o *Warehouse) GetAddressCountryOk() (*CountryCode, bool)`

GetAddressCountryOk returns a tuple with the AddressCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCountry

`func (o *Warehouse) SetAddressCountry(v CountryCode)`

SetAddressCountry sets AddressCountry field to given value.

### HasAddressCountry

`func (o *Warehouse) HasAddressCountry() bool`

HasAddressCountry returns a boolean if a field has been set.

### SetAddressCountryNil

`func (o *Warehouse) SetAddressCountryNil(b bool)`

 SetAddressCountryNil sets the value for AddressCountry to be an explicit nil

### UnsetAddressCountry
`func (o *Warehouse) UnsetAddressCountry()`

UnsetAddressCountry ensures that no value is present for AddressCountry, not even an explicit nil
### GetAddressStreet

`func (o *Warehouse) GetAddressStreet() string`

GetAddressStreet returns the AddressStreet field if non-nil, zero value otherwise.

### GetAddressStreetOk

`func (o *Warehouse) GetAddressStreetOk() (*string, bool)`

GetAddressStreetOk returns a tuple with the AddressStreet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressStreet

`func (o *Warehouse) SetAddressStreet(v string)`

SetAddressStreet sets AddressStreet field to given value.

### HasAddressStreet

`func (o *Warehouse) HasAddressStreet() bool`

HasAddressStreet returns a boolean if a field has been set.

### SetAddressStreetNil

`func (o *Warehouse) SetAddressStreetNil(b bool)`

 SetAddressStreetNil sets the value for AddressStreet to be an explicit nil

### UnsetAddressStreet
`func (o *Warehouse) UnsetAddressStreet()`

UnsetAddressStreet ensures that no value is present for AddressStreet, not even an explicit nil
### GetAddressZip

`func (o *Warehouse) GetAddressZip() string`

GetAddressZip returns the AddressZip field if non-nil, zero value otherwise.

### GetAddressZipOk

`func (o *Warehouse) GetAddressZipOk() (*string, bool)`

GetAddressZipOk returns a tuple with the AddressZip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressZip

`func (o *Warehouse) SetAddressZip(v string)`

SetAddressZip sets AddressZip field to given value.

### HasAddressZip

`func (o *Warehouse) HasAddressZip() bool`

HasAddressZip returns a boolean if a field has been set.

### SetAddressZipNil

`func (o *Warehouse) SetAddressZipNil(b bool)`

 SetAddressZipNil sets the value for AddressZip to be an explicit nil

### UnsetAddressZip
`func (o *Warehouse) UnsetAddressZip()`

UnsetAddressZip ensures that no value is present for AddressZip, not even an explicit nil
### GetBinLocations

`func (o *Warehouse) GetBinLocations() interface{}`

GetBinLocations returns the BinLocations field if non-nil, zero value otherwise.

### GetBinLocationsOk

`func (o *Warehouse) GetBinLocationsOk() (*interface{}, bool)`

GetBinLocationsOk returns a tuple with the BinLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinLocations

`func (o *Warehouse) SetBinLocations(v interface{})`

SetBinLocations sets BinLocations field to given value.

### HasBinLocations

`func (o *Warehouse) HasBinLocations() bool`

HasBinLocations returns a boolean if a field has been set.

### SetBinLocationsNil

`func (o *Warehouse) SetBinLocationsNil(b bool)`

 SetBinLocationsNil sets the value for BinLocations to be an explicit nil

### UnsetBinLocations
`func (o *Warehouse) UnsetBinLocations()`

UnsetBinLocations ensures that no value is present for BinLocations, not even an explicit nil
### GetCode

`func (o *Warehouse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Warehouse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Warehouse) SetCode(v string)`

SetCode sets Code field to given value.


### GetIsActive

`func (o *Warehouse) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *Warehouse) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *Warehouse) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *Warehouse) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetIsDefault

`func (o *Warehouse) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *Warehouse) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *Warehouse) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *Warehouse) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetName

`func (o *Warehouse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Warehouse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Warehouse) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *Warehouse) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Warehouse) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Warehouse) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Warehouse) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Warehouse) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Warehouse) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


