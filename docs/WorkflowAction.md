# WorkflowAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActionType** | **string** |  | 
**Body** | Pointer to **NullableString** |  | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWorkflowAction

`func NewWorkflowAction(actionType string, ) *WorkflowAction`

NewWorkflowAction instantiates a new WorkflowAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowActionWithDefaults

`func NewWorkflowActionWithDefaults() *WorkflowAction`

NewWorkflowActionWithDefaults instantiates a new WorkflowAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActionType

`func (o *WorkflowAction) GetActionType() string`

GetActionType returns the ActionType field if non-nil, zero value otherwise.

### GetActionTypeOk

`func (o *WorkflowAction) GetActionTypeOk() (*string, bool)`

GetActionTypeOk returns a tuple with the ActionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionType

`func (o *WorkflowAction) SetActionType(v string)`

SetActionType sets ActionType field to given value.


### GetBody

`func (o *WorkflowAction) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *WorkflowAction) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *WorkflowAction) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *WorkflowAction) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *WorkflowAction) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *WorkflowAction) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetSubject

`func (o *WorkflowAction) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *WorkflowAction) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *WorkflowAction) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *WorkflowAction) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *WorkflowAction) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *WorkflowAction) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


