# AppRoleWriteBindSecretIdRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BindSecretId** | Pointer to **bool** | Impose secret_id to be presented when logging in using this role. | [optional] [default to true]



## Methods


### NewAppRoleWriteBindSecretIdRequest

`func NewAppRoleWriteBindSecretIdRequest() *AppRoleWriteBindSecretIdRequest`

NewAppRoleWriteBindSecretIdRequest instantiates a new AppRoleWriteBindSecretIdRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppRoleWriteBindSecretIdRequestWithDefaults

`func NewAppRoleWriteBindSecretIdRequestWithDefaults() *AppRoleWriteBindSecretIdRequest`

NewAppRoleWriteBindSecretIdRequestWithDefaults instantiates a new AppRoleWriteBindSecretIdRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetBindSecretId

`func (o *AppRoleWriteBindSecretIdRequest) GetBindSecretId() bool`

GetBindSecretId returns the BindSecretId field if non-nil, zero value otherwise.

### GetBindSecretIdOk

`func (o *AppRoleWriteBindSecretIdRequest) GetBindSecretIdOk() (*bool, bool)`

GetBindSecretIdOk returns a tuple with the BindSecretId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindSecretId

`func (o *AppRoleWriteBindSecretIdRequest) SetBindSecretId(v bool)`

SetBindSecretId sets BindSecretId field to given value.


### HasBindSecretId

`func (o *AppRoleWriteBindSecretIdRequest) HasBindSecretId() bool`

HasBindSecretId returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


