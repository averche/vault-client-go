# AppRoleReadSecretIdNumUsesResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SecretIdNumUses** | Pointer to **int32** | Number of times a secret ID can access the role, after which the SecretID will expire. Defaults to 0 meaning that the secret ID is of unlimited use. | [optional] 



## Methods


### NewAppRoleReadSecretIdNumUsesResponse

`func NewAppRoleReadSecretIdNumUsesResponse() *AppRoleReadSecretIdNumUsesResponse`

NewAppRoleReadSecretIdNumUsesResponse instantiates a new AppRoleReadSecretIdNumUsesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppRoleReadSecretIdNumUsesResponseWithDefaults

`func NewAppRoleReadSecretIdNumUsesResponseWithDefaults() *AppRoleReadSecretIdNumUsesResponse`

NewAppRoleReadSecretIdNumUsesResponseWithDefaults instantiates a new AppRoleReadSecretIdNumUsesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetSecretIdNumUses

`func (o *AppRoleReadSecretIdNumUsesResponse) GetSecretIdNumUses() int32`

GetSecretIdNumUses returns the SecretIdNumUses field if non-nil, zero value otherwise.

### GetSecretIdNumUsesOk

`func (o *AppRoleReadSecretIdNumUsesResponse) GetSecretIdNumUsesOk() (*int32, bool)`

GetSecretIdNumUsesOk returns a tuple with the SecretIdNumUses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretIdNumUses

`func (o *AppRoleReadSecretIdNumUsesResponse) SetSecretIdNumUses(v int32)`

SetSecretIdNumUses sets SecretIdNumUses field to given value.


### HasSecretIdNumUses

`func (o *AppRoleReadSecretIdNumUsesResponse) HasSecretIdNumUses() bool`

HasSecretIdNumUses returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


