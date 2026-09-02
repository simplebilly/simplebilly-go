# PayrollCreatePayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmployeeIds** | **[]string** |  | 
**ExtraPayments** | Pointer to [**[]ExtraPayment**](ExtraPayment.md) |  | [optional] 
**Month** | **int32** |  | 
**Year** | **int32** |  | 

## Methods

### NewPayrollCreatePayload

`func NewPayrollCreatePayload(employeeIds []string, month int32, year int32, ) *PayrollCreatePayload`

NewPayrollCreatePayload instantiates a new PayrollCreatePayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayrollCreatePayloadWithDefaults

`func NewPayrollCreatePayloadWithDefaults() *PayrollCreatePayload`

NewPayrollCreatePayloadWithDefaults instantiates a new PayrollCreatePayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmployeeIds

`func (o *PayrollCreatePayload) GetEmployeeIds() []string`

GetEmployeeIds returns the EmployeeIds field if non-nil, zero value otherwise.

### GetEmployeeIdsOk

`func (o *PayrollCreatePayload) GetEmployeeIdsOk() (*[]string, bool)`

GetEmployeeIdsOk returns a tuple with the EmployeeIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmployeeIds

`func (o *PayrollCreatePayload) SetEmployeeIds(v []string)`

SetEmployeeIds sets EmployeeIds field to given value.


### GetExtraPayments

`func (o *PayrollCreatePayload) GetExtraPayments() []ExtraPayment`

GetExtraPayments returns the ExtraPayments field if non-nil, zero value otherwise.

### GetExtraPaymentsOk

`func (o *PayrollCreatePayload) GetExtraPaymentsOk() (*[]ExtraPayment, bool)`

GetExtraPaymentsOk returns a tuple with the ExtraPayments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraPayments

`func (o *PayrollCreatePayload) SetExtraPayments(v []ExtraPayment)`

SetExtraPayments sets ExtraPayments field to given value.

### HasExtraPayments

`func (o *PayrollCreatePayload) HasExtraPayments() bool`

HasExtraPayments returns a boolean if a field has been set.

### SetExtraPaymentsNil

`func (o *PayrollCreatePayload) SetExtraPaymentsNil(b bool)`

 SetExtraPaymentsNil sets the value for ExtraPayments to be an explicit nil

### UnsetExtraPayments
`func (o *PayrollCreatePayload) UnsetExtraPayments()`

UnsetExtraPayments ensures that no value is present for ExtraPayments, not even an explicit nil
### GetMonth

`func (o *PayrollCreatePayload) GetMonth() int32`

GetMonth returns the Month field if non-nil, zero value otherwise.

### GetMonthOk

`func (o *PayrollCreatePayload) GetMonthOk() (*int32, bool)`

GetMonthOk returns a tuple with the Month field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonth

`func (o *PayrollCreatePayload) SetMonth(v int32)`

SetMonth sets Month field to given value.


### GetYear

`func (o *PayrollCreatePayload) GetYear() int32`

GetYear returns the Year field if non-nil, zero value otherwise.

### GetYearOk

`func (o *PayrollCreatePayload) GetYearOk() (*int32, bool)`

GetYearOk returns a tuple with the Year field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYear

`func (o *PayrollCreatePayload) SetYear(v int32)`

SetYear sets Year field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


