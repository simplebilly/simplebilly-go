# OpenItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AmountDue** | **string** |  | 
**AmountPaid** | **string** |  | 
**CustomerId** | Pointer to **NullableString** |  | [optional] 
**DaysOverdue** | Pointer to **NullableInt64** |  | [optional] 
**DueDate** | Pointer to **NullableString** |  | [optional] 
**InvoiceId** | **string** |  | 
**InvoiceNumber** | **string** |  | 
**IssueDate** | **string** |  | 
**OpenAmount** | **string** |  | 
**ReminderLevel** | [**ReminderLevel**](ReminderLevel.md) |  | 

## Methods

### NewOpenItem

`func NewOpenItem(amountDue string, amountPaid string, invoiceId string, invoiceNumber string, issueDate string, openAmount string, reminderLevel ReminderLevel, ) *OpenItem`

NewOpenItem instantiates a new OpenItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenItemWithDefaults

`func NewOpenItemWithDefaults() *OpenItem`

NewOpenItemWithDefaults instantiates a new OpenItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmountDue

`func (o *OpenItem) GetAmountDue() string`

GetAmountDue returns the AmountDue field if non-nil, zero value otherwise.

### GetAmountDueOk

`func (o *OpenItem) GetAmountDueOk() (*string, bool)`

GetAmountDueOk returns a tuple with the AmountDue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountDue

`func (o *OpenItem) SetAmountDue(v string)`

SetAmountDue sets AmountDue field to given value.


### GetAmountPaid

`func (o *OpenItem) GetAmountPaid() string`

GetAmountPaid returns the AmountPaid field if non-nil, zero value otherwise.

### GetAmountPaidOk

`func (o *OpenItem) GetAmountPaidOk() (*string, bool)`

GetAmountPaidOk returns a tuple with the AmountPaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountPaid

`func (o *OpenItem) SetAmountPaid(v string)`

SetAmountPaid sets AmountPaid field to given value.


### GetCustomerId

`func (o *OpenItem) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *OpenItem) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *OpenItem) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *OpenItem) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *OpenItem) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *OpenItem) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetDaysOverdue

`func (o *OpenItem) GetDaysOverdue() int64`

GetDaysOverdue returns the DaysOverdue field if non-nil, zero value otherwise.

### GetDaysOverdueOk

`func (o *OpenItem) GetDaysOverdueOk() (*int64, bool)`

GetDaysOverdueOk returns a tuple with the DaysOverdue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysOverdue

`func (o *OpenItem) SetDaysOverdue(v int64)`

SetDaysOverdue sets DaysOverdue field to given value.

### HasDaysOverdue

`func (o *OpenItem) HasDaysOverdue() bool`

HasDaysOverdue returns a boolean if a field has been set.

### SetDaysOverdueNil

`func (o *OpenItem) SetDaysOverdueNil(b bool)`

 SetDaysOverdueNil sets the value for DaysOverdue to be an explicit nil

### UnsetDaysOverdue
`func (o *OpenItem) UnsetDaysOverdue()`

UnsetDaysOverdue ensures that no value is present for DaysOverdue, not even an explicit nil
### GetDueDate

`func (o *OpenItem) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *OpenItem) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *OpenItem) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *OpenItem) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *OpenItem) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *OpenItem) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetInvoiceId

`func (o *OpenItem) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *OpenItem) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *OpenItem) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.


### GetInvoiceNumber

`func (o *OpenItem) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *OpenItem) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *OpenItem) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetIssueDate

`func (o *OpenItem) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *OpenItem) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *OpenItem) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.


### GetOpenAmount

`func (o *OpenItem) GetOpenAmount() string`

GetOpenAmount returns the OpenAmount field if non-nil, zero value otherwise.

### GetOpenAmountOk

`func (o *OpenItem) GetOpenAmountOk() (*string, bool)`

GetOpenAmountOk returns a tuple with the OpenAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAmount

`func (o *OpenItem) SetOpenAmount(v string)`

SetOpenAmount sets OpenAmount field to given value.


### GetReminderLevel

`func (o *OpenItem) GetReminderLevel() ReminderLevel`

GetReminderLevel returns the ReminderLevel field if non-nil, zero value otherwise.

### GetReminderLevelOk

`func (o *OpenItem) GetReminderLevelOk() (*ReminderLevel, bool)`

GetReminderLevelOk returns a tuple with the ReminderLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderLevel

`func (o *OpenItem) SetReminderLevel(v ReminderLevel)`

SetReminderLevel sets ReminderLevel field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


