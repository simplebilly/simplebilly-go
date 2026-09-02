# Invoice

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

### NewInvoice

`func NewInvoice(currency CurrencyCode, invoiceType InvoiceType, issueDate string, lineItems interface{}, status InvoiceStatus, subtotal string, totalAmount string, totalTax string, ) *Invoice`

NewInvoice instantiates a new Invoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceWithDefaults

`func NewInvoiceWithDefaults() *Invoice`

NewInvoiceWithDefaults instantiates a new Invoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachments

`func (o *Invoice) GetAttachments() interface{}`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *Invoice) GetAttachmentsOk() (*interface{}, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *Invoice) SetAttachments(v interface{})`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *Invoice) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### SetAttachmentsNil

`func (o *Invoice) SetAttachmentsNil(b bool)`

 SetAttachmentsNil sets the value for Attachments to be an explicit nil

### UnsetAttachments
`func (o *Invoice) UnsetAttachments()`

UnsetAttachments ensures that no value is present for Attachments, not even an explicit nil
### GetBillingPeriodEnd

`func (o *Invoice) GetBillingPeriodEnd() string`

GetBillingPeriodEnd returns the BillingPeriodEnd field if non-nil, zero value otherwise.

### GetBillingPeriodEndOk

`func (o *Invoice) GetBillingPeriodEndOk() (*string, bool)`

GetBillingPeriodEndOk returns a tuple with the BillingPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriodEnd

`func (o *Invoice) SetBillingPeriodEnd(v string)`

SetBillingPeriodEnd sets BillingPeriodEnd field to given value.

### HasBillingPeriodEnd

`func (o *Invoice) HasBillingPeriodEnd() bool`

HasBillingPeriodEnd returns a boolean if a field has been set.

### SetBillingPeriodEndNil

`func (o *Invoice) SetBillingPeriodEndNil(b bool)`

 SetBillingPeriodEndNil sets the value for BillingPeriodEnd to be an explicit nil

### UnsetBillingPeriodEnd
`func (o *Invoice) UnsetBillingPeriodEnd()`

UnsetBillingPeriodEnd ensures that no value is present for BillingPeriodEnd, not even an explicit nil
### GetBillingPeriodStart

`func (o *Invoice) GetBillingPeriodStart() string`

GetBillingPeriodStart returns the BillingPeriodStart field if non-nil, zero value otherwise.

### GetBillingPeriodStartOk

`func (o *Invoice) GetBillingPeriodStartOk() (*string, bool)`

GetBillingPeriodStartOk returns a tuple with the BillingPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriodStart

`func (o *Invoice) SetBillingPeriodStart(v string)`

SetBillingPeriodStart sets BillingPeriodStart field to given value.

### HasBillingPeriodStart

`func (o *Invoice) HasBillingPeriodStart() bool`

HasBillingPeriodStart returns a boolean if a field has been set.

### SetBillingPeriodStartNil

`func (o *Invoice) SetBillingPeriodStartNil(b bool)`

 SetBillingPeriodStartNil sets the value for BillingPeriodStart to be an explicit nil

### UnsetBillingPeriodStart
`func (o *Invoice) UnsetBillingPeriodStart()`

UnsetBillingPeriodStart ensures that no value is present for BillingPeriodStart, not even an explicit nil
### GetCancellationDate

`func (o *Invoice) GetCancellationDate() string`

GetCancellationDate returns the CancellationDate field if non-nil, zero value otherwise.

### GetCancellationDateOk

`func (o *Invoice) GetCancellationDateOk() (*string, bool)`

GetCancellationDateOk returns a tuple with the CancellationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationDate

`func (o *Invoice) SetCancellationDate(v string)`

SetCancellationDate sets CancellationDate field to given value.

### HasCancellationDate

`func (o *Invoice) HasCancellationDate() bool`

HasCancellationDate returns a boolean if a field has been set.

### SetCancellationDateNil

`func (o *Invoice) SetCancellationDateNil(b bool)`

 SetCancellationDateNil sets the value for CancellationDate to be an explicit nil

### UnsetCancellationDate
`func (o *Invoice) UnsetCancellationDate()`

UnsetCancellationDate ensures that no value is present for CancellationDate, not even an explicit nil
### GetCancellationInvoiceId

`func (o *Invoice) GetCancellationInvoiceId() string`

GetCancellationInvoiceId returns the CancellationInvoiceId field if non-nil, zero value otherwise.

### GetCancellationInvoiceIdOk

`func (o *Invoice) GetCancellationInvoiceIdOk() (*string, bool)`

GetCancellationInvoiceIdOk returns a tuple with the CancellationInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationInvoiceId

`func (o *Invoice) SetCancellationInvoiceId(v string)`

SetCancellationInvoiceId sets CancellationInvoiceId field to given value.

### HasCancellationInvoiceId

`func (o *Invoice) HasCancellationInvoiceId() bool`

HasCancellationInvoiceId returns a boolean if a field has been set.

### SetCancellationInvoiceIdNil

`func (o *Invoice) SetCancellationInvoiceIdNil(b bool)`

 SetCancellationInvoiceIdNil sets the value for CancellationInvoiceId to be an explicit nil

### UnsetCancellationInvoiceId
`func (o *Invoice) UnsetCancellationInvoiceId()`

UnsetCancellationInvoiceId ensures that no value is present for CancellationInvoiceId, not even an explicit nil
### GetCancellationReason

`func (o *Invoice) GetCancellationReason() string`

GetCancellationReason returns the CancellationReason field if non-nil, zero value otherwise.

### GetCancellationReasonOk

`func (o *Invoice) GetCancellationReasonOk() (*string, bool)`

GetCancellationReasonOk returns a tuple with the CancellationReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationReason

`func (o *Invoice) SetCancellationReason(v string)`

SetCancellationReason sets CancellationReason field to given value.

### HasCancellationReason

`func (o *Invoice) HasCancellationReason() bool`

HasCancellationReason returns a boolean if a field has been set.

### SetCancellationReasonNil

`func (o *Invoice) SetCancellationReasonNil(b bool)`

 SetCancellationReasonNil sets the value for CancellationReason to be an explicit nil

### UnsetCancellationReason
`func (o *Invoice) UnsetCancellationReason()`

UnsetCancellationReason ensures that no value is present for CancellationReason, not even an explicit nil
### GetContractId

`func (o *Invoice) GetContractId() string`

GetContractId returns the ContractId field if non-nil, zero value otherwise.

### GetContractIdOk

`func (o *Invoice) GetContractIdOk() (*string, bool)`

GetContractIdOk returns a tuple with the ContractId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractId

`func (o *Invoice) SetContractId(v string)`

SetContractId sets ContractId field to given value.

### HasContractId

`func (o *Invoice) HasContractId() bool`

HasContractId returns a boolean if a field has been set.

### SetContractIdNil

`func (o *Invoice) SetContractIdNil(b bool)`

 SetContractIdNil sets the value for ContractId to be an explicit nil

### UnsetContractId
`func (o *Invoice) UnsetContractId()`

UnsetContractId ensures that no value is present for ContractId, not even an explicit nil
### GetCurrency

`func (o *Invoice) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Invoice) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Invoice) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *Invoice) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *Invoice) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *Invoice) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *Invoice) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *Invoice) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *Invoice) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetDiscountAmount

