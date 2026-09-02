# EmailTemplateCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** | E-mail body with optional placeholders. | 
**Name** | **string** | Human-readable template name, e.g. \&quot;Follow-up after quote\&quot;. | 
**Status** | [**EmailTemplateStatus**](EmailTemplateStatus.md) | One of: active | inactive | 
**Subject** | **string** | E-mail subject line with optional placeholders. | 
**Variables** | Pointer to **interface{}** | Placeholders used by this template, e.g. &#x60;[\&quot;contact.first_name\&quot;]&#x60;. | [optional] 

## Methods

### NewEmailTemplateCreate

`func NewEmailTemplateCreate(body string, name string, status EmailTemplateStatus, subject string, ) *EmailTemplateCreate`

NewEmailTemplateCreate instantiates a new EmailTemplateCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailTemplateCreateWithDefaults

`func NewEmailTemplateCreateWithDefaults() *EmailTemplateCreate`

NewEmailTemplateCreateWithDefaults instantiates a new EmailTemplateCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *EmailTemplateCreate) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *EmailTemplateCreate) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *EmailTemplateCreate) SetBody(v string)`

SetBody sets Body field to given value.


### GetName

`func (o *EmailTemplateCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EmailTemplateCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EmailTemplateCreate) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *EmailTemplateCreate) GetStatus() EmailTemplateStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmailTemplateCreate) GetStatusOk() (*EmailTemplateStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmailTemplateCreate) SetStatus(v EmailTemplateStatus)`

SetStatus sets Status field to given value.


### GetSubject

`func (o *EmailTemplateCreate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *EmailTemplateCreate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *EmailTemplateCreate) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetVariables

`func (o *EmailTemplateCreate) GetVariables() interface{}`

GetVariables returns the Variables field if non-nil, zero value otherwise.

### GetVariablesOk

`func (o *EmailTemplateCreate) GetVariablesOk() (*interface{}, bool)`

GetVariablesOk returns a tuple with the Variables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariables

`func (o *EmailTemplateCreate) SetVariables(v interface{})`

SetVariables sets Variables field to given value.

### HasVariables

`func (o *EmailTemplateCreate) HasVariables() bool`

HasVariables returns a boolean if a field has been set.

### SetVariablesNil

`func (o *EmailTemplateCreate) SetVariablesNil(b bool)`

 SetVariablesNil sets the value for Variables to be an explicit nil

### UnsetVariables
`func (o *EmailTemplateCreate) UnsetVariables()`

UnsetVariables ensures that no value is present for Variables, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


