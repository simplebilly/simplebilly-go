# OffenlegungItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Exists** | **bool** | Ob die zugrunde liegenden Daten im System vorhanden sind. | 
**Name** | **string** | Bezeichnung des Offenlegungsbestandteils (§ 325 Abs. 1 HGB). | 
**Source** | **string** | Woher der Bestandteil stammt bzw. fehlt. | 

## Methods

### NewOffenlegungItem

`func NewOffenlegungItem(exists bool, name string, source string, ) *OffenlegungItem`

NewOffenlegungItem instantiates a new OffenlegungItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOffenlegungItemWithDefaults

`func NewOffenlegungItemWithDefaults() *OffenlegungItem`

NewOffenlegungItemWithDefaults instantiates a new OffenlegungItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExists

`func (o *OffenlegungItem) GetExists() bool`

GetExists returns the Exists field if non-nil, zero value otherwise.

### GetExistsOk

`func (o *OffenlegungItem) GetExistsOk() (*bool, bool)`

GetExistsOk returns a tuple with the Exists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExists

`func (o *OffenlegungItem) SetExists(v bool)`

SetExists sets Exists field to given value.


### GetName

`func (o *OffenlegungItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OffenlegungItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OffenlegungItem) SetName(v string)`

SetName sets Name field to given value.


### GetSource

`func (o *OffenlegungItem) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *OffenlegungItem) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *OffenlegungItem) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