`func (o *Invoice) GetDiscountAmount() string`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *Invoice) GetDiscountAmountOk() (*string, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *Invoice) SetDiscountAmount(v string)`

SetDiscountAmount sets DiscountAmount field to given value.

### HasDiscountAmount

`func (o *Invoice) HasDiscountAmount() bool`

HasDiscountAmount returns a boolean if a field has been set.

### SetDiscountAmountNil

`func (o *Invoice) SetDiscountAmountNil(b bool)`

 SetDiscountAmountNil sets the value for DiscountAmount to be an explicit nil

### UnsetDiscountAmount
`func (o *Invoice) UnsetDiscountAmount()`

UnsetDiscountAmount ensures that no value is present for DiscountAmount, not even an explicit nil
### GetDiscountDays

`func (o *Invoice) GetDiscountDays() int32`

GetDiscountDays returns the DiscountDays field if non-nil, zero value otherwise.

### GetDiscountDaysOk

`func (o *Invoice) GetDiscountDaysOk() (*int32, bool)`

GetDiscountDaysOk returns a tuple with the DiscountDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDays

`func (o *Invoice) SetDiscountDays(v int32)`

SetDiscountDays sets DiscountDays field to given value.

### HasDiscountDays

`func (o *Invoice) HasDiscountDays() bool`

HasDiscountDays returns a boolean if a field has been set.

### SetDiscountDaysNil

`func (o *Invoice) SetDiscountDaysNil(b bool)`

 SetDiscountDaysNil sets the value for DiscountDays to be an explicit nil

### UnsetDiscountDays
`func (o *Invoice) UnsetDiscountDays()`

UnsetDiscountDays ensures that no value is present for DiscountDays, not even an explicit nil
### GetDiscountPercentage

`func (o *Invoice) GetDiscountPercentage() string`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *Invoice) GetDiscountPercentageOk() (*string, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *Invoice) SetDiscountPercentage(v string)`

SetDiscountPercentage sets DiscountPercentage field to given value.

### HasDiscountPercentage

`func (o *Invoice) HasDiscountPercentage() bool`

HasDiscountPercentage returns a boolean if a field has been set.

### SetDiscountPercentageNil

`func (o *Invoice) SetDiscountPercentageNil(b bool)`

 SetDiscountPercentageNil sets the value for DiscountPercentage to be an explicit nil

### UnsetDiscountPercentage
`func (o *Invoice) UnsetDiscountPercentage()`

UnsetDiscountPercentage ensures that no value is present for DiscountPercentage, not even an explicit nil
### GetDocumentType

`func (o *Invoice) GetDocumentType() DocumentType`

GetDocumentType returns the DocumentType field if non-nil, zero value otherwise.

### GetDocumentTypeOk

`func (o *Invoice) GetDocumentTypeOk() (*DocumentType, bool)`

GetDocumentTypeOk returns a tuple with the DocumentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentType

`func (o *Invoice) SetDocumentType(v DocumentType)`

SetDocumentType sets DocumentType field to given value.

### HasDocumentType

`func (o *Invoice) HasDocumentType() bool`

HasDocumentType returns a boolean if a field has been set.

### GetDunningLevel

`func (o *Invoice) GetDunningLevel() int32`

GetDunningLevel returns the DunningLevel field if non-nil, zero value otherwise.

