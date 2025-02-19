# EntityCreateAliasRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanonicalId** | Pointer to **string** | Entity ID to which this alias belongs | [optional] 
**CustomMetadata** | Pointer to **map[string]interface{}** | User provided key-value pairs | [optional] 
**EntityId** | Pointer to **string** | Entity ID to which this alias belongs. This field is deprecated, use canonical_id. | [optional] 
**Id** | Pointer to **string** | ID of the entity alias. If set, updates the corresponding entity alias. | [optional] 
**MountAccessor** | Pointer to **string** | Mount accessor to which this alias belongs to; unused for a modify | [optional] 
**Name** | Pointer to **string** | Name of the alias; unused for a modify | [optional] 



## Methods


### NewEntityCreateAliasRequest

`func NewEntityCreateAliasRequest() *EntityCreateAliasRequest`

NewEntityCreateAliasRequest instantiates a new EntityCreateAliasRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityCreateAliasRequestWithDefaults

`func NewEntityCreateAliasRequestWithDefaults() *EntityCreateAliasRequest`

NewEntityCreateAliasRequestWithDefaults instantiates a new EntityCreateAliasRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCanonicalId

`func (o *EntityCreateAliasRequest) GetCanonicalId() string`

GetCanonicalId returns the CanonicalId field if non-nil, zero value otherwise.

### GetCanonicalIdOk

`func (o *EntityCreateAliasRequest) GetCanonicalIdOk() (*string, bool)`

GetCanonicalIdOk returns a tuple with the CanonicalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalId

`func (o *EntityCreateAliasRequest) SetCanonicalId(v string)`

SetCanonicalId sets CanonicalId field to given value.


### HasCanonicalId

`func (o *EntityCreateAliasRequest) HasCanonicalId() bool`

HasCanonicalId returns a boolean if a field has been set.




### GetCustomMetadata

`func (o *EntityCreateAliasRequest) GetCustomMetadata() map[string]interface{}`

GetCustomMetadata returns the CustomMetadata field if non-nil, zero value otherwise.

### GetCustomMetadataOk

`func (o *EntityCreateAliasRequest) GetCustomMetadataOk() (*map[string]interface{}, bool)`

GetCustomMetadataOk returns a tuple with the CustomMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomMetadata

`func (o *EntityCreateAliasRequest) SetCustomMetadata(v map[string]interface{})`

SetCustomMetadata sets CustomMetadata field to given value.


### HasCustomMetadata

`func (o *EntityCreateAliasRequest) HasCustomMetadata() bool`

HasCustomMetadata returns a boolean if a field has been set.




### GetEntityId

`func (o *EntityCreateAliasRequest) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *EntityCreateAliasRequest) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *EntityCreateAliasRequest) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### HasEntityId

`func (o *EntityCreateAliasRequest) HasEntityId() bool`

HasEntityId returns a boolean if a field has been set.




### GetId

`func (o *EntityCreateAliasRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntityCreateAliasRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntityCreateAliasRequest) SetId(v string)`

SetId sets Id field to given value.


### HasId

`func (o *EntityCreateAliasRequest) HasId() bool`

HasId returns a boolean if a field has been set.




### GetMountAccessor

`func (o *EntityCreateAliasRequest) GetMountAccessor() string`

GetMountAccessor returns the MountAccessor field if non-nil, zero value otherwise.

### GetMountAccessorOk

`func (o *EntityCreateAliasRequest) GetMountAccessorOk() (*string, bool)`

GetMountAccessorOk returns a tuple with the MountAccessor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMountAccessor

`func (o *EntityCreateAliasRequest) SetMountAccessor(v string)`

SetMountAccessor sets MountAccessor field to given value.


### HasMountAccessor

`func (o *EntityCreateAliasRequest) HasMountAccessor() bool`

HasMountAccessor returns a boolean if a field has been set.




### GetName

`func (o *EntityCreateAliasRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EntityCreateAliasRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EntityCreateAliasRequest) SetName(v string)`

SetName sets Name field to given value.


### HasName

`func (o *EntityCreateAliasRequest) HasName() bool`

HasName returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


