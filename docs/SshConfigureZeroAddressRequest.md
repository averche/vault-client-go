# SshConfigureZeroAddressRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Roles** | Pointer to **[]string** | [Required] Comma separated list of role names which allows credentials to be requested for any IP address. CIDR blocks previously registered under these roles will be ignored. | [optional] 



## Methods


### NewSshConfigureZeroAddressRequest

`func NewSshConfigureZeroAddressRequest() *SshConfigureZeroAddressRequest`

NewSshConfigureZeroAddressRequest instantiates a new SshConfigureZeroAddressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSshConfigureZeroAddressRequestWithDefaults

`func NewSshConfigureZeroAddressRequestWithDefaults() *SshConfigureZeroAddressRequest`

NewSshConfigureZeroAddressRequestWithDefaults instantiates a new SshConfigureZeroAddressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetRoles

`func (o *SshConfigureZeroAddressRequest) GetRoles() []string`

GetRoles returns the Roles field if non-nil, zero value otherwise.

### GetRolesOk

`func (o *SshConfigureZeroAddressRequest) GetRolesOk() (*[]string, bool)`

GetRolesOk returns a tuple with the Roles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoles

`func (o *SshConfigureZeroAddressRequest) SetRoles(v []string)`

SetRoles sets Roles field to given value.


### HasRoles

`func (o *SshConfigureZeroAddressRequest) HasRoles() bool`

HasRoles returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


