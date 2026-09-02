# InvoiceCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attachments** | Pointer to **interface{}** |  | [optional] 
**BillingPeriodEnd** | Pointer to **NullableString** |  | [optional] 
**BillingPeriodStart** | Pointer to **NullableString** |  | [optional] 
**CancellationDate** | Pointer to **NullableString** |  | [optional] 
**CancellationInvoiceId** | Pointer to **NullableString** | References the invoice entity. | [optional] 
**CancellationReason** | Pointer to **NullableString** |  | [optional] 
**ContractId** | Pointer to **NullableString** | References the contract entity. | [optional] 
**Currency** | [**CurrencyCode**](CurrencyCode.md) |  | 
**CustomerId** | Pointer to **NullableString** | References the customer entity. | [optional] 
**DiscountAmount** | Pointer to **NullableString** |  | [optional] 
**DiscountDays** | Pointer to **NullableInt32** |  | [optional] 
**DiscountPercentage** | Pointer to **NullableString** |  | [optional] 
**DocumentType** | Pointer to [**DocumentType**](DocumentType.md) |  | [optional] 
**DunningLevel** | Pointer to **int32** |  | [optional] 
**InputVatAmount** | Pointer to **NullableString** |  | [optional] 
**InputVatDeductible** | Pointer to **bool** |  | [optional] 
**InputVatPercentage** | Pointer to **NullableString** |  | [optional] 
**IntroductionText** | Pointer to **NullableString** |  | [optional] 
**InvoiceType** | [**InvoiceType**](InvoiceType.md) |  | 
**IsCancelled** | Pointer to **bool** |  | [optional] 
**IsDraft** | Pointer to **bool** |  | [optional] 
**IsEuAcquisition** | Pointer to **bool** |  | [optional] 
**IsEuDelivery** | Pointer to **bool** |  | [optional] 
**IsIntraCommunityAcquisition** | Pointer to **bool** |  | [optional] 
**IsReverseCharge** | Pointer to **bool** |  | [optional] 
**IssueDate** | **string** |  | 
**LedgerAccount** | Pointer to **NullableString** |  | [optional] 
**LineItems** | **interface{}** |  | 
**Margin25a** | Pointer to **bool** |  | [optional] 
**Margin25aGross** | Pointer to **NullableString** |  | [optional] 
**Margin25aPurchasePrice** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OrderNumber** | Pointer to **NullableString** |  | [optional] 
**OriginalPdfPath** | Pointer to **NullableString** |  | [optional] 
**PaidAmount** | Pointer to **string** |  | [optional] 
**PaymentDueDate** | Pointer to **NullableString** |  | [optional] 
**PaymentStatus** | Pointer to [**PaymentStatus**](PaymentStatus.md) |  | [optional] 
**PaymentTermsText** | Pointer to **NullableString** |  | [optional] 
**PrecedingSalesVoucherId** | Pointer to **NullableString** | References the preceding sales voucher entity. | [optional] 
**PrecedingSalesVoucherType** | Pointer to [**NullablePrecedingSalesVoucherType**](PrecedingSalesVoucherType.md) |  | [optional] 
**ReceiptConfirmationAvailable** | Pointer to **bool** |  | [optional] 
**RelatedInvoiceId** | Pointer to **NullableString** | References the invoice entity. | [optional] 
**RelationshipType** | Pointer to **NullableString** |  | [optional] 
**SenderSnapshot** | Pointer to **interface{}** |  | [optional] 
**SentAt** | Pointer to **NullableTime** |  | [optional] 
**ServicePeriodEnd** | Pointer to **NullableString** |  | [optional] 
**ServicePeriodStart** | Pointer to **NullableString** |  | [optional] 
**Status** | [**InvoiceStatus**](InvoiceStatus.md) |  | 
**Subtotal** | **string** |  | 
**SupplierId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**TaxExemptionReason** | Pointer to **NullableString** |  | [optional] 
**TotalAmount** | **string** |  | 
**TotalTax** | **string** |  | 
**VatCountry** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**VatSpecialCase** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewInvoiceCreate

`func NewInvoiceCreate(currency CurrencyCode, invoiceType InvoiceType, issueDate string, lineItems interface{}, status InvoiceStatus, subtotal string, totalAmount string, totalTax string, ) *InvoiceCreate`

NewInvoiceCreate instantiates a new InvoiceCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceCreateWithDefaults

`func NewInvoiceCreateWithDefaults() *InvoiceCreate`

NewInvoiceCreateWithDefaults instantiates a new InvoiceCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachments

