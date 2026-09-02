# BudgetKategorie

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Budget** | **string** |  | 
**Differenz** | **string** |  | 
**Goal** | Pointer to **NullableString** | User-set monthly goal for the category, if any. | [optional] 
**Ist** | **string** |  | 
**Kategorie** | **string** |  | 

## Methods

### NewBudgetKategorie

`func NewBudgetKategorie(budget string, differenz string, ist string, kategorie string, ) *BudgetKategorie`

NewBudgetKategorie instantiates a new BudgetKategorie object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetKategorieWithDefaults

`func NewBudgetKategorieWithDefaults() *BudgetKategorie`

NewBudgetKategorieWithDefaults instantiates a new BudgetKategorie object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBudget

`func (o *BudgetKategorie) GetBudget() string`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *BudgetKategorie) GetBudgetOk() (*string, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *BudgetKategorie) SetBudget(v string)`

SetBudget sets Budget field to given value.


### GetDifferenz

`func (o *BudgetKategorie) GetDifferenz() string`

GetDifferenz returns the Differenz field if non-nil, zero value otherwise.

### GetDifferenzOk

`func (o *BudgetKategorie) GetDifferenzOk() (*string, bool)`

GetDifferenzOk returns a tuple with the Differenz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDifferenz

`func (o *BudgetKategorie) SetDifferenz(v string)`

SetDifferenz sets Differenz field to given value.


### GetGoal

`func (o *BudgetKategorie) GetGoal() string`

GetGoal returns the Goal field if non-nil, zero value otherwise.

### GetGoalOk

`func (o *BudgetKategorie) GetGoalOk() (*string, bool)`

GetGoalOk returns a tuple with the Goal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoal

`func (o *BudgetKategorie) SetGoal(v string)`

SetGoal sets Goal field to given value.

### HasGoal

`func (o *BudgetKategorie) HasGoal() bool`

HasGoal returns a boolean if a field has been set.

### SetGoalNil

`func (o *BudgetKategorie) SetGoalNil(b bool)`

 SetGoalNil sets the value for Goal to be an explicit nil

### UnsetGoal
`func (o *BudgetKategorie) UnsetGoal()`

UnsetGoal ensures that no value is present for Goal, not even an explicit nil
### GetIst

`func (o *BudgetKategorie) GetIst() string`

GetIst returns the Ist field if non-nil, zero value otherwise.

### GetIstOk

`func (o *BudgetKategorie) GetIstOk() (*string, bool)`

GetIstOk returns a tuple with the Ist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIst

`func (o *BudgetKategorie) SetIst(v string)`

SetIst sets Ist field to given value.


### GetKategorie

`func (o *BudgetKategorie) GetKategorie() string`

GetKategorie returns the Kategorie field if non-nil, zero value otherwise.

### GetKategorieOk

`func (o *BudgetKategorie) GetKategorieOk() (*string, bool)`

GetKategorieOk returns a tuple with the Kategorie field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKategorie

`func (o *BudgetKategorie) SetKategorie(v string)`

SetKategorie sets Kategorie field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


