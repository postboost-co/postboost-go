# Competitor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**AccountId** | **int32** |  | 
**Username** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**Image** | Pointer to **NullableString** |  | [optional] 
**FollowersCount** | Pointer to **NullableInt32** |  | [optional] 
**MediaCount** | Pointer to **NullableInt32** |  | [optional] 
**AvgEngagement** | **int32** | Average likes plus comments per imported post. | 
**LastSnapshotDate** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCompetitor

`func NewCompetitor(id int32, accountId int32, username string, avgEngagement int32, ) *Competitor`

NewCompetitor instantiates a new Competitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorWithDefaults

`func NewCompetitorWithDefaults() *Competitor`

NewCompetitorWithDefaults instantiates a new Competitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Competitor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Competitor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Competitor) SetId(v int32)`

SetId sets Id field to given value.


### GetAccountId

`func (o *Competitor) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *Competitor) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *Competitor) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetUsername

`func (o *Competitor) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *Competitor) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *Competitor) SetUsername(v string)`

SetUsername sets Username field to given value.


### GetName

`func (o *Competitor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Competitor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Competitor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Competitor) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *Competitor) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *Competitor) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetImage

`func (o *Competitor) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Competitor) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Competitor) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *Competitor) HasImage() bool`

HasImage returns a boolean if a field has been set.

### SetImageNil

`func (o *Competitor) SetImageNil(b bool)`

 SetImageNil sets the value for Image to be an explicit nil

### UnsetImage
`func (o *Competitor) UnsetImage()`

UnsetImage ensures that no value is present for Image, not even an explicit nil
### GetFollowersCount

`func (o *Competitor) GetFollowersCount() int32`

GetFollowersCount returns the FollowersCount field if non-nil, zero value otherwise.

### GetFollowersCountOk

`func (o *Competitor) GetFollowersCountOk() (*int32, bool)`

GetFollowersCountOk returns a tuple with the FollowersCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowersCount

`func (o *Competitor) SetFollowersCount(v int32)`

SetFollowersCount sets FollowersCount field to given value.

### HasFollowersCount

`func (o *Competitor) HasFollowersCount() bool`

HasFollowersCount returns a boolean if a field has been set.

### SetFollowersCountNil

`func (o *Competitor) SetFollowersCountNil(b bool)`

 SetFollowersCountNil sets the value for FollowersCount to be an explicit nil

### UnsetFollowersCount
`func (o *Competitor) UnsetFollowersCount()`

UnsetFollowersCount ensures that no value is present for FollowersCount, not even an explicit nil
### GetMediaCount

`func (o *Competitor) GetMediaCount() int32`

GetMediaCount returns the MediaCount field if non-nil, zero value otherwise.

### GetMediaCountOk

`func (o *Competitor) GetMediaCountOk() (*int32, bool)`

GetMediaCountOk returns a tuple with the MediaCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaCount

`func (o *Competitor) SetMediaCount(v int32)`

SetMediaCount sets MediaCount field to given value.

### HasMediaCount

`func (o *Competitor) HasMediaCount() bool`

HasMediaCount returns a boolean if a field has been set.

### SetMediaCountNil

`func (o *Competitor) SetMediaCountNil(b bool)`

 SetMediaCountNil sets the value for MediaCount to be an explicit nil

### UnsetMediaCount
`func (o *Competitor) UnsetMediaCount()`

UnsetMediaCount ensures that no value is present for MediaCount, not even an explicit nil
### GetAvgEngagement

`func (o *Competitor) GetAvgEngagement() int32`

GetAvgEngagement returns the AvgEngagement field if non-nil, zero value otherwise.

### GetAvgEngagementOk

`func (o *Competitor) GetAvgEngagementOk() (*int32, bool)`

GetAvgEngagementOk returns a tuple with the AvgEngagement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEngagement

`func (o *Competitor) SetAvgEngagement(v int32)`

SetAvgEngagement sets AvgEngagement field to given value.


### GetLastSnapshotDate

`func (o *Competitor) GetLastSnapshotDate() string`

GetLastSnapshotDate returns the LastSnapshotDate field if non-nil, zero value otherwise.

### GetLastSnapshotDateOk

`func (o *Competitor) GetLastSnapshotDateOk() (*string, bool)`

GetLastSnapshotDateOk returns a tuple with the LastSnapshotDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSnapshotDate

`func (o *Competitor) SetLastSnapshotDate(v string)`

SetLastSnapshotDate sets LastSnapshotDate field to given value.

### HasLastSnapshotDate

`func (o *Competitor) HasLastSnapshotDate() bool`

HasLastSnapshotDate returns a boolean if a field has been set.

### SetLastSnapshotDateNil

`func (o *Competitor) SetLastSnapshotDateNil(b bool)`

 SetLastSnapshotDateNil sets the value for LastSnapshotDate to be an explicit nil

### UnsetLastSnapshotDate
`func (o *Competitor) UnsetLastSnapshotDate()`

UnsetLastSnapshotDate ensures that no value is present for LastSnapshotDate, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