`func (o *InvoiceCreate) GetAttachments() interface{}`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *InvoiceCreate) GetAttachmentsOk() (*interface{}, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *InvoiceCreate) SetAttachments(v interface{})`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *InvoiceCreate) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### SetAttachmentsNil

`func (o *InvoiceCreate) SetAttachmentsNil(b bool)`

 SetAttachmentsNil sets the value for Attachments to be an explicit nil

### UnsetAttachments
`func (o *InvoiceCreate) UnsetAttachments()`

UnsetAttachments ensures that no value is present for Attachments, not even an explicit nil
### GetBillingPeriodEnd

`func (o *InvoiceCreate) GetBillingPeriodEnd() string`

GetBillingPeriodEnd returns the BillingPeriodEnd field if non-nil, zero value otherwise.

### GetBillingPeriodEndOk

`func (o *InvoiceCreate) GetBillingPeriodEndOk() (*string, bool)`

GetBillingPeriodEndOk returns a tuple with the BillingPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriodEnd

`func (o *InvoiceCreate) SetBillingPeriodEnd(v string)`

SetBillingPeriodEnd sets BillingPeriodEnd field to given value.

### HasBillingPeriodEnd

`func (o *InvoiceCreate) HasBillingPeriodEnd() bool`

HasBillingPeriodEnd returns a boolean if a field has been set.

### SetBillingPeriodEndNil

`func (o *InvoiceCreate) SetBillingPeriodEndNil(b bool)`

 SetBillingPeriodEndNil sets the value for BillingPeriodEnd to be an explicit nil

### UnsetBillingPeriodEnd
`func (o *InvoiceCreate) UnsetBillingPeriodEnd()`

UnsetBillingPeriodEnd ensures that no value is present for BillingPeriodEnd, not even an explicit nil
### GetBillingPeriodStart

`func (o *InvoiceCreate) GetBillingPeriodStart() string`

GetBillingPeriodStart returns the BillingPeriodStart field if non-nil, zero value otherwise.

### GetBillingPeriodStartOk

`func (o *InvoiceCreate) GetBillingPeriodStartOk() (*string, bool)`

GetBillingPeriodStartOk returns a tuple with the BillingPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriodStart

`func (o *InvoiceCreate) SetBillingPeriodStart(v string)`

SetBillingPeriodStart sets BillingPeriodStart field to given value.

### HasBillingPeriodStart

`func (o *InvoiceCreate) HasBillingPeriodStart() bool`

HasBillingPeriodStart returns a boolean if a field has been set.

### SetBillingPeriodStartNil

`func (o *InvoiceCreate) SetBillingPeriodStartNil(b bool)`

 SetBillingPeriodStartNil sets the value for BillingPeriodStart to be an explicit nil

### UnsetBillingPeriodStart
`func (o *InvoiceCreate) UnsetBillingPeriodStart()`

UnsetBillingPeriodStart ensures that no value is present for BillingPeriodStart, not even an explicit nil
### GetCancellationDate

`func (o *InvoiceCreate) GetCancellationDate() string`

GetCancellationDate returns the CancellationDate field if non-nil, zero value otherwise.

### GetCancellationDateOk

`func (o *InvoiceCreate) GetCancellationDateOk() (*string, bool)`

GetCancellationDateOk returns a tuple with the CancellationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationDate

`func (o *InvoiceCreate) SetCancellationDate(v string)`

SetCancellationDate sets CancellationDate field to given value.

### HasCancellationDate

`func (o *InvoiceCreate) HasCancellationDate() bool`

HasCancellationDate returns a boolean if a field has been set.

### SetCancellationDateNil

`func (o *InvoiceCreate) SetCancellationDateNil(b bool)`

 SetCancellationDateNil sets the value for CancellationDate to be an explicit nil

### UnsetCancellationDate
`func (o *InvoiceCreate) UnsetCancellationDate()`

UnsetCancellationDate ensures that no value is present for CancellationDate, not even an explicit nil
### GetCancellationInvoiceId

`func (o *InvoiceCreate) GetCancellationInvoiceId() string`

GetCancellationInvoiceId returns the CancellationInvoiceId field if non-nil, zero value otherwise.

### GetCancellationInvoiceIdOk

`func (o *InvoiceCreate) GetCancellationInvoiceIdOk() (*string, bool)`

GetCancellationInvoiceIdOk returns a tuple with the CancellationInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationInvoiceId

`func (o *InvoiceCreate) SetCancellationInvoiceId(v string)`

SetCancellationInvoiceId sets CancellationInvoiceId field to given value.

### HasCancellationInvoiceId

`func (o *InvoiceCreate) HasCancellationInvoiceId() bool`

HasCancellationInvoiceId returns a boolean if a field has been set.

### SetCancellationInvoiceIdNil

`func (o *InvoiceCreate) SetCancellationInvoiceIdNil(b bool)`

 SetCancellationInvoiceIdNil sets the value for CancellationInvoiceId to be an explicit nil

### UnsetCancellationInvoiceId
`func (o *InvoiceCreate) UnsetCancellationInvoiceId()`

UnsetCancellationInvoiceId ensures that no value is present for CancellationInvoiceId, not even an explicit nil
### GetCancellationReason

`func (o *InvoiceCreate) GetCancellationReason() string`

GetCancellationReason returns the CancellationReason field if non-nil, zero value otherwise.

### GetCancellationReasonOk

`func (o *InvoiceCreate) GetCancellationReasonOk() (*string, bool)`

GetCancellationReasonOk returns a tuple with the CancellationReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationReason

`func (o *InvoiceCreate) SetCancellationReason(v string)`

SetCancellationReason sets CancellationReason field to given value.

### HasCancellationReason

`func (o *InvoiceCreate) HasCancellationReason() bool`

HasCancellationReason returns a boolean if a field has been set.

### SetCancellationReasonNil

`func (o *InvoiceCreate) SetCancellationReasonNil(b bool)`

 SetCancellationReasonNil sets the value for CancellationReason to be an explicit nil

### UnsetCancellationReason
`func (o *InvoiceCreate) UnsetCancellationReason()`

UnsetCancellationReason ensures that no value is present for CancellationReason, not even an explicit nil
### GetContractId

`func (o *InvoiceCreate) GetContractId() string`

GetContractId returns the ContractId field if non-nil, zero value otherwise.

### GetContractIdOk

`func (o *InvoiceCreate) GetContractIdOk() (*string, bool)`

GetContractIdOk returns a tuple with the ContractId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractId

`func (o *InvoiceCreate) SetContractId(v string)`

SetContractId sets ContractId field to given value.

### HasContractId

`func (o *InvoiceCreate) HasContractId() bool`

HasContractId returns a boolean if a field has been set.

### SetContractIdNil

`func (o *InvoiceCreate) SetContractIdNil(b bool)`

 SetContractIdNil sets the value for ContractId to be an explicit nil

### UnsetContractId
`func (o *InvoiceCreate) UnsetContractId()`

UnsetContractId ensures that no value is present for ContractId, not even an explicit nil
### GetCurrency

`func (o *InvoiceCreate) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *InvoiceCreate) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *InvoiceCreate) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *InvoiceCreate) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *InvoiceCreate) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *InvoiceCreate) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *InvoiceCreate) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *InvoiceCreate) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *InvoiceCreate) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetDiscountAmount

`func (o *InvoiceCreate) GetDiscountAmount() string`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *InvoiceCreate) GetDiscountAmountOk() (*string, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *InvoiceCreate) SetDiscountAmount(v string)`

SetDiscountAmount sets DiscountAmount field to given value.

### HasDiscountAmount

`func (o *InvoiceCreate) HasDiscountAmount() bool`

HasDiscountAmount returns a boolean if a field has been set.

### SetDiscountAmountNil

`func (o *InvoiceCreate) SetDiscountAmountNil(b bool)`

 SetDiscountAmountNil sets the value for DiscountAmount to be an explicit nil

### UnsetDiscountAmount
`func (o *InvoiceCreate) UnsetDiscountAmount()`

UnsetDiscountAmount ensures that no value is present for DiscountAmount, not even an explicit nil
### GetDiscountDays

`func (o *InvoiceCreate) GetDiscountDays() int32`

GetDiscountDays returns the DiscountDays field if non-nil, zero value otherwise.

### GetDiscountDaysOk

`func (o *InvoiceCreate) GetDiscountDaysOk() (*int32, bool)`

GetDiscountDaysOk returns a tuple with the DiscountDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDays

`func (o *InvoiceCreate) SetDiscountDays(v int32)`

SetDiscountDays sets DiscountDays field to given value.

### HasDiscountDays

`func (o *InvoiceCreate) HasDiscountDays() bool`

HasDiscountDays returns a boolean if a field has been set.

### SetDiscountDaysNil

`func (o *InvoiceCreate) SetDiscountDaysNil(b bool)`

 SetDiscountDaysNil sets the value for DiscountDays to be an explicit nil

### UnsetDiscountDays
`func (o *InvoiceCreate) UnsetDiscountDays()`

UnsetDiscountDays ensures that no value is present for DiscountDays, not even an explicit nil
### GetDiscountPercentage

`func (o *InvoiceCreate) GetDiscountPercentage() string`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *InvoiceCreate) GetDiscountPercentageOk() (*string, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *InvoiceCreate) SetDiscountPercentage(v string)`

SetDiscountPercentage sets DiscountPercentage field to given value.

### HasDiscountPercentage

`func (o *InvoiceCreate) HasDiscountPercentage() bool`

HasDiscountPercentage returns a boolean if a field has been set.

### SetDiscountPercentageNil

`func (o *InvoiceCreate) SetDiscountPercentageNil(b bool)`

 SetDiscountPercentageNil sets the value for DiscountPercentage to be an explicit nil

### UnsetDiscountPercentage
`func (o *InvoiceCreate) UnsetDiscountPercentage()`

UnsetDiscountPercentage ensures that no value is present for DiscountPercentage, not even an explicit nil
### GetDocumentType

`func (o *InvoiceCreate) GetDocumentType() DocumentType`

GetDocumentType returns the DocumentType field if non-nil, zero value otherwise.

### GetDocumentTypeOk

`func (o *InvoiceCreate) GetDocumentTypeOk() (*DocumentType, bool)`

GetDocumentTypeOk returns a tuple with the DocumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentType

`func (o *InvoiceCreate) SetDocumentType(v DocumentType)`

SetDocumentType sets DocumentType field to given value.

### HasDocumentType

`func (o *InvoiceCreate) HasDocumentType() bool`

HasDocumentType returns a boolean if a field has been set.

### GetDunningLevel

`func (o *InvoiceCreate) GetDunningLevel() int32`

GetDunningLevel returns the DunningLevel field if non-nil, zero value otherwise.

### GetDunningLevelOk

`func (o *InvoiceCreate) GetDunningLevelOk() (*int32, bool)`

GetDunningLevelOk returns a tuple with the DunningLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunningLevel

`func (o *InvoiceCreate) SetDunningLevel(v int32)`

SetDunningLevel sets DunningLevel field to given value.

### HasDunningLevel

`func (o *InvoiceCreate) HasDunningLevel() bool`

HasDunningLevel returns a boolean if a field has been set.

### GetInputVatAmount

`func (o *InvoiceCreate) GetInputVatAmount() string`

GetInputVatAmount returns the InputVatAmount field if non-nil, zero value otherwise.

### GetInputVatAmountOk

`func (o *InvoiceCreate) GetInputVatAmountOk() (*string, bool)`

GetInputVatAmountOk returns a tuple with the InputVatAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatAmount

`func (o *InvoiceCreate) SetInputVatAmount(v string)`

SetInputVatAmount sets InputVatAmount field to given value.

### HasInputVatAmount

`func (o *InvoiceCreate) HasInputVatAmount() bool`

HasInputVatAmount returns a boolean if a field has been set.

### SetInputVatAmountNil

`func (o *InvoiceCreate) SetInputVatAmountNil(b bool)`

 SetInputVatAmountNil sets the value for InputVatAmount to be an explicit nil

### UnsetInputVatAmount
`func (o *InvoiceCreate) UnsetInputVatAmount()`

UnsetInputVatAmount ensures that no value is present for InputVatAmount, not even an explicit nil
### GetInputVatDeductible

