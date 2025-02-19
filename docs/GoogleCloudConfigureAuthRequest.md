# GoogleCloudConfigureAuthRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Credentials** | Pointer to **string** | Google credentials JSON that Vault will use to verify users against GCP APIs. If not specified, will use application default credentials | [optional] 
**CustomEndpoint** | Pointer to **map[string]interface{}** | Specifies overrides for various Google API Service Endpoints used in requests. | [optional] 
**GceAlias** | Pointer to **string** | Indicates what value to use when generating an alias for GCE authentications. | [optional] [default to "role_id"]
**GceMetadata** | Pointer to **[]string** | The metadata to include on the aliases and audit logs generated by this plugin. When set to &#x27;default&#x27;, includes: instance_creation_timestamp, instance_id, instance_name, project_id, project_number, role, service_account_id, service_account_email, zone. Not editing this field means the &#x27;default&#x27; fields are included. Explicitly setting this field to empty overrides the &#x27;default&#x27; and means no metadata will be included. If not using &#x27;default&#x27;, explicit fields must be sent like: &#x27;field1,field2&#x27;. | [optional] [default to ["default"]]
**GoogleCertsEndpoint** | Pointer to **string** | Deprecated. This field does nothing and be removed in a future release | [optional] 
**IamAlias** | Pointer to **string** | Indicates what value to use when generating an alias for IAM authentications. | [optional] [default to "role_id"]
**IamMetadata** | Pointer to **[]string** | The metadata to include on the aliases and audit logs generated by this plugin. When set to &#x27;default&#x27;, includes: project_id, role, service_account_id, service_account_email. Not editing this field means the &#x27;default&#x27; fields are included. Explicitly setting this field to empty overrides the &#x27;default&#x27; and means no metadata will be included. If not using &#x27;default&#x27;, explicit fields must be sent like: &#x27;field1,field2&#x27;. | [optional] [default to ["default"]]



## Methods


### NewGoogleCloudConfigureAuthRequest

`func NewGoogleCloudConfigureAuthRequest() *GoogleCloudConfigureAuthRequest`

NewGoogleCloudConfigureAuthRequest instantiates a new GoogleCloudConfigureAuthRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGoogleCloudConfigureAuthRequestWithDefaults

`func NewGoogleCloudConfigureAuthRequestWithDefaults() *GoogleCloudConfigureAuthRequest`

NewGoogleCloudConfigureAuthRequestWithDefaults instantiates a new GoogleCloudConfigureAuthRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCredentials

`func (o *GoogleCloudConfigureAuthRequest) GetCredentials() string`

GetCredentials returns the Credentials field if non-nil, zero value otherwise.

### GetCredentialsOk

`func (o *GoogleCloudConfigureAuthRequest) GetCredentialsOk() (*string, bool)`

GetCredentialsOk returns a tuple with the Credentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentials

`func (o *GoogleCloudConfigureAuthRequest) SetCredentials(v string)`

SetCredentials sets Credentials field to given value.


### HasCredentials

`func (o *GoogleCloudConfigureAuthRequest) HasCredentials() bool`

HasCredentials returns a boolean if a field has been set.




### GetCustomEndpoint

`func (o *GoogleCloudConfigureAuthRequest) GetCustomEndpoint() map[string]interface{}`

GetCustomEndpoint returns the CustomEndpoint field if non-nil, zero value otherwise.

### GetCustomEndpointOk

`func (o *GoogleCloudConfigureAuthRequest) GetCustomEndpointOk() (*map[string]interface{}, bool)`

GetCustomEndpointOk returns a tuple with the CustomEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomEndpoint

`func (o *GoogleCloudConfigureAuthRequest) SetCustomEndpoint(v map[string]interface{})`

SetCustomEndpoint sets CustomEndpoint field to given value.


### HasCustomEndpoint

`func (o *GoogleCloudConfigureAuthRequest) HasCustomEndpoint() bool`