### GetDunningLevelOk

`func (o *Invoice) GetDunningLevelOk() (*int32, bool)`

GetDunningLevelOk returns a tuple with the DunningLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDunningLevel

`func (o *Invoice) SetDunningLevel(v int32)`

SetDunningLevel sets DunningLevel field to given value.

### HasDunningLevel

`func (o *Invoice) HasDunningLevel() bool`

HasDunningLevel returns a boolean if a field has been set.

### GetInputVatAmount

`func (o *Invoice) GetInputVatAmount() string`

GetInputVatAmount returns the InputVatAmount field if non-nil, zero value otherwise.

### GetInputVatAmountOk

`func (o *Invoice) GetInputVatAmountOk() (*string, bool)`

GetInputVatAmountOk returns a tuple with the InputVatAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatAmount

`func (o *Invoice) SetInputVatAmount(v string)`

SetInputVatAmount sets InputVatAmount field to given value.

### HasInputVatAmount

`func (o *Invoice) HasInputVatAmount() bool`

HasInputVatAmount returns a boolean if a field has been set.

### SetInputVatAmountNil

`func (o *Invoice) SetInputVatAmountNil(b bool)`

 SetInputVatAmountNil sets the value for InputVatAmount to be an explicit nil

### UnsetInputVatAmount
`func (o *Invoice) UnsetInputVatAmount()`

UnsetInputVatAmount ensures that no value is present for InputVatAmount, not even an explicit nil
### GetInputVatDeductible

`func (o *Invoice) GetInputVatDeductible() bool`

GetInputVatDeductible returns the InputVatDeductible field if non-nil, zero value otherwise.

### GetInputVatDeductibleOk

`func (o *Invoice) GetInputVatDeductibleOk() (*bool, bool)`

GetInputVatDeductibleOk returns a tuple with the InputVatDeductible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatDeductible

`func (o *Invoice) SetInputVatDeductible(v bool)`

SetInputVatDeductible sets InputVatDeductible field to given value.

### HasInputVatDeductible

`func (o *Invoice) HasInputVatDeductible() bool`

HasInputVatDeductible returns a boolean if a field has been set.

### GetInputVatPercentage

`func (o *Invoice) GetInputVatPercentage() string`

GetInputVatPercentage returns the InputVatPercentage field if non-nil, zero value otherwise.

### GetInputVatPercentageOk

`func (o *Invoice) GetInputVatPercentageOk() (*string, bool)`

GetInputVatPercentageOk returns a tuple with the InputVatPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatPercentage

`func (o *Invoice) SetInputVatPercentage(v string)`

SetInputVatPercentage sets InputVatPercentage field to given value.

### HasInputVatPercentage

`func (o *Invoice) HasInputVatPercentage() bool`

HasInputVatPercentage returns a boolean if a field has been set.

### SetInputVatPercentageNil

`func (o *Invoice) SetInputVatPercentageNil(b bool)`

 SetInputVatPercentageNil sets the value for InputVatPercentage to be an explicit nil

### UnsetInputVatPercentage
`func (o *Invoice) UnsetInputVatPercentage()`

UnsetInputVatPercentage ensures that no value is present for InputVatPercentage, not even an explicit nil
### GetIntroductionText

`func (o *Invoice) GetIntroductionText() string`

GetIntroductionText returns the IntroductionText field if non-nil, zero value otherwise.

### GetIntroductionTextOk

`func (o *Invoice) GetIntroductionTextOk() (*string, bool)`

GetIntroductionTextOk returns a tuple with the IntroductionText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroductionText

`func (o *Invoice) SetIntroductionText(v string)`

SetIntroductionText sets IntroductionText field to given value.

### HasIntroductionText

`func (o *Invoice) HasIntroductionText() bool`

HasIntroductionText returns a boolean if a field has been set.

### SetIntroductionTextNil

`func (o *Invoice) SetIntroductionTextNil(b bool)`

 SetIntroductionTextNil sets the value for IntroductionText to be an explicit nil

### UnsetIntroductionText
`func (o *Invoice) UnsetIntroductionText()`

UnsetIntroductionText ensures that no value is present for IntroductionText, not even an explicit nil
### GetInvoiceType

`func (o *Invoice) GetInvoiceType() InvoiceType`

GetInvoiceType returns the InvoiceType field if non-nil, zero value otherwise.

### GetInvoiceTypeOk

`func (o *Invoice) GetInvoiceTypeOk() (*InvoiceType, bool)`

GetInvoiceTypeOk returns a tuple with the InvoiceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceType

`func (o *Invoice) SetInvoiceType(v InvoiceType)`

SetInvoiceType sets InvoiceType field to given value.


### GetIsCancelled

`func (o *Invoice) GetIsCancelled() bool`

GetIsCancelled returns the IsCancelled field if non-nil, zero value otherwise.

### GetIsCancelledOk

`func (o *Invoice) GetIsCancelledOk() (*bool, bool)`

GetIsCancelledOk returns a tuple with the IsCancelled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCancelled

`func (o *Invoice) SetIsCancelled(v bool)`

SetIsCancelled sets IsCancelled field to given value.

### HasIsCancelled

`func (o *Invoice) HasIsCancelled() bool`

HasIsCancelled returns a boolean if a field has been set.

### GetIsDraft

`func (o *Invoice) GetIsDraft() bool`

