# BudgetErgebnis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Jahr** | **int32** |  | 
**Monat** | **int32** |  | 
**MonatsBudget** | [**[]BudgetKategorie**](BudgetKategorie.md) |  | 
**PrognoseRestjahr** | [**[]BudgetKategorie**](BudgetKategorie.md) |  | 

## Methods

### NewBudgetErgebnis

`func NewBudgetErgebnis(jahr int32, monat int32, monatsBudget []BudgetKategorie, prognoseRestjahr []BudgetKategorie, ) *BudgetErgebnis`

NewBudgetErgebnis instantiates a new BudgetErgebnis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetErgebnisWithDefaults

`func NewBudgetErgebnisWithDefaults() *BudgetErgebnis`

NewBudgetErgebnisWithDefaults instantiates a new BudgetErgebnis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJahr

`func (o *BudgetErgebnis) GetJahr() int32`

GetJahr returns the Jahr field if non-nil, zero value otherwise.

### GetJahrOk

`func (o *BudgetErgebnis) GetJahrOk() (*int32, bool)`

GetJahrOk returns a tuple with the Jahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahr

`func (o *BudgetErgebnis) SetJahr(v int32)`

SetJahr sets Jahr field to given value.


### GetMonat

`func (o *BudgetErgebnis) GetMonat() int32`

GetMonat returns the Monat field if non-nil, zero value otherwise.

### GetMonatOk

`func (o *BudgetErgebnis) GetMonatOk() (*int32, bool)`

GetMonatOk returns a tuple with the Monat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonat

`func (o *BudgetErgebnis) SetMonat(v int32)`

SetMonat sets Monat field to given value.


### GetMonatsBudget

`func (o *BudgetErgebnis) GetMonatsBudget() []BudgetKategorie`

GetMonatsBudget returns the MonatsBudget field if non-nil, zero value otherwise.

### GetMonatsBudgetOk

`func (o *BudgetErgebnis) GetMonatsBudgetOk() (*[]BudgetKategorie, bool)`

GetMonatsBudgetOk returns a tuple with the MonatsBudget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonatsBudget

`func (o *BudgetErgebnis) SetMonatsBudget(v []BudgetKategorie)`

SetMonatsBudget sets MonatsBudget field to given value.


### GetPrognoseRestjahr

`func (o *BudgetErgebnis) GetPrognoseRestjahr() []BudgetKategorie`

GetPrognoseRestjahr returns the PrognoseRestjahr field if non-nil, zero value otherwise.

### GetPrognoseRestjahrOk

`func (o *BudgetErgebnis) GetPrognoseRestjahrOk() (*[]BudgetKategorie, bool)`

GetPrognoseRestjahrOk returns a tuple with the PrognoseRestjahr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrognoseRestjahr

`func (o *BudgetErgebnis) SetPrognoseRestjahr(v []BudgetKategorie)`

SetPrognoseRestjahr sets PrognoseRestjahr field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


