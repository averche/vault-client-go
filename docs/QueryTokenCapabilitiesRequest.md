# QueryTokenCapabilitiesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Path** | Pointer to **[]string** | Use &#x27;paths&#x27; instead. | [optional] 
**Paths** | Pointer to **[]string** | Paths on which capabilities are being queried. | [optional] 
**Token** | Pointer to **string** | Token for which capabilities are being queried. | [optional] 



## Methods


### NewQueryTokenCapabilitiesRequest

`func NewQueryTokenCapabilitiesRequest() *QueryTokenCapabilitiesRequest`

NewQueryTokenCapabilitiesRequest instantiates a new QueryTokenCapabilitiesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryTokenCapabilitiesRequestWithDefaults

`func NewQueryTokenCapabilitiesRequestWithDefaults() *QueryTokenCapabilitiesRequest`

NewQueryTokenCapabilitiesRequestWithDefaults instantiates a new QueryTokenCapabilitiesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetPath

`func (o *QueryTokenCapabilitiesRequest) GetPath() []string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *QueryTokenCapabilitiesRequest) GetPathOk() (*[]string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *QueryTokenCapabilitiesRequest) SetPath(v []string)`

SetPath sets Path field to given value.


### HasPath

`func (o *QueryTokenCapabilitiesRequest) HasPath() bool`

HasPath returns a boolean if a field has been set.




### GetPaths

`func (o *QueryTokenCapabilitiesRequest) GetPaths() []string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *QueryTokenCapabilitiesRequest) GetPathsOk() (*[]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *QueryTokenCapabilitiesRequest) SetPaths(v []string)`

SetPaths sets Paths field to given value.


### HasPaths

`func (o *QueryTokenCapabilitiesRequest) HasPaths() bool`

HasPaths returns a boolean if a field has been set.




### GetToken

`func (o *QueryTokenCapabilitiesRequest) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *QueryTokenCapabilitiesRequest) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *QueryTokenCapabilitiesRequest) SetToken(v string)`

SetToken sets Token field to given value.


### HasToken

`func (o *QueryTokenCapabilitiesRequest) HasToken() bool`

HasToken returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


