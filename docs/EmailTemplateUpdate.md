# EmailTemplateUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | Pointer to **NullableString** | E-mail body with optional placeholders. | [optional] 
**Name** | Pointer to **NullableString** | Human-readable template name, e.g. \&quot;Follow-up after quote\&quot;. | [optional] 
**Status** | Pointer to [**NullableEmailTemplateStatus**](EmailTemplateStatus.md) | One of: active | inactive | [optional] 
**Subject** | Pointer to **NullableString** | E-mail subject line with optional placeholders. | [optional] 
**Variables** | Pointer to **interface{}** | Placeholders used by this template, e.g. &#x60;[\&quot;contact.first_name\&quot;]&#x60;. | [optional] 

## Methods

### NewEmailTemplateUpdate

`func NewEmailTemplateUpdate() *EmailTemplateUpdate`

NewEmailTemplateUpdate instantiates a new EmailTemplateUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailTemplateUpdateWithDefaults

`func NewEmailTemplateUpdateWithDefaults() *EmailTemplateUpdate`

NewEmailTemplateUpdateWithDefaults instantiates a new EmailTemplateUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *EmailTemplateUpdate) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *EmailTemplateUpdate) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *EmailTemplateUpdate) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *EmailTemplateUpdate) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *EmailTemplateUpdate) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *EmailTemplateUpdate) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetName

`func (o *EmailTemplateUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EmailTemplateUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EmailTemplateUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EmailTemplateUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *EmailTemplateUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *EmailTemplateUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetStatus

`func (o *EmailTemplateUpdate) GetStatus() EmailTemplateStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmailTemplateUpdate) GetStatusOk() (*EmailTemplateStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmailTemplateUpdate) SetStatus(v EmailTemplateStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmailTemplateUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *EmailTemplateUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *EmailTemplateUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSubject

`func (o *EmailTemplateUpdate) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *EmailTemplateUpdate) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *EmailTemplateUpdate) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *EmailTemplateUpdate) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *EmailTemplateUpdate) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *EmailTemplateUpdate) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetVariables

`func (o *EmailTemplateUpdate) GetVariables() interface{}`

GetVariables returns the Variables field if non-nil, zero value otherwise.

### GetVariablesOk

`func (o *EmailTemplateUpdate) GetVariablesOk() (*interface{}, bool)`

GetVariablesOk returns a tuple with the Variables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariables

`func (o *EmailTemplateUpdate) SetVariables(v interface{})`

SetVariables sets Variables field to given value.

### HasVariables

`func (o *EmailTemplateUpdate) HasVariables() bool`

HasVariables returns a boolean if a field has been set.

### SetVariablesNil

`func (o *EmailTemplateUpdate) SetVariablesNil(b bool)`

 SetVariablesNil sets the value for Variables to be an explicit nil

### UnsetVariables
`func (o *EmailTemplateUpdate) UnsetVariables()`

UnsetVariables ensures that no value is present for Variables, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


