# Workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | Pointer to **interface{}** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Name** | **string** |  | 
**TriggerEvent** | **string** | Event that triggers the workflow, e.g. &#x60;order.paid&#x60;, &#x60;order.shipped&#x60;. | 

## Methods

### NewWorkflow

`func NewWorkflow(name string, triggerEvent string, ) *Workflow`

NewWorkflow instantiates a new Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowWithDefaults

`func NewWorkflowWithDefaults() *Workflow`

NewWorkflowWithDefaults instantiates a new Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *Workflow) GetActions() interface{}`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *Workflow) GetActionsOk() (*interface{}, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *Workflow) SetActions(v interface{})`

SetActions sets Actions field to given value.

### HasActions

`func (o *Workflow) HasActions() bool`

HasActions returns a boolean if a field has been set.

### SetActionsNil

`func (o *Workflow) SetActionsNil(b bool)`

 SetActionsNil sets the value for Actions to be an explicit nil

### UnsetActions
`func (o *Workflow) UnsetActions()`

UnsetActions ensures that no value is present for Actions, not even an explicit nil
### GetEnabled

`func (o *Workflow) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Workflow) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Workflow) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *Workflow) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetName

`func (o *Workflow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Workflow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Workflow) SetName(v string)`

SetName sets Name field to given value.


### GetTriggerEvent

`func (o *Workflow) GetTriggerEvent() string`

GetTriggerEvent returns the TriggerEvent field if non-nil, zero value otherwise.

### GetTriggerEventOk

`func (o *Workflow) GetTriggerEventOk() (*string, bool)`

GetTriggerEventOk returns a tuple with the TriggerEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerEvent

`func (o *Workflow) SetTriggerEvent(v string)`

SetTriggerEvent sets TriggerEvent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


