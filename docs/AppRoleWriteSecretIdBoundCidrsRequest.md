# AppRoleWriteSecretIdBoundCidrsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SecretIdBoundCidrs** | Pointer to **[]string** | Comma separated string or list of CIDR blocks. If set, specifies the blocks of IP addresses which can perform the login operation. | [optional] 



## Methods


### NewAppRoleWriteSecretIdBoundCidrsRequest

`func NewAppRoleWriteSecretIdBoundCidrsRequest() *AppRoleWriteSecretIdBoundCidrsRequest`

NewAppRoleWriteSecretIdBoundCidrsRequest instantiates a new AppRoleWriteSecretIdBoundCidrsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppRoleWriteSecretIdBoundCidrsRequestWithDefaults

`func NewAppRoleWriteSecretIdBoundCidrsRequestWithDefaults() *AppRoleWriteSecretIdBoundCidrsRequest`

NewAppRoleWriteSecretIdBoundCidrsRequestWithDefaults instantiates a new AppRoleWriteSecretIdBoundCidrsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetSecretIdBoundCidrs

`func (o *AppRoleWriteSecretIdBoundCidrsRequest) GetSecretIdBoundCidrs() []string`

GetSecretIdBoundCidrs returns the SecretIdBoundCidrs field if non-nil, zero value otherwise.

### GetSecretIdBoundCidrsOk

`func (o *AppRoleWriteSecretIdBoundCidrsRequest) GetSecretIdBoundCidrsOk() (*[]string, bool)`

GetSecretIdBoundCidrsOk returns a tuple with the SecretIdBoundCidrs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretIdBoundCidrs

`func (o *AppRoleWriteSecretIdBoundCidrsRequest) SetSecretIdBoundCidrs(v []string)`

SetSecretIdBoundCidrs sets SecretIdBoundCidrs field to given value.


### HasSecretIdBoundCidrs

`func (o *AppRoleWriteSecretIdBoundCidrsRequest) HasSecretIdBoundCidrs() bool`

HasSecretIdBoundCidrs returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