HasCustomEndpoint returns a boolean if a field has been set.




### GetGceAlias

`func (o *GoogleCloudConfigureAuthRequest) GetGceAlias() string`

GetGceAlias returns the GceAlias field if non-nil, zero value otherwise.

### GetGceAliasOk

`func (o *GoogleCloudConfigureAuthRequest) GetGceAliasOk() (*string, bool)`

GetGceAliasOk returns a tuple with the GceAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGceAlias

`func (o *GoogleCloudConfigureAuthRequest) SetGceAlias(v string)`

SetGceAlias sets GceAlias field to given value.


### HasGceAlias

`func (o *GoogleCloudConfigureAuthRequest) HasGceAlias() bool`

HasGceAlias returns a boolean if a field has been set.




### GetGceMetadata

`func (o *GoogleCloudConfigureAuthRequest) GetGceMetadata() []string`

GetGceMetadata returns the GceMetadata field if non-nil, zero value otherwise.

### GetGceMetadataOk

`func (o *GoogleCloudConfigureAuthRequest) GetGceMetadataOk() (*[]string, bool)`

GetGceMetadataOk returns a tuple with the GceMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGceMetadata

`func (o *GoogleCloudConfigureAuthRequest) SetGceMetadata(v []string)`

SetGceMetadata sets GceMetadata field to given value.


### HasGceMetadata

`func (o *GoogleCloudConfigureAuthRequest) HasGceMetadata() bool`

HasGceMetadata returns a boolean if a field has been set.




### GetGoogleCertsEndpoint

`func (o *GoogleCloudConfigureAuthRequest) GetGoogleCertsEndpoint() string`

GetGoogleCertsEndpoint returns the GoogleCertsEndpoint field if non-nil, zero value otherwise.

### GetGoogleCertsEndpointOk

`func (o *GoogleCloudConfigureAuthRequest) GetGoogleCertsEndpointOk() (*string, bool)`

GetGoogleCertsEndpointOk returns a tuple with the GoogleCertsEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoogleCertsEndpoint

`func (o *GoogleCloudConfigureAuthRequest) SetGoogleCertsEndpoint(v string)`

SetGoogleCertsEndpoint sets GoogleCertsEndpoint field to given value.


### HasGoogleCertsEndpoint

`func (o *GoogleCloudConfigureAuthRequest) HasGoogleCertsEndpoint() bool`

HasGoogleCertsEndpoint returns a boolean if a field has been set.




### GetIamAlias

`func (o *GoogleCloudConfigureAuthRequest) GetIamAlias() string`

GetIamAlias returns the IamAlias field if non-nil, zero value otherwise.

### GetIamAliasOk

`func (o *GoogleCloudConfigureAuthRequest) GetIamAliasOk() (*string, bool)`

GetIamAliasOk returns a tuple with the IamAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIamAlias

`func (o *GoogleCloudConfigureAuthRequest) SetIamAlias(v string)`

SetIamAlias sets IamAlias field to given value.


### HasIamAlias

`func (o *GoogleCloudConfigureAuthRequest) HasIamAlias() bool`

HasIamAlias returns a boolean if a field has been set.




### GetIamMetadata

`func (o *GoogleCloudConfigureAuthRequest) GetIamMetadata() []string`

GetIamMetadata returns the IamMetadata field if non-nil, zero value otherwise.

### GetIamMetadataOk

`func (o *GoogleCloudConfigureAuthRequest) GetIamMetadataOk() (*[]string, bool)`

GetIamMetadataOk returns a tuple with the IamMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIamMetadata

`func (o *GoogleCloudConfigureAuthRequest) SetIamMetadata(v []string)`

SetIamMetadata sets IamMetadata field to given value.


### HasIamMetadata

`func (o *GoogleCloudConfigureAuthRequest) HasIamMetadata() bool`

HasIamMetadata returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