`func (o *InvoiceCreate) GetInputVatDeductible() bool`

GetInputVatDeductible returns the InputVatDeductible field if non-nil, zero value otherwise.

### GetInputVatDeductibleOk

`func (o *InvoiceCreate) GetInputVatDeductibleOk() (*bool, bool)`

GetInputVatDeductibleOk returns a tuple with the InputVatDeductible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatDeductible

`func (o *InvoiceCreate) SetInputVatDeductible(v bool)`

SetInputVatDeductible sets InputVatDeductible field to given value.

### HasInputVatDeductible

`func (o *InvoiceCreate) HasInputVatDeductible() bool`

HasInputVatDeductible returns a boolean if a field has been set.

### GetInputVatPercentage

`func (o *InvoiceCreate) GetInputVatPercentage() string`

GetInputVatPercentage returns the InputVatPercentage field if non-nil, zero value otherwise.

### GetInputVatPercentageOk

`func (o *InvoiceCreate) GetInputVatPercentageOk() (*string, bool)`

GetInputVatPercentageOk returns a tuple with the InputVatPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatPercentage

`func (o *InvoiceCreate) SetInputVatPercentage(v string)`

SetInputVatPercentage sets InputVatPercentage field to given value.

### HasInputVatPercentage

`func (o *InvoiceCreate) HasInputVatPercentage() bool`

HasInputVatPercentage returns a boolean if a field has been set.

### SetInputVatPercentageNil

`func (o *InvoiceCreate) SetInputVatPercentageNil(b bool)`

 SetInputVatPercentageNil sets the value for InputVatPercentage to be an explicit nil

### UnsetInputVatPercentage
`func (o *InvoiceCreate) UnsetInputVatPercentage()`

UnsetInputVatPercentage ensures that no value is present for InputVatPercentage, not even an explicit nil
### GetIntroductionText

`func (o *InvoiceCreate) GetIntroductionText() string`

GetIntroductionText returns the IntroductionText field if non-nil, zero value otherwise.

### GetIntroductionTextOk

`func (o *InvoiceCreate) GetIntroductionTextOk() (*string, bool)`

GetIntroductionTextOk returns a tuple with the IntroductionText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroductionText

`func (o *InvoiceCreate) SetIntroductionText(v string)`

SetIntroductionText sets IntroductionText field to given value.

### HasIntroductionText

`func (o *InvoiceCreate) HasIntroductionText() bool`

HasIntroductionText returns a boolean if a field has been set.

### SetIntroductionTextNil

`func (o *InvoiceCreate) SetIntroductionTextNil(b bool)`

 SetIntroductionTextNil sets the value for IntroductionText to be an explicit nil

### UnsetIntroductionText
`func (o *InvoiceCreate) UnsetIntroductionText()`

UnsetIntroductionText ensures that no value is present for IntroductionText, not even an explicit nil
### GetInvoiceType

`func (o *InvoiceCreate) GetInvoiceType() InvoiceType`

GetInvoiceType returns the InvoiceType field if non-nil, zero value otherwise.

### GetInvoiceTypeOk

`func (o *InvoiceCreate) GetInvoiceTypeOk() (*InvoiceType, bool)`

GetInvoiceTypeOk returns a tuple with the InvoiceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceType

`func (o *InvoiceCreate) SetInvoiceType(v InvoiceType)`

SetInvoiceType sets InvoiceType field to given value.


### GetIsCancelled

`func (o *InvoiceCreate) GetIsCancelled() bool`

GetIsCancelled returns the IsCancelled field if non-nil, zero value otherwise.

### GetIsCancelledOk

`func (o *InvoiceCreate) GetIsCancelledOk() (*bool, bool)`

GetIsCancelledOk returns a tuple with the IsCancelled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCancelled

`func (o *InvoiceCreate) SetIsCancelled(v bool)`

SetIsCancelled sets IsCancelled field to given value.

### HasIsCancelled

`func (o *InvoiceCreate) HasIsCancelled() bool`

HasIsCancelled returns a boolean if a field has been set.

### GetIsDraft

`func (o *InvoiceCreate) GetIsDraft() bool`

GetIsDraft returns the IsDraft field if non-nil, zero value otherwise.

### GetIsDraftOk

`func (o *InvoiceCreate) GetIsDraftOk() (*bool, bool)`

GetIsDraftOk returns a tuple with the IsDraft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraft

`func (o *InvoiceCreate) SetIsDraft(v bool)`

SetIsDraft sets IsDraft field to given value.

### HasIsDraft

`func (o *InvoiceCreate) HasIsDraft() bool`

HasIsDraft returns a boolean if a field has been set.

### GetIsEuAcquisition

`func (o *InvoiceCreate) GetIsEuAcquisition() bool`

GetIsEuAcquisition returns the IsEuAcquisition field if non-nil, zero value otherwise.

### GetIsEuAcquisitionOk

`func (o *InvoiceCreate) GetIsEuAcquisitionOk() (*bool, bool)`

GetIsEuAcquisitionOk returns a tuple with the IsEuAcquisition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEuAcquisition

`func (o *InvoiceCreate) SetIsEuAcquisition(v bool)`

SetIsEuAcquisition sets IsEuAcquisition field to given value.

### HasIsEuAcquisition

`func (o *InvoiceCreate) HasIsEuAcquisition() bool`

HasIsEuAcquisition returns a boolean if a field has been set.

### GetIsEuDelivery

`func (o *InvoiceCreate) GetIsEuDelivery() bool`

GetIsEuDelivery returns the IsEuDelivery field if non-nil, zero value otherwise.

### GetIsEuDeliveryOk

