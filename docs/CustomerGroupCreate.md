# CustomerGroupCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**MemberIds** | Pointer to **[]string** | Contact ids that are members of this group. | [optional] 
**MembershipFilter** | Pointer to **NullableString** | Rule description for membership, e.g. \&quot;orders &gt; 5 last 12 months\&quot;. | [optional] 
**Name** | **string** | Unique group name, e.g. \&quot;VIP\&quot;, \&quot;Wholesale\&quot;, \&quot;Newsletter\&quot;. | 

## Methods

### NewCustomerGroupCreate

`func NewCustomerGroupCreate(name string, ) *CustomerGroupCreate`

NewCustomerGroupCreate instantiates a new CustomerGroupCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerGroupCreateWithDefaults

`func NewCustomerGroupCreateWithDefaults() *CustomerGroupCreate`

NewCustomerGroupCreateWithDefaults instantiates a new CustomerGroupCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *CustomerGroupCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerGroupCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerGroupCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerGroupCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CustomerGroupCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CustomerGroupCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetMemberIds

`func (o *CustomerGroupCreate) GetMemberIds() []string`

GetMemberIds returns the MemberIds field if non-nil, zero value otherwise.

### GetMemberIdsOk

`func (o *CustomerGroupCreate) GetMemberIdsOk() (*[]string, bool)`

GetMemberIdsOk returns a tuple with the MemberIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberIds

`func (o *CustomerGroupCreate) SetMemberIds(v []string)`

SetMemberIds sets MemberIds field to given value.

### HasMemberIds

`func (o *CustomerGroupCreate) HasMemberIds() bool`

HasMemberIds returns a boolean if a field has been set.

### GetMembershipFilter

`func (o *CustomerGroupCreate) GetMembershipFilter() string`

GetMembershipFilter returns the MembershipFilter field if non-nil, zero value otherwise.

### GetMembershipFilterOk

`func (o *CustomerGroupCreate) GetMembershipFilterOk() (*string, bool)`

GetMembershipFilterOk returns a tuple with the MembershipFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipFilter

`func (o *CustomerGroupCreate) SetMembershipFilter(v string)`

SetMembershipFilter sets MembershipFilter field to given value.

### HasMembershipFilter

`func (o *CustomerGroupCreate) HasMembershipFilter() bool`

HasMembershipFilter returns a boolean if a field has been set.

### SetMembershipFilterNil

`func (o *CustomerGroupCreate) SetMembershipFilterNil(b bool)`

 SetMembershipFilterNil sets the value for MembershipFilter to be an explicit nil

### UnsetMembershipFilter
`func (o *CustomerGroupCreate) UnsetMembershipFilter()`

UnsetMembershipFilter ensures that no value is present for MembershipFilter, not even an explicit nil
### GetName

`func (o *CustomerGroupCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerGroupCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerGroupCreate) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


