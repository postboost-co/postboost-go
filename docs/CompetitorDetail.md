# CompetitorDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**AccountId** | **int32** |  | 
**Username** | **string** |  | 
**Name** | Pointer to **string** |  | [optional] 
**Image** | Pointer to **string** |  | [optional] 
**FollowersCount** | Pointer to **int32** |  | [optional] 
**MediaCount** | Pointer to **int32** |  | [optional] 
**AvgEngagement** | **int32** | Average likes plus comments per imported post. | 
**LastSnapshotDate** | Pointer to **string** |  | [optional] 
**Snapshots** | [**[]CompetitorSnapshot**](CompetitorSnapshot.md) |  | 
**RecentMedia** | [**[]CompetitorMedia**](CompetitorMedia.md) |  | 

## Methods

### NewCompetitorDetail

`func NewCompetitorDetail(id int32, accountId int32, username string, avgEngagement int32, snapshots []CompetitorSnapshot, recentMedia []CompetitorMedia, ) *CompetitorDetail`

NewCompetitorDetail instantiates a new CompetitorDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorDetailWithDefaults

`func NewCompetitorDetailWithDefaults() *CompetitorDetail`

NewCompetitorDetailWithDefaults instantiates a new CompetitorDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorDetail) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorDetail) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorDetail) SetId(v int32)`

SetId sets Id field to given value.


### GetAccountId

`func (o *CompetitorDetail) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *CompetitorDetail) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *CompetitorDetail) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetUsername

`func (o *CompetitorDetail) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *CompetitorDetail) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *CompetitorDetail) SetUsername(v string)`

SetUsername sets Username field to given value.


### GetName

`func (o *CompetitorDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CompetitorDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CompetitorDetail) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CompetitorDetail) HasName() bool`

HasName returns a boolean if a field has been set.

### GetImage

`func (o *CompetitorDetail) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *CompetitorDetail) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *CompetitorDetail) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *CompetitorDetail) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetFollowersCount

`func (o *CompetitorDetail) GetFollowersCount() int32`

GetFollowersCount returns the FollowersCount field if non-nil, zero value otherwise.

### GetFollowersCountOk

`func (o *CompetitorDetail) GetFollowersCountOk() (*int32, bool)`

GetFollowersCountOk returns a tuple with the FollowersCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowersCount

`func (o *CompetitorDetail) SetFollowersCount(v int32)`

SetFollowersCount sets FollowersCount field to given value.

### HasFollowersCount

`func (o *CompetitorDetail) HasFollowersCount() bool`

HasFollowersCount returns a boolean if a field has been set.

### GetMediaCount

`func (o *CompetitorDetail) GetMediaCount() int32`

GetMediaCount returns the MediaCount field if non-nil, zero value otherwise.

### GetMediaCountOk

`func (o *CompetitorDetail) GetMediaCountOk() (*int32, bool)`

GetMediaCountOk returns a tuple with the MediaCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaCount

`func (o *CompetitorDetail) SetMediaCount(v int32)`

SetMediaCount sets MediaCount field to given value.

### HasMediaCount

`func (o *CompetitorDetail) HasMediaCount() bool`

HasMediaCount returns a boolean if a field has been set.

### GetAvgEngagement

`func (o *CompetitorDetail) GetAvgEngagement() int32`

GetAvgEngagement returns the AvgEngagement field if non-nil, zero value otherwise.

### GetAvgEngagementOk

`func (o *CompetitorDetail) GetAvgEngagementOk() (*int32, bool)`

GetAvgEngagementOk returns a tuple with the AvgEngagement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgEngagement

`func (o *CompetitorDetail) SetAvgEngagement(v int32)`

SetAvgEngagement sets AvgEngagement field to given value.


### GetLastSnapshotDate

`func (o *CompetitorDetail) GetLastSnapshotDate() string`

GetLastSnapshotDate returns the LastSnapshotDate field if non-nil, zero value otherwise.

### GetLastSnapshotDateOk

`func (o *CompetitorDetail) GetLastSnapshotDateOk() (*string, bool)`

GetLastSnapshotDateOk returns a tuple with the LastSnapshotDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSnapshotDate

`func (o *CompetitorDetail) SetLastSnapshotDate(v string)`

SetLastSnapshotDate sets LastSnapshotDate field to given value.

### HasLastSnapshotDate

`func (o *CompetitorDetail) HasLastSnapshotDate() bool`

HasLastSnapshotDate returns a boolean if a field has been set.

### GetSnapshots

`func (o *CompetitorDetail) GetSnapshots() []CompetitorSnapshot`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *CompetitorDetail) GetSnapshotsOk() (*[]CompetitorSnapshot, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *CompetitorDetail) SetSnapshots(v []CompetitorSnapshot)`

SetSnapshots sets Snapshots field to given value.


### GetRecentMedia

`func (o *CompetitorDetail) GetRecentMedia() []CompetitorMedia`

GetRecentMedia returns the RecentMedia field if non-nil, zero value otherwise.

### GetRecentMediaOk

`func (o *CompetitorDetail) GetRecentMediaOk() (*[]CompetitorMedia, bool)`

GetRecentMediaOk returns a tuple with the RecentMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentMedia

`func (o *CompetitorDetail) SetRecentMedia(v []CompetitorMedia)`

SetRecentMedia sets RecentMedia field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