GetIsDraft returns the IsDraft field if non-nil, zero value otherwise.

### GetIsDraftOk

`func (o *Invoice) GetIsDraftOk() (*bool, bool)`

GetIsDraftOk returns a tuple with the IsDraft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraft

`func (o *Invoice) SetIsDraft(v bool)`

SetIsDraft sets IsDraft field to given value.

### HasIsDraft

`func (o *Invoice) HasIsDraft() bool`

HasIsDraft returns a boolean if a field has been set.

### GetIsEuAcquisition

`func (o *Invoice) GetIsEuAcquisition() bool`

GetIsEuAcquisition returns the IsEuAcquisition field if non-nil, zero value otherwise.

### GetIsEuAcquisitionOk

`func (o *Invoice) GetIsEuAcquisitionOk() (*bool, bool)`

GetIsEuAcquisitionOk returns a tuple with the IsEuAcquisition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEuAcquisition

`func (o *Invoice) SetIsEuAcquisition(v bool)`

SetIsEuAcquisition sets IsEuAcquisition field to given value.

### HasIsEuAcquisition

`func (o *Invoice) HasIsEuAcquisition() bool`

HasIsEuAcquisition returns a boolean if a field has been set.

### GetIsEuDelivery

`func (o *Invoice) GetIsEuDelivery() bool`

GetIsEuDelivery returns the IsEuDelivery field if non-nil, zero value otherwise.

### GetIsEuDeliveryOk

`func (o *Invoice) GetIsEuDeliveryOk() (*bool, bool)`

GetIsEuDeliveryOk returns a tuple with the IsEuDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEuDelivery

`func (o *Invoice) SetIsEuDelivery(v bool)`

SetIsEuDelivery sets IsEuDelivery field to given value.

### HasIsEuDelivery

`func (o *Invoice) HasIsEuDelivery() bool`

HasIsEuDelivery returns a boolean if a field has been set.

### GetIsIntraCommunityAcquisition

`func (o *Invoice) GetIsIntraCommunityAcquisition() bool`

GetIsIntraCommunityAcquisition returns the IsIntraCommunityAcquisition field if non-nil, zero value otherwise.

### GetIsIntraCommunityAcquisitionOk

`func (o *Invoice) GetIsIntraCommunityAcquisitionOk() (*bool, bool)`

GetIsIntraCommunityAcquisitionOk returns a tuple with the IsIntraCommunityAcquisition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsIntraCommunityAcquisition

`func (o *Invoice) SetIsIntraCommunityAcquisition(v bool)`

SetIsIntraCommunityAcquisition sets IsIntraCommunityAcquisition field to given value.

### HasIsIntraCommunityAcquisition

`func (o *Invoice) HasIsIntraCommunityAcquisition() bool`

HasIsIntraCommunityAcquisition returns a boolean if a field has been set.

### GetIsReverseCharge

`func (o *Invoice) GetIsReverseCharge() bool`

GetIsReverseCharge returns the IsReverseCharge field if non-nil, zero value otherwise.

### GetIsReverseChargeOk

`func (o *Invoice) GetIsReverseChargeOk() (*bool, bool)`

GetIsReverseChargeOk returns a tuple with the IsReverseCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReverseCharge

`func (o *Invoice) SetIsReverseCharge(v bool)`

SetIsReverseCharge sets IsReverseCharge field to given value.

### HasIsReverseCharge

`func (o *Invoice) HasIsReverseCharge() bool`

HasIsReverseCharge returns a boolean if a field has been set.

### GetIssueDate

`func (o *Invoice) GetIssueDate() string`

GetIssueDate returns the IssueDate field if non-nil, zero value otherwise.

### GetIssueDateOk

`func (o *Invoice) GetIssueDateOk() (*string, bool)`

GetIssueDateOk returns a tuple with the IssueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueDate

`func (o *Invoice) SetIssueDate(v string)`

SetIssueDate sets IssueDate field to given value.


### GetLedgerAccount

`func (o *Invoice) GetLedgerAccount() string`

GetLedgerAccount returns the LedgerAccount field if non-nil, zero value otherwise.

### GetLedgerAccountOk

`func (o *Invoice) GetLedgerAccountOk() (*string, bool)`

GetLedgerAccountOk returns a tuple with the LedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerAccount

`func (o *Invoice) SetLedgerAccount(v string)`

SetLedgerAccount sets LedgerAccount field to given value.

### HasLedgerAccount

`func (o *Invoice) HasLedgerAccount() bool`

HasLedgerAccount returns a boolean if a field has been set.

### SetLedgerAccountNil

`func (o *Invoice) SetLedgerAccountNil(b bool)`

 SetLedgerAccountNil sets the value for LedgerAccount to be an explicit nil

### UnsetLedgerAccount
`func (o *Invoice) UnsetLedgerAccount()`

UnsetLedgerAccount ensures that no value is present for LedgerAccount, not even an explicit nil
### GetLineItems