`func (o *InvoiceCreate) GetIsEuDeliveryOk() (*bool, bool)`

GetIsEuDeliveryOk returns a tuple with the IsEuDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEuDelivery

`func (o *InvoiceCreate) SetIsEuDelivery(v bool)`

SetIsEuDelivery sets IsEuDelivery field to given value.

### HasIsEuDelivery

`func (o *InvoiceCreate) HasIsEuDelivery() bool`

HasIsEuDelivery returns a boolean if a field has been set.

### GetIsIntraCommunityAcquisition

`func (o *InvoiceCreate) GetIsIntraCommunityAcquisition() bool`

GetIsIntraCommunityAcquisition returns the IsIntraCommunityAcquisition field if non-nil, zero value otherwise.

### GetIsIntraCommunityAcquisitionOk

`func (o *InvoiceCreate) GetIsIntraCommunityAcquisitionOk() (*bool, bool)`

GetIsIntraCommunityAcquisitionOk returns a tuple with the IsIntraCommunityAcquisition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsIntraCommunityAcquisition

`func (o *InvoiceCreate) SetIsIntraCommunityAcquisition(v bool)`

SetIsIntraCommunityAcquisition sets IsIntraCommunityAcquisition field to given value.

### HasIsIntraCommunityAcquisition

`func (o *InvoiceCreate) HasIsIntraCommunityAcquisition() bool`

HasIsIntraCommunityAcquisition returns a boolean if a field has been set.

### GetIsReverseCharge

`func (o *InvoiceCreate) GetIsReverseCharge() bool`

GetIsReverseCharge returns the IsReverseCharge field if non-nil, zero value otherwise.

### GetIsReverseChargeOk

`func (o *InvoiceCreate) GetIsReverseChargeOk() (*bool, bool)`

GetIsReverseChargeOk returns a tuple with the IsReverseCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReverseCharge

`func (o *InvoiceCreate) SetIsReverseCharge(v bool)`

SetIsReverseCharge sets IsReverseCharge field to given value.

### HasIsReverseCharge

`func (o *InvoiceCreate) HasIsReverseCharge() bool`

HasIsReverseCharge returns a boolean if a field has been set.

### GetIssueDate

