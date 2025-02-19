# GenerateRandomRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bytes** | Pointer to **int32** | The number of bytes to generate (POST body parameter). Defaults to 32 (256 bits). | [optional] [default to 32]
**Format** | Pointer to **string** | Encoding format to use. Can be \&quot;hex\&quot; or \&quot;base64\&quot;. Defaults to \&quot;base64\&quot;. | [optional] [default to "base64"]
**Source** | Pointer to **string** | Which system to source random data from, ether \&quot;platform\&quot;, \&quot;seal\&quot;, or \&quot;all\&quot;. | [optional] [default to "platform"]
**Urlbytes** | Pointer to **string** | The number of bytes to generate (POST URL parameter) | [optional] 



## Methods


### NewGenerateRandomRequest

`func NewGenerateRandomRequest() *GenerateRandomRequest`

NewGenerateRandomRequest instantiates a new GenerateRandomRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenerateRandomRequestWithDefaults

`func NewGenerateRandomRequestWithDefaults() *GenerateRandomRequest`

NewGenerateRandomRequestWithDefaults instantiates a new GenerateRandomRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetBytes

`func (o *GenerateRandomRequest) GetBytes() int32`

GetBytes returns the Bytes field if non-nil, zero value otherwise.

### GetBytesOk

`func (o *GenerateRandomRequest) GetBytesOk() (*int32, bool)`

GetBytesOk returns a tuple with the Bytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytes

`func (o *GenerateRandomRequest) SetBytes(v int32)`

SetBytes sets Bytes field to given value.


### HasBytes

`func (o *GenerateRandomRequest) HasBytes() bool`

HasBytes returns a boolean if a field has been set.




### GetFormat

`func (o *GenerateRandomRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *GenerateRandomRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *GenerateRandomRequest) SetFormat(v string)`

SetFormat sets Format field to given value.


### HasFormat

`func (o *GenerateRandomRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.




### GetSource

`func (o *GenerateRandomRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *GenerateRandomRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *GenerateRandomRequest) SetSource(v string)`

SetSource sets Source field to given value.


### HasSource

`func (o *GenerateRandomRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.




### GetUrlbytes

`func (o *GenerateRandomRequest) GetUrlbytes() string`

GetUrlbytes returns the Urlbytes field if non-nil, zero value otherwise.

### GetUrlbytesOk

`func (o *GenerateRandomRequest) GetUrlbytesOk() (*string, bool)`

GetUrlbytesOk returns a tuple with the Urlbytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlbytes

`func (o *GenerateRandomRequest) SetUrlbytes(v string)`

SetUrlbytes sets Urlbytes field to given value.


### HasUrlbytes

`func (o *GenerateRandomRequest) HasUrlbytes() bool`

HasUrlbytes returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