`func (o *Invoice) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *Invoice) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *Invoice) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *Invoice) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *Invoice) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetMargin25a

`func (o *Invoice) GetMargin25a() bool`

GetMargin25a returns the Margin25a field if non-nil, zero value otherwise.

### GetMargin25aOk

`func (o *Invoice) GetMargin25aOk() (*bool, bool)`

GetMargin25aOk returns a tuple with the Margin25a field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25a

`func (o *Invoice) SetMargin25a(v bool)`

SetMargin25a sets Margin25a field to given value.

### HasMargin25a

`func (o *Invoice) HasMargin25a() bool`

HasMargin25a returns a boolean if a field has been set.

### GetMargin25aGross

`func (o *Invoice) GetMargin25aGross() string`

GetMargin25aGross returns the Margin25aGross field if non-nil, zero value otherwise.

### GetMargin25aGrossOk

`func (o *Invoice) GetMargin25aGrossOk() (*string, bool)`

GetMargin25aGrossOk returns a tuple with the Margin25aGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25aGross

`func (o *Invoice) SetMargin25aGross(v string)`

SetMargin25aGross sets Margin25aGross field to given value.

### HasMargin25aGross

`func (o *Invoice) HasMargin25aGross() bool`

HasMargin25aGross returns a boolean if a field has been set.

### SetMargin25aGrossNil

`func (o *Invoice) SetMargin25aGrossNil(b bool)`

 SetMargin25aGrossNil sets the value for Margin25aGross to be an explicit nil

### UnsetMargin25aGross
`func (o *Invoice) UnsetMargin25aGross()`

UnsetMargin25aGross ensures that no value is present for Margin25aGross, not even an explicit nil
### GetMargin25aPurchasePrice

`func (o *Invoice) GetMargin25aPurchasePrice() string`

GetMargin25aPurchasePrice returns the Margin25aPurchasePrice field if non-nil, zero value otherwise.

### GetMargin25aPurchasePriceOk

`func (o *Invoice) GetMargin25aPurchasePriceOk() (*string, bool)`

GetMargin25aPurchasePriceOk returns a tuple with the Margin25aPurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25aPurchasePrice

`func (o *Invoice) SetMargin25aPurchasePrice(v string)`

SetMargin25aPurchasePrice sets Margin25aPurchasePrice field to given value.

### HasMargin25aPurchasePrice

`func (o *Invoice) HasMargin25aPurchasePrice() bool`

HasMargin25aPurchasePrice returns a boolean if a field has been set.

### SetMargin25aPurchasePriceNil

`func (o *Invoice) SetMargin25aPurchasePriceNil(b bool)`

 SetMargin25aPurchasePriceNil sets the value for Margin25aPurchasePrice to be an explicit nil

### UnsetMargin25aPurchasePrice
`func (o *Invoice) UnsetMargin25aPurchasePrice()`

UnsetMargin25aPurchasePrice ensures that no value is present for Margin25aPurchasePrice, not even an explicit nil
### GetNotes

`func (o *Invoice) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Invoice) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Invoice) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Invoice) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Invoice) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Invoice) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOrderNumber

`func (o *Invoice) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *Invoice) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *Invoice) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *Invoice) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### SetOrderNumberNil

`func (o *Invoice) SetOrderNumberNil(b bool)`

 SetOrderNumberNil sets the value for OrderNumber to be an explicit nil

### UnsetOrderNumber
`func (o *Invoice) UnsetOrderNumber()`

UnsetOrderNumber ensures that no value is present for OrderNumber, not even an explicit nil
### GetOriginalPdfPath

`func (o *Invoice) GetOriginalPdfPath() string`

GetOriginalPdfPath returns the OriginalPdfPath field if non-nil, zero value otherwise.

### GetOriginalPdfPathOk

`func (o *Invoice) GetOriginalPdfPathOk() (*string, bool)`

GetOriginalPdfPathOk returns a tuple with the OriginalPdfPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPdfPath

`func (o *Invoice) SetOriginalPdfPath(v string)`

SetOriginalPdfPath sets OriginalPdfPath field to given value.

### HasOriginalPdfPath

`func (o *Invoice) HasOriginalPdfPath() bool`

HasOriginalPdfPath returns a boolean if a field has been set.

### SetOriginalPdfPathNil

`func (o *Invoice) SetOriginalPdfPathNil(b bool)`

 SetOriginalPdfPathNil sets the value for OriginalPdfPath to be an explicit nil

### UnsetOriginalPdfPath
`func (o *Invoice) UnsetOriginalPdfPath()`

UnsetOriginalPdfPath ensures that no value is present for OriginalPdfPath, not even an explicit nil
### GetPaidAmount

`func (o *Invoice) GetPaidAmount() string`

GetPaidAmount returns the PaidAmount field if non-nil, zero value otherwise.

### GetPaidAmountOk

`func (o *Invoice) GetPaidAmountOk() (*string, bool)`

GetPaidAmountOk returns a tuple with the PaidAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAmount

`func (o *Invoice) SetPaidAmount(v string)`

SetPaidAmount sets PaidAmount field to given value.

### HasPaidAmount

`func (o *Invoice) HasPaidAmount() bool`

HasPaidAmount returns a boolean if a field has been set.

### GetPaymentDueDate

`func (o *Invoice) GetPaymentDueDate() string`

GetPaymentDueDate returns the PaymentDueDate field if non-nil, zero value otherwise.

### GetPaymentDueDateOk

`func (o *Invoice) GetPaymentDueDateOk() (*string, bool)`

GetPaymentDueDateOk returns a tuple with the PaymentDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDate

`func (o *Invoice) SetPaymentDueDate(v string)`

SetPaymentDueDate sets PaymentDueDate field to given value.

### HasPaymentDueDate

`func (o *Invoice) HasPaymentDueDate() bool`

HasPaymentDueDate returns a boolean if a field has been set.

### SetPaymentDueDateNil

`func (o *Invoice) SetPaymentDueDateNil(b bool)`

 SetPaymentDueDateNil sets the value for PaymentDueDate to be an explicit nil

### UnsetPaymentDueDate
`func (o *Invoice) UnsetPaymentDueDate()`

UnsetPaymentDueDate ensures that no value is present for PaymentDueDate, not even an explicit nil
### GetPaymentStatus

`func (o *Invoice) GetPaymentStatus() PaymentStatus`

GetPaymentStatus returns the PaymentStatus field if non-nil, zero value otherwise.

### GetPaymentStatusOk

`func (o *Invoice) GetPaymentStatusOk() (*PaymentStatus, bool)`

GetPaymentStatusOk returns a tuple with the PaymentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentStatus

`func (o *Invoice) SetPaymentStatus(v PaymentStatus)`

SetPaymentStatus sets PaymentStatus field to given value.

### HasPaymentStatus

`func (o *Invoice) HasPaymentStatus() bool`

HasPaymentStatus returns a boolean if a field has been set.

### GetPaymentTermsText

`func (o *Invoice) GetPaymentTermsText() string`

GetPaymentTermsText returns the PaymentTermsText field if non-nil, zero value otherwise.

### GetPaymentTermsTextOk

`func (o *Invoice) GetPaymentTermsTextOk() (*string, bool)`

GetPaymentTermsTextOk returns a tuple with the PaymentTermsText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTermsText

`func (o *Invoice) SetPaymentTermsText(v string)`

SetPaymentTermsText sets PaymentTermsText field to given value.

### HasPaymentTermsText

`func (o *Invoice) HasPaymentTermsText() bool`

HasPaymentTermsText returns a boolean if a field has been set.

### SetPaymentTermsTextNil

`func (o *Invoice) SetPaymentTermsTextNil(b bool)`

 SetPaymentTermsTextNil sets the value for PaymentTermsText to be an explicit nil

### UnsetPaymentTermsText
`func (o *Invoice) UnsetPaymentTermsText()`

UnsetPaymentTermsText ensures that no value is present for PaymentTermsText, not even an explicit nil
### GetPrecedingSalesVoucherId

`func (o *Invoice) GetPrecedingSalesVoucherId() string`

GetPrecedingSalesVoucherId returns the PrecedingSalesVoucherId field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherIdOk

`func (o *Invoice) GetPrecedingSalesVoucherIdOk() (*string, bool)`

GetPrecedingSalesVoucherIdOk returns a tuple with the PrecedingSalesVoucherId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherId

`func (o *Invoice) SetPrecedingSalesVoucherId(v string)`

SetPrecedingSalesVoucherId sets PrecedingSalesVoucherId field to given value.

### HasPrecedingSalesVoucherId

`func (o *Invoice) HasPrecedingSalesVoucherId() bool`

HasPrecedingSalesVoucherId returns a boolean if a field has been set.

### SetPrecedingSalesVoucherIdNil

`func (o *Invoice) SetPrecedingSalesVoucherIdNil(b bool)`

 SetPrecedingSalesVoucherIdNil sets the value for PrecedingSalesVoucherId to be an explicit nil

### UnsetPrecedingSalesVoucherId
`func (o *Invoice) UnsetPrecedingSalesVoucherId()`

UnsetPrecedingSalesVoucherId ensures that no value is present for PrecedingSalesVoucherId, not even an explicit nil
### GetPrecedingSalesVoucherType

`func (o *Invoice) GetPrecedingSalesVoucherType() PrecedingSalesVoucherType`

GetPrecedingSalesVoucherType returns the PrecedingSalesVoucherType field if non-nil, zero value otherwise.

### GetPrecedingSalesVoucherTypeOk

`func (o *Invoice) GetPrecedingSalesVoucherTypeOk() (*PrecedingSalesVoucherType, bool)`

GetPrecedingSalesVoucherTypeOk returns a tuple with the PrecedingSalesVoucherType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecedingSalesVoucherType

`func (o *Invoice) SetPrecedingSalesVoucherType(v PrecedingSalesVoucherType)`

SetPrecedingSalesVoucherType sets PrecedingSalesVoucherType field to given value.

### HasPrecedingSalesVoucherType

`func (o *Invoice) HasPrecedingSalesVoucherType() bool`

HasPrecedingSalesVoucherType returns a boolean if a field has been set.

### SetPrecedingSalesVoucherTypeNil

`func (o *Invoice) SetPrecedingSalesVoucherTypeNil(b bool)`

 SetPrecedingSalesVoucherTypeNil sets the value for PrecedingSalesVoucherType to be an explicit nil

### UnsetPrecedingSalesVoucherType
`func (o *Invoice) UnsetPrecedingSalesVoucherType()`

UnsetPrecedingSalesVoucherType ensures that no value is present for PrecedingSalesVoucherType, not even an explicit nil
### GetReceiptConfirmationAvailable

`func (o *Invoice) GetReceiptConfirmationAvailable() bool`

GetReceiptConfirmationAvailable returns the ReceiptConfirmationAvailable field if non-nil, zero value otherwise.

### GetReceiptConfirmationAvailableOk

`func (o *Invoice) GetReceiptConfirmationAvailableOk() (*bool, bool)`

GetReceiptConfirmationAvailableOk returns a tuple with the ReceiptConfirmationAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptConfirmationAvailable

`func (o *Invoice) SetReceiptConfirmationAvailable(v bool)`

SetReceiptConfirmationAvailable sets ReceiptConfirmationAvailable field to given value.

### HasReceiptConfirmationAvailable

`func (o *Invoice) HasReceiptConfirmationAvailable() bool`

HasReceiptConfirmationAvailable returns a boolean if a field has been set.

### GetRelatedInvoiceId

`func (o *Invoice) GetRelatedInvoiceId() string`

GetRelatedInvoiceId returns the RelatedInvoiceId field if non-nil, zero value otherwise.

### GetRelatedInvoiceIdOk

`func (o *Invoice) GetRelatedInvoiceIdOk() (*string, bool)`

GetRelatedInvoiceIdOk returns a tuple with the RelatedInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedInvoiceId

`func (o *Invoice) SetRelatedInvoiceId(v string)`

SetRelatedInvoiceId sets RelatedInvoiceId field to given value.

### HasRelatedInvoiceId

`func (o *Invoice) HasRelatedInvoiceId() bool`

HasRelatedInvoiceId returns a boolean if a field has been set.

### SetRelatedInvoiceIdNil

`func (o *Invoice) SetRelatedInvoiceIdNil(b bool)`

 SetRelatedInvoiceIdNil sets the value for RelatedInvoiceId to be an explicit nil

### UnsetRelatedInvoiceId
`func (o *Invoice) UnsetRelatedInvoiceId()`

UnsetRelatedInvoiceId ensures that no value is present for RelatedInvoiceId, not even an explicit nil
### GetRelationshipType

`func (o *Invoice) GetRelationshipType() string`

GetRelationshipType returns the RelationshipType field if non-nil, zero value otherwise.

### GetRelationshipTypeOk

`func (o *Invoice) GetRelationshipTypeOk() (*string, bool)`

GetRelationshipTypeOk returns a tuple with the RelationshipType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelationshipType

`func (o *Invoice) SetRelationshipType(v string)`

SetRelationshipType sets RelationshipType field to given value.

### HasRelationshipType

`func (o *Invoice) HasRelationshipType() bool`

HasRelationshipType returns a boolean if a field has been set.

### SetRelationshipTypeNil

`func (o *Invoice) SetRelationshipTypeNil(b bool)`

 SetRelationshipTypeNil sets the value for RelationshipType to be an explicit nil

### UnsetRelationshipType
`func (o *Invoice) UnsetRelationshipType()`

UnsetRelationshipType ensures that no value is present for RelationshipType, not even an explicit nil
### GetSenderSnapshot

`func (o *Invoice) GetSenderSnapshot() interface{}`

GetSenderSnapshot returns the SenderSnapshot field if non-nil, zero value otherwise.

### GetSenderSnapshotOk

`func (o *Invoice) GetSenderSnapshotOk() (*interface{}, bool)`

GetSenderSnapshotOk returns a tuple with the SenderSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderSnapshot

`func (o *Invoice) SetSenderSnapshot(v interface{})`

SetSenderSnapshot sets SenderSnapshot field to given value.

### HasSenderSnapshot

`func (o *Invoice) HasSenderSnapshot() bool`

HasSenderSnapshot returns a boolean if a field has been set.

### SetSenderSnapshotNil

`func (o *Invoice) SetSenderSnapshotNil(b bool)`

 SetSenderSnapshotNil sets the value for SenderSnapshot to be an explicit nil

### UnsetSenderSnapshot
`func (o *Invoice) UnsetSenderSnapshot()`

UnsetSenderSnapshot ensures that no value is present for SenderSnapshot, not even an explicit nil
### GetSentAt

`func (o *Invoice) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *Invoice) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *Invoice) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *Invoice) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *Invoice) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *Invoice) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetServicePeriodEnd

`func (o *Invoice) GetServicePeriodEnd() string`

GetServicePeriodEnd returns the ServicePeriodEnd field if non-nil, zero value otherwise.

### GetServicePeriodEndOk

`func (o *Invoice) GetServicePeriodEndOk() (*string, bool)`

GetServicePeriodEndOk returns a tuple with the ServicePeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePeriodEnd

`func (o *Invoice) SetServicePeriodEnd(v string)`

SetServicePeriodEnd sets ServicePeriodEnd field to given value.

### HasServicePeriodEnd

`func (o *Invoice) HasServicePeriodEnd() bool`

HasServicePeriodEnd returns a boolean if a field has been set.

### SetServicePeriodEndNil

`func (o *Invoice) SetServicePeriodEndNil(b bool)`

 SetServicePeriodEndNil sets the value for ServicePeriodEnd to be an explicit nil

### UnsetServicePeriodEnd
`func (o *Invoice) UnsetServicePeriodEnd()`

UnsetServicePeriodEnd ensures that no value is present for ServicePeriodEnd, not even an explicit nil
### GetServicePeriodStart

`func (o *Invoice) GetServicePeriodStart() string`

GetServicePeriodStart returns the ServicePeriodStart field if non-nil, zero value otherwise.

### GetServicePeriodStartOk

`func (o *Invoice) GetServicePeriodStartOk() (*string, bool)`