`func (o *InvoiceCreate) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *InvoiceCreate) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *InvoiceCreate) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.


### GetLedgerAccount

`func (o *InvoiceCreate) GetLedgerAccount() string`

GetLedgerAccount returns the LedgerAccount field if non-nil, zero value otherwise.

### GetLedgerAccountOk

`func (o *InvoiceCreate) GetLedgerAccountOk() (*string, bool)`

GetLedgerAccountOk returns a tuple with the LedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerAccount

`func (o *InvoiceCreate) SetLedgerAccount(v string)`

SetLedgerAccount sets LedgerAccount field to given value.

### HasLedgerAccount

`func (o *InvoiceCreate) HasLedgerAccount() bool`

HasLedgerAccount returns a boolean if a field has been set.

### SetLedgerAccountNil

`func (o *InvoiceCreate) SetLedgerAccountNil(b bool)`

 SetLedgerAccountNil sets the value for LedgerAccount to be an explicit nil

### UnsetLedgerAccount
`func (o *InvoiceCreate) UnsetLedgerAccount()`

UnsetLedgerAccount ensures that no value is present for LedgerAccount, not even an explicit nil
### GetLineItems

`func (o *InvoiceCreate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *InvoiceCreate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *InvoiceCreate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *InvoiceCreate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *InvoiceCreate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetMargin25a

`func (o *InvoiceCreate) GetMargin25a() bool`

GetMargin25a returns the Margin25a field if non-nil, zero value otherwise.

### GetMargin25aOk

`func (o *InvoiceCreate) GetMargin25aOk() (*bool, bool)`

GetMargin25aOk returns a tuple with the Margin25a field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25a

`func (o *InvoiceCreate) SetMargin25a(v bool)`

SetMargin25a sets Margin25a field to given value.

### HasMargin25a

`func (o *InvoiceCreate) HasMargin25a() bool`

HasMargin25a returns a boolean if a field has been set.

### GetMargin25aGross

`func (o *InvoiceCreate) GetMargin25aGross() string`

GetMargin25aGross returns the Margin25aGross field if non-nil, zero value otherwise.

### GetMargin25aGrossOk

`func (o *InvoiceCreate) GetMargin25aGrossOk() (*string, bool)`

GetMargin25aGrossOk returns a tuple with the Margin25aGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25aGross

`func (o *InvoiceCreate) SetMargin25aGross(v string)`

SetMargin25aGross sets Margin25aGross field to given value.

### HasMargin25aGross

`func (o *InvoiceCreate) HasMargin25aGross() bool`

HasMargin25aGross returns a boolean if a field has been set.

### SetMargin25aGrossNil

`func (o *InvoiceCreate) SetMargin25aGrossNil(b bool)`

 SetMargin25aGrossNil sets the value for Margin25aGross to be an explicit nil

### UnsetMargin25aGross
`func (o *InvoiceCreate) UnsetMargin25aGross()`

UnsetMargin25aGross ensures that no value is present for Margin25aGross, not even an explicit nil
### GetMargin25aPurchasePrice

`func (o *InvoiceCreate) GetMargin25aPurchasePrice() string`

GetMargin25aPurchasePrice returns the Margin25aPurchasePrice field if non-nil, zero value otherwise.

### GetMargin25aPurchasePriceOk

`func (o *InvoiceCreate) GetMargin25aPurchasePriceOk() (*string, bool)`

GetMargin25aPurchasePriceOk returns a tuple with the Margin25aPurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25aPurchasePrice

`func (o *InvoiceCreate) SetMargin25aPurchasePrice(v string)`

SetMargin25aPurchasePrice sets Margin25aPurchasePrice field to given value.

### HasMargin25aPurchasePrice

`func (o *InvoiceCreate) HasMargin25aPurchasePrice() bool`

HasMargin25aPurchasePrice returns a boolean if a field has been set.

### SetMargin25aPurchasePriceNil

`func (o *InvoiceCreate) SetMargin25aPurchasePriceNil(b bool)`

 SetMargin25aPurchasePriceNil sets the value for Margin25aPurchasePrice to be an explicit nil

### UnsetMargin25aPurchasePrice
`func (o *InvoiceCreate) UnsetMargin25aPurchasePrice()`

UnsetMargin25aPurchasePrice ensures that no value is present for Margin25aPurchasePrice, not even an explicit nil
### GetNotes

`func (o *InvoiceCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *InvoiceCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *InvoiceCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *InvoiceCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *InvoiceCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *InvoiceCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *InvoiceCreate) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *InvoiceCreate) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *InvoiceCreate) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *InvoiceCreate) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *InvoiceCreate) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *InvoiceCreate) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetOriginalPdfPath

`func (o *InvoiceCreate) GetOriginalPdfPath() string`

GetOriginalPdfPath returns the OriginalPdfPath field if non-nil, zero value otherwise.

### GetOriginalPdfPathOk

`func (o *InvoiceCreate) GetOriginalPdfPathOk() (*string, bool)`

GetOriginalPdfPathOk returns a tuple with the OriginalPdfPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPdfPath

`func (o *InvoiceCreate) SetOriginalPdfPath(v string)`

SetOriginalPdfPath sets OriginalPdfPath field to given value.

### HasOriginalPdfPath

`func (o *InvoiceCreate) HasOriginalPdfPath() bool`

HasOriginalPdfPath returns a boolean if a field has been set.

### SetOriginalPdfPathNil

`func (o *InvoiceCreate) SetOriginalPdfPathNil(b bool)`

 SetOriginalPdfPathNil sets the value for OriginalPdfPath to be an explicit nil

### UnsetOriginalPdfPath
`func (o *InvoiceCreate) UnsetOriginalPdfPath()`

UnsetOriginalPdfPath ensures that no value is present for OriginalPdfPath, not even an explicit nil
### GetPaidAmount

`func (o *InvoiceCreate) GetPaidAmount() string`

GetPaidAmount returns the PaidAmount field if non-nil, zero value otherwise.

### GetPaidAmountOk

`func (o *InvoiceCreate) GetPaidAmountOk() (*string, bool)`

GetPaidAmountOk returns a tuple with the PaidAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAmount

`func (o *InvoiceCreate) SetPaidAmount(v string)`

SetPaidAmount sets PaidAmount field to given value.

### HasPaidAmount

`func (o *InvoiceCreate) HasPaidAmount() bool`

HasPaidAmount returns a boolean if a field has been set.

### GetPaymentDueDate

`func (o *InvoiceCreate) GetPaymentDueDate() string`

GetPaymentDueDate returns the PaymentDueDate field if non-nil, zero value otherwise.

### GetPaymentDueDateOk

`func (o *InvoiceCreate) GetPaymentDueDateOk() (*string, bool)`

GetPaymentDueDateOk returns a tuple with the PaymentDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDate

`func (o *InvoiceCreate) SetPaymentDueDate(v string)`

SetPaymentDueDate sets PaymentDueDate field to given value.

### HasPaymentDueDate

`func (o *InvoiceCreate) HasPaymentDueDate() bool`

HasPaymentDueDate returns a boolean if a field has been set.

### SetPaymentDueDateNil

`func (o *InvoiceCreate) SetPaymentDueDateNil(b bool)`

 SetPaymentDueDateNil sets the value for PaymentDueDate to be an explicit nil

### UnsetPaymentDueDate
`func (o *InvoiceCreate) UnsetPaymentDueDate()`

UnsetPaymentDueDate ensures that no value is present for PaymentDueDate, not even an explicit nil
### GetPaymentStatus

`func (o *InvoiceCreate) GetPaymentStatus() PaymentStatus`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *InvoiceCreate) GetPaymentStatusOk() (*PaymentStatus, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *InvoiceCreate) SetPaymentStatus(v PaymentStatus)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *InvoiceCreate) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentTermsText

`func (o *InvoiceCreate) GetPaymentTermsText() string`

GetPaymentTermsText returns the PaymentTermsText field if non-nil, zero value otherwise.

### GetPaymentTermsTextOk

`func (o *InvoiceCreate) GetPaymentTermsTextOk() (*string, bool)`

GetPaymentTermsTextOk returns a tuple with the PaymentTermsText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTermsText

`func (o *InvoiceCreate) SetPaymentTermsText(v string)`

SetPaymentTermsText sets PaymentTermsText field to given value.

### HasPaymentTermsText

`func (o *InvoiceCreate) HasPaymentTermsText() bool`

HasPaymentTermsText returns a boolean if a field has been set.

### SetPaymentTermsTextNil

`func (o *InvoiceCreate) SetPaymentTermsTextNil(b bool)`

 SetPaymentTermsTextNil sets the value for PaymentTermsText to be an explicit nil

### UnsetPaymentTermsText
`func (o *InvoiceCreate) UnsetPaymentTermsText()`

UnsetPaymentTermsText ensures that no value is present for PaymentTermsText, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *InvoiceCreate) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *InvoiceCreate) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *InvoiceCreate) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *InvoiceCreate) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *InvoiceCreate) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *InvoiceCreate) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *InvoiceCreate) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *InvoiceCreate) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *InvoiceCreate) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *InvoiceCreate) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *InvoiceCreate) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *InvoiceCreate) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetReceiptConfirmationAvailable

`func (o *InvoiceCreate) GetReceiptConfirmationAvailable() bool`

GetReceiptConfirmationAvailable returns the ReceiptConfirmationAvailable field if non-nil, zero value otherwise.

### GetReceiptConfirmationAvailableOk

`func (o *InvoiceCreate) GetReceiptConfirmationAvailableOk() (*bool, bool)`

GetReceiptConfirmationAvailableOk returns a tuple with the ReceiptConfirmationAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptConfirmationAvailable

`func (o *InvoiceCreate) SetReceiptConfirmationAvailable(v bool)`

SetReceiptConfirmationAvailable sets ReceiptConfirmationAvailable field to given value.

### HasReceiptConfirmationAvailable

`func (o *InvoiceCreate) HasReceiptConfirmationAvailable() bool`

HasReceiptConfirmationAvailable returns a boolean if a field has been set.

### GetRelatedInvoiceId

`func (o *InvoiceCreate) GetRelatedInvoiceId() string`

GetRelatedInvoiceId returns the RelatedInvoiceId field if non-nil, zero value otherwise.

### GetRelatedInvoiceIdOk

`func (o *InvoiceCreate) GetRelatedInvoiceIdOk() (*string, bool)`

GetRelatedInvoiceIdOk returns a tuple with the RelatedInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedInvoiceId

`func (o *InvoiceCreate) SetRelatedInvoiceId(v string)`

SetRelatedInvoiceId sets RelatedInvoiceId field to given value.

### HasRelatedInvoiceId

`func (o *InvoiceCreate) HasRelatedInvoiceId() bool`

HasRelatedInvoiceId returns a boolean if a field has been set.

### SetRelatedInvoiceIdNil

`func (o *InvoiceCreate) SetRelatedInvoiceIdNil(b bool)`

 SetRelatedInvoiceIdNil sets the value for RelatedInvoiceId to be an explicit nil

### UnsetRelatedInvoiceId
`func (o *InvoiceCreate) UnsetRelatedInvoiceId()`

UnsetRelatedInvoiceId ensures that no value is present for RelatedInvoiceId, not even an explicit nil
### GetRelationshipType

`func (o *InvoiceCreate) GetRelationshipType() string`

GetRelationshipType returns the RelationshipType field if non-nil, zero value otherwise.

### GetRelationshipTypeOk

`func (o *InvoiceCreate) GetRelationshipTypeOk() (*string, bool)`

GetRelationshipTypeOk returns a tuple with the RelationshipType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelationshipType

`func (o *InvoiceCreate) SetRelationshipType(v string)`

SetRelationshipType sets RelationshipType field to given value.

### HasRelationshipType

`func (o *InvoiceCreate) HasRelationshipType() bool`

HasRelationshipType returns a boolean if a field has been set.

### SetRelationshipTypeNil

`func (o *InvoiceCreate) SetRelationshipTypeNil(b bool)`

 SetRelationshipTypeNil sets the value for RelationshipType to be an explicit nil

### UnsetRelationshipType
`func (o *InvoiceCreate) UnsetRelationshipType()`

UnsetRelationshipType ensures that no value is present for RelationshipType, not even an explicit nil
### GetSenderSnapshot

`func (o *InvoiceCreate) GetSenderSnapshot() interface{}`

GetSenderSnapshot returns the SenderSnapshot field if non-nil, zero value otherwise.

### GetSenderSnapshotOk

`func (o *InvoiceCreate) GetSenderSnapshotOk() (*interface{}, bool)`

GetSenderSnapshotOk returns a tuple with the SenderSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderSnapshot

`func (o *InvoiceCreate) SetSenderSnapshot(v interface{})`

SetSenderSnapshot sets SenderSnapshot field to given value.

### HasSenderSnapshot

`func (o *InvoiceCreate) HasSenderSnapshot() bool`

HasSenderSnapshot returns a boolean if a field has been set.

### SetSenderSnapshotNil

`func (o *InvoiceCreate) SetSenderSnapshotNil(b bool)`

 SetSenderSnapshotNil sets the value for SenderSnapshot to be an explicit nil

### UnsetSenderSnapshot
`func (o *InvoiceCreate) UnsetSenderSnapshot()`

UnsetSenderSnapshot ensures that no value is present for SenderSnapshot, not even an explicit nil
### GetSentAt

`func (o *InvoiceCreate) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *InvoiceCreate) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *InvoiceCreate) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *InvoiceCreate) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *InvoiceCreate) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *InvoiceCreate) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetServicePeriodEnd

`func (o *InvoiceCreate) GetServicePeriodEnd() string`

GetServicePeriodEnd returns the ServicePeriodEnd field if non-nil, zero value otherwise.

### GetServicePeriodEndOk

`func (o *InvoiceCreate) GetServicePeriodEndOk() (*string, bool)`

GetServicePeriodEndOk returns a tuple with the ServicePeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePeriodEnd

`func (o *InvoiceCreate) SetServicePeriodEnd(v string)`

SetServicePeriodEnd sets ServicePeriodEnd field to given value.

### HasServicePeriodEnd

`func (o *InvoiceCreate) HasServicePeriodEnd() bool`

HasServicePeriodEnd returns a boolean if a field has been set.

### SetServicePeriodEndNil

`func (o *InvoiceCreate) SetServicePeriodEndNil(b bool)`

 SetServicePeriodEndNil sets the value for ServicePeriodEnd to be an explicit nil

### UnsetServicePeriodEnd
`func (o *InvoiceCreate) UnsetServicePeriodEnd()`

UnsetServicePeriodEnd ensures that no value is present for ServicePeriodEnd, not even an explicit nil
### GetServicePeriodStart

`func (o *InvoiceCreate) GetServicePeriodStart() string`

GetServicePeriodStart returns the ServicePeriodStart field if non-nil, zero value otherwise.

### GetServicePeriodStartOk

`func (o *InvoiceCreate) GetServicePeriodStartOk() (*string, bool)`

GetServicePeriodStartOk returns a tuple with the ServicePeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePeriodStart

`func (o *InvoiceCreate) SetServicePeriodStart(v string)`

SetServicePeriodStart sets ServicePeriodStart field to given value.

### HasServicePeriodStart

`func (o *InvoiceCreate) HasServicePeriodStart() bool`

HasServicePeriodStart returns a boolean if a field has been set.

### SetServicePeriodStartNil

`func (o *InvoiceCreate) SetServicePeriodStartNil(b bool)`

 SetServicePeriodStartNil sets the value for ServicePeriodStart to be an explicit nil

### UnsetServicePeriodStart
`func (o *InvoiceCreate) UnsetServicePeriodStart()`

UnsetServicePeriodStart ensures that no value is present for ServicePeriodStart, not even an explicit nil
### GetStatus

`func (o *InvoiceCreate) GetStatus() InvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InvoiceCreate) GetStatusOk() (*InvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InvoiceCreate) SetStatus(v InvoiceStatus)`

SetStatus sets Status field to given value.


### GetSubtotal

`func (o *InvoiceCreate) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *InvoiceCreate) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *InvoiceCreate) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.


### GetSupplierId

`func (o *InvoiceCreate) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *InvoiceCreate) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *InvoiceCreate) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *InvoiceCreate) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### SetSupplierIdNil

`func (o *InvoiceCreate) SetSupplierIdNil(b bool)`

 SetSupplierIdNil sets the value for SupplierId to be an explicit nil

### UnsetSupplierId
`func (o *InvoiceCreate) UnsetSupplierId()`

UnsetSupplierId ensures that no value is present for SupplierId, not even an explicit nil
### GetTaxExemptionReason

`func (o *InvoiceCreate) GetTaxExemptionReason() string`

GetTaxExemptionReason returns the TaxExemptionReason field if non-nil, zero value otherwise.

### GetTaxExemptionReasonOk

`func (o *InvoiceCreate) GetTaxExemptionReasonOk() (*string, bool)`

GetTaxExemptionReasonOk returns a tuple with the TaxExemptionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxExemptionReason

`func (o *InvoiceCreate) SetTaxExemptionReason(v string)`

SetTaxExemptionReason sets TaxExemptionReason field to given value.

### HasTaxExemptionReason

`func (o *InvoiceCreate) HasTaxExemptionReason() bool`

HasTaxExemptionReason returns a boolean if a field has been set.

### SetTaxExemptionReasonNil

`func (o *InvoiceCreate) SetTaxExemptionReasonNil(b bool)`

 SetTaxExemptionReasonNil sets the value for TaxExemptionReason to be an explicit nil

### UnsetTaxExemptionReason
`func (o *InvoiceCreate) UnsetTaxExemptionReason()`

UnsetTaxExemptionReason ensures that no value is present for TaxExemptionReason, not even an explicit nil
### GetTotalAmount

`func (o *InvoiceCreate) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *InvoiceCreate) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *InvoiceCreate) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetTotalTax

`func (o *InvoiceCreate) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *InvoiceCreate) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *InvoiceCreate) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.


### GetVatCountry

`func (o *InvoiceCreate) GetVatCountry() CountryCode`

GetVatCountry returns the VatCountry field if non-nil, zero value otherwise.

### GetVatCountryOk

`func (o *InvoiceCreate) GetVatCountryOk() (*CountryCode, bool)`

GetVatCountryOk returns a tuple with the VatCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatCountry

`func (o *InvoiceCreate) SetVatCountry(v CountryCode)`

SetVatCountry sets VatCountry field to given value.

### HasVatCountry

`func (o *InvoiceCreate) HasVatCountry() bool`

HasVatCountry returns a boolean if a field has been set.

### SetVatCountryNil

`func (o *InvoiceCreate) SetVatCountryNil(b bool)`

 SetVatCountryNil sets the value for VatCountry to be an explicit nil

### UnsetVatCountry
`func (o *InvoiceCreate) UnsetVatCountry()`

UnsetVatCountry ensures that no value is present for VatCountry, not even an explicit nil
### GetVatSpecialCase

`func (o *InvoiceCreate) GetVatSpecialCase() string`

GetVatSpecialCase returns the VatSpecialCase field if non-nil, zero value otherwise.

### GetVatSpecialCaseOk

`func (o *InvoiceCreate) GetVatSpecialCaseOk() (*string, bool)`

GetVatSpecialCaseOk returns a tuple with the VatSpecialCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatSpecialCase

`func (o *InvoiceCreate) SetVatSpecialCase(v string)`

SetVatSpecialCase sets VatSpecialCase field to given value.

### HasVatSpecialCase

`func (o *InvoiceCreate) HasVatSpecialCase() bool`

HasVatSpecialCase returns a boolean if a field has been set.

### SetVatSpecialCaseNil

`func (o *InvoiceCreate) SetVatSpecialCaseNil(b bool)`

 SetVatSpecialCaseNil sets the value for VatSpecialCase to be an explicit nil

### UnsetVatSpecialCase
`func (o *InvoiceCreate) UnsetVatSpecialCase()`

UnsetVatSpecialCase ensures that no value is present for VatSpecialCase, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