GetServicePeriodStartOk returns a tuple with the ServicePeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePeriodStart

`func (o *Invoice) SetServicePeriodStart(v string)`

SetServicePeriodStart sets ServicePeriodStart field to given value.

### HasServicePeriodStart

`func (o *Invoice) HasServicePeriodStart() bool`

HasServicePeriodStart returns a boolean if a field has been set.

### SetServicePeriodStartNil

`func (o *Invoice) SetServicePeriodStartNil(b bool)`

 SetServicePeriodStartNil sets the value for ServicePeriodStart to be an explicit nil

### UnsetServicePeriodStart
`func (o *Invoice) UnsetServicePeriodStart()`

UnsetServicePeriodStart ensures that no value is present for ServicePeriodStart, not even an explicit nil
### GetStatus

`func (o *Invoice) GetStatus() InvoiceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Invoice) GetStatusOk() (*InvoiceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Invoice) SetStatus(v InvoiceStatus)`

SetStatus sets Status field to given value.


### GetSubtotal

`func (o *Invoice) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *Invoice) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *Invoice) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.


### GetSupplierId

`func (o *Invoice) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *Invoice) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *Invoice) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *Invoice) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### SetSupplierIdNil

`func (o *Invoice) SetSupplierIdNil(b bool)`

 SetSupplierIdNil sets the value for SupplierId to be an explicit nil

### UnsetSupplierId
`func (o *Invoice) UnsetSupplierId()`

UnsetSupplierId ensures that no value is present for SupplierId, not even an explicit nil
### GetTaxExemptionReason

`func (o *Invoice) GetTaxExemptionReason() string`

GetTaxExemptionReason returns the TaxExemptionReason field if non-nil, zero value otherwise.

### GetTaxExemptionReasonOk

`func (o *Invoice) GetTaxExemptionReasonOk() (*string, bool)`

GetTaxExemptionReasonOk returns a tuple with the TaxExemptionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxExemptionReason

`func (o *Invoice) SetTaxExemptionReason(v string)`

SetTaxExemptionReason sets TaxExemptionReason field to given value.

### HasTaxExemptionReason

`func (o *Invoice) HasTaxExemptionReason() bool`

HasTaxExemptionReason returns a boolean if a field has been set.

### SetTaxExemptionReasonNil

`func (o *Invoice) SetTaxExemptionReasonNil(b bool)`

 SetTaxExemptionReasonNil sets the value for TaxExemptionReason to be an explicit nil

### UnsetTaxExemptionReason
`func (o *Invoice) UnsetTaxExemptionReason()`

UnsetTaxExemptionReason ensures that no value is present for TaxExemptionReason, not even an explicit nil
### GetTotalAmount

`func (o *Invoice) GetTotalAmount() string`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *Invoice) GetTotalAmountOk() (*string, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *Invoice) SetTotalAmount(v string)`

SetTotalAmount sets TotalAmount field to given value.


### GetTotalTax

`func (o *Invoice) GetTotalTax() string`

GetTotalTax returns the TotalTax field if non-nil, zero value otherwise.

### GetTotalTaxOk

`func (o *Invoice) GetTotalTaxOk() (*string, bool)`

GetTotalTaxOk returns a tuple with the TotalTax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTax

`func (o *Invoice) SetTotalTax(v string)`

SetTotalTax sets TotalTax field to given value.


### GetVatCountry

`func (o *Invoice) GetVatCountry() CountryCode`

GetVatCountry returns the VatCountry field if non-nil, zero value otherwise.

### GetVatCountryOk

`func (o *Invoice) GetVatCountryOk() (*CountryCode, bool)`

GetVatCountryOk returns a tuple with the VatCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatCountry

`func (o *Invoice) SetVatCountry(v CountryCode)`

SetVatCountry sets VatCountry field to given value.

### HasVatCountry

`func (o *Invoice) HasVatCountry() bool`

HasVatCountry returns a boolean if a field has been set.

### SetVatCountryNil

`func (o *Invoice) SetVatCountryNil(b bool)`

 SetVatCountryNil sets the value for VatCountry to be an explicit nil

### UnsetVatCountry
`func (o *Invoice) UnsetVatCountry()`

UnsetVatCountry ensures that no value is present for VatCountry, not even an explicit nil
### GetVatSpecialCase

`func (o *Invoice) GetVatSpecialCase() string`

GetVatSpecialCase returns the VatSpecialCase field if non-nil, zero value otherwise.

### GetVatSpecialCaseOk

`func (o *Invoice) GetVatSpecialCaseOk() (*string, bool)`

GetVatSpecialCaseOk returns a tuple with the VatSpecialCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatSpecialCase

`func (o *Invoice) SetVatSpecialCase(v string)`

SetVatSpecialCase sets VatSpecialCase field to given value.

### HasVatSpecialCase

`func (o *Invoice) HasVatSpecialCase() bool`

HasVatSpecialCase returns a boolean if a field has been set.

### SetVatSpecialCaseNil

`func (o *Invoice) SetVatSpecialCaseNil(b bool)`

 SetVatSpecialCaseNil sets the value for VatSpecialCase to be an explicit nil

### UnsetVatSpecialCase
`func (o *Invoice) UnsetVatSpecialCase()`

UnsetVatSpecialCase ensures that no value is present for VatSpecialCase, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


