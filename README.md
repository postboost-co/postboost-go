# PostBoost Go SDK

Official Go client for the [PostBoost API](https://postboost.co/docs/api).

## Install

```bash
go get github.com/postboost-co/postboost-go
```

| | |
|---|---|
| **pkg.go.dev** | [pkg.go.dev/github.com/postboost-co/postboost-go](https://pkg.go.dev/github.com/postboost-co/postboost-go) |
| **GitHub** | [postboost-co/postboost-go](https://github.com/postboost-co/postboost-go) |
| **Docs** | [postboost.co/docs/api](https://postboost.co/docs/api) |
| **Version** | v1.8.0 |

## Quick start

```go
import postboost "github.com/postboost-co/postboost-go"

cfg := postboost.NewConfiguration()
cfg.AddDefaultHeader("Authorization", "Bearer "+apiToken)
client := postboost.NewAPIClient(cfg)

posts, _, err := client.PostsAPI.ListPosts(ctx, "YOUR_WORKSPACE_UUID").Execute()
```

---

## Documentation for API Endpoints

All URIs are relative to *https://postboost.co/app/api*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AIAPI* | [**BlogToSocial**](docs/AIAPI.md#blogtosocial) | **Post** /{workspaceUuid}/ai/blog-to-social | Generate social media captions from a blog post
*AIAPI* | [**ImageAltText**](docs/AIAPI.md#imagealttext) | **Post** /{workspaceUuid}/ai/image-alt-text | Generate alt text for a media image using AI
*AIAPI* | [**ImageEdit**](docs/AIAPI.md#imageedit) | **Post** /{workspaceUuid}/ai/image-edit | Edit an existing media image using AI
*AIAPI* | [**ImageGenerate**](docs/AIAPI.md#imagegenerate) | **Post** /{workspaceUuid}/ai/image-generate | Generate social media images from a caption
*AIAPI* | [**ImagePrompt**](docs/AIAPI.md#imageprompt) | **Post** /{workspaceUuid}/ai/image-prompt | Build an optimized image prompt from a social media caption
*AIAPI* | [**ImageVariations**](docs/AIAPI.md#imagevariations) | **Post** /{workspaceUuid}/ai/image-variations | Generate variations of an existing media image
*AccountsAPI* | [**GetAccount**](docs/AccountsAPI.md#getaccount) | **Get** /{workspaceUuid}/accounts/{accountUuid} | Get account
*AccountsAPI* | [**ListAccounts**](docs/AccountsAPI.md#listaccounts) | **Get** /{workspaceUuid}/accounts | List accounts
*AnalyticsAPI* | [**GetAccountAnalytics**](docs/AnalyticsAPI.md#getaccountanalytics) | **Get** /{workspaceUuid}/analytics/accounts/{accountUuid} | Get account analytics
*AnalyticsAPI* | [**GetAnalyticsSummary**](docs/AnalyticsAPI.md#getanalyticssummary) | **Get** /{workspaceUuid}/analytics | Get analytics summary
*AnalyticsAPI* | [**GetBestPostingTimes**](docs/AnalyticsAPI.md#getbestpostingtimes) | **Get** /{workspaceUuid}/analytics/best-times | Get best posting times
*AnalyticsAPI* | [**GetPostAnalytics_0**](docs/AnalyticsAPI.md#getpostanalytics_0) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
*AnalyticsAPI* | [**GetPostingTimes**](docs/AnalyticsAPI.md#getpostingtimes) | **Get** /{workspaceUuid}/analytics/posting-times | Get posting times heatmap
*MediaAPI* | [**AbortChunkedUpload**](docs/MediaAPI.md#abortchunkedupload) | **Delete** /{workspaceUuid}/media/chunked/{uploadUuid} | Abort chunked upload
*MediaAPI* | [**CompleteChunkedUpload**](docs/MediaAPI.md#completechunkedupload) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/complete | Complete chunked upload
*MediaAPI* | [**CreateMediaFolder**](docs/MediaAPI.md#createmediafolder) | **Post** /{workspaceUuid}/media/folders | Create media folder
*MediaAPI* | [**DeleteMediaBulk**](docs/MediaAPI.md#deletemediabulk) | **Delete** /{workspaceUuid}/media | Delete media (bulk)
*MediaAPI* | [**DeleteMediaFolder**](docs/MediaAPI.md#deletemediafolder) | **Delete** /{workspaceUuid}/media/folders/{folderUuid} | Delete media folder
*MediaAPI* | [**GetMedia**](docs/MediaAPI.md#getmedia) | **Get** /{workspaceUuid}/media/{mediaUuid} | Get media
*MediaAPI* | [**GetRemoteUploadStatus**](docs/MediaAPI.md#getremoteuploadstatus) | **Get** /{workspaceUuid}/media/remote/{downloadId}/status | Get remote upload status
*MediaAPI* | [**InitiateChunkedUpload**](docs/MediaAPI.md#initiatechunkedupload) | **Post** /{workspaceUuid}/media/chunked/initiate | Initiate chunked upload
*MediaAPI* | [**InitiateRemoteUpload**](docs/MediaAPI.md#initiateremoteupload) | **Post** /{workspaceUuid}/media/remote/initiate | Initiate remote upload
*MediaAPI* | [**ListMedia**](docs/MediaAPI.md#listmedia) | **Get** /{workspaceUuid}/media | List media
*MediaAPI* | [**ListMediaFolders**](docs/MediaAPI.md#listmediafolders) | **Get** /{workspaceUuid}/media/folders | List media folders
*MediaAPI* | [**UpdateMedia**](docs/MediaAPI.md#updatemedia) | **Put** /{workspaceUuid}/media/{mediaUuid} | Update media
*MediaAPI* | [**UpdateMediaFolder**](docs/MediaAPI.md#updatemediafolder) | **Put** /{workspaceUuid}/media/folders/{folderUuid} | Update media folder
*MediaAPI* | [**UploadChunk**](docs/MediaAPI.md#uploadchunk) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/upload | Upload a chunk
*MediaAPI* | [**UploadMedia**](docs/MediaAPI.md#uploadmedia) | **Post** /{workspaceUuid}/media | Upload media (binary)
*MentionsAPI* | [**CreateMention**](docs/MentionsAPI.md#createmention) | **Post** /{workspaceUuid}/mentions | Create mention
*MentionsAPI* | [**DeleteMention**](docs/MentionsAPI.md#deletemention) | **Delete** /{workspaceUuid}/mentions/{mentionId} | Delete mention
*MentionsAPI* | [**GetMention**](docs/MentionsAPI.md#getmention) | **Get** /{workspaceUuid}/mentions/{mentionId} | Get mention
*MentionsAPI* | [**ListMentions**](docs/MentionsAPI.md#listmentions) | **Get** /{workspaceUuid}/mentions | List mentions
*MentionsAPI* | [**UpdateMention**](docs/MentionsAPI.md#updatemention) | **Put** /{workspaceUuid}/mentions/{mentionId} | Update mention
*PostsAPI* | [**AddPostToQueue**](docs/PostsAPI.md#addposttoqueue) | **Post** /{workspaceUuid}/posts/add-to-queue/{postUuid} | Add post to queue
*PostsAPI* | [**ApprovePost**](docs/PostsAPI.md#approvepost) | **Post** /{workspaceUuid}/posts/approve/{postUuid} | Approve post
*PostsAPI* | [**CreatePost**](docs/PostsAPI.md#createpost) | **Post** /{workspaceUuid}/posts | Create post
*PostsAPI* | [**DeletePost**](docs/PostsAPI.md#deletepost) | **Delete** /{workspaceUuid}/posts/{postUuid} | Delete post
*PostsAPI* | [**DeletePostsBulk**](docs/PostsAPI.md#deletepostsbulk) | **Delete** /{workspaceUuid}/posts | Delete posts (bulk)
*PostsAPI* | [**GetPost**](docs/PostsAPI.md#getpost) | **Get** /{workspaceUuid}/posts/{postUuid} | Get post
*PostsAPI* | [**GetPostAnalytics**](docs/PostsAPI.md#getpostanalytics) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
*PostsAPI* | [**ListPosts**](docs/PostsAPI.md#listposts) | **Get** /{workspaceUuid}/posts | List posts
*PostsAPI* | [**RetryPostAccount**](docs/PostsAPI.md#retrypostaccount) | **Post** /{workspaceUuid}/posts/retry/{postUuid}/{accountUuid} | Retry publishing to one account
*PostsAPI* | [**SchedulePost**](docs/PostsAPI.md#schedulepost) | **Post** /{workspaceUuid}/posts/schedule/{postUuid} | Schedule post
*PostsAPI* | [**UpdatePost**](docs/PostsAPI.md#updatepost) | **Put** /{workspaceUuid}/posts/{postUuid} | Update post
*ReceiptsAPI* | [**CreateReceipt**](docs/ReceiptsAPI.md#createreceipt) | **Post** /panel/receipts | Create receipt
*ReceiptsAPI* | [**DeleteReceipt**](docs/ReceiptsAPI.md#deletereceipt) | **Delete** /panel/receipts/{receiptUuid} | Delete receipt
*ReceiptsAPI* | [**DeleteReceiptsBulk**](docs/ReceiptsAPI.md#deletereceiptsbulk) | **Delete** /panel/receipts | Delete receipts (bulk)
*ReceiptsAPI* | [**GetReceipt**](docs/ReceiptsAPI.md#getreceipt) | **Get** /panel/receipts/{receiptUuid} | Get receipt
*ReceiptsAPI* | [**ListReceipts**](docs/ReceiptsAPI.md#listreceipts) | **Get** /panel/receipts | List receipts
*ReceiptsAPI* | [**UpdateReceipt**](docs/ReceiptsAPI.md#updatereceipt) | **Put** /panel/receipts/{receiptUuid} | Update receipt
*SubscriptionsAPI* | [**AddGenericSubscription**](docs/SubscriptionsAPI.md#addgenericsubscription) | **Post** /panel/workspaces/{workspaceUuid}/subscription/generic | Add generic subscription
*SubscriptionsAPI* | [**CancelSubscription**](docs/SubscriptionsAPI.md#cancelsubscription) | **Post** /panel/workspaces/{workspaceUuid}/subscription/cancel | Cancel subscription
*SubscriptionsAPI* | [**ChangeSubscriptionPlan**](docs/SubscriptionsAPI.md#changesubscriptionplan) | **Put** /panel/workspaces/{workspaceUuid}/subscription/change-plan | Change subscription plan
*SubscriptionsAPI* | [**CheckoutSubscription**](docs/SubscriptionsAPI.md#checkoutsubscription) | **Post** /panel/workspaces/{workspaceUuid}/subscription/new | New subscription checkout
*SubscriptionsAPI* | [**CreateSubscription**](docs/SubscriptionsAPI.md#createsubscription) | **Post** /panel/workspaces/{workspaceUuid}/subscription | Create subscription
*SubscriptionsAPI* | [**DeleteSubscription**](docs/SubscriptionsAPI.md#deletesubscription) | **Delete** /panel/workspaces/{workspaceUuid}/subscription | Delete subscription
*SubscriptionsAPI* | [**GetSubscription**](docs/SubscriptionsAPI.md#getsubscription) | **Get** /panel/workspaces/{workspaceUuid}/subscription | Get subscription
*SubscriptionsAPI* | [**RemoveGenericSubscription**](docs/SubscriptionsAPI.md#removegenericsubscription) | **Delete** /panel/workspaces/{workspaceUuid}/subscription/generic | Remove generic subscription
*SubscriptionsAPI* | [**ResumeSubscription**](docs/SubscriptionsAPI.md#resumesubscription) | **Post** /panel/workspaces/{workspaceUuid}/subscription/resume | Resume subscription
*SubscriptionsAPI* | [**UpdateSubscription**](docs/SubscriptionsAPI.md#updatesubscription) | **Put** /panel/workspaces/{workspaceUuid}/subscription | Update subscription
*TagsAPI* | [**CreateTag**](docs/TagsAPI.md#createtag) | **Post** /{workspaceUuid}/tags | Create tag
*TagsAPI* | [**DeleteTag**](docs/TagsAPI.md#deletetag) | **Delete** /{workspaceUuid}/tags/{tagUuid} | Delete tag
*TagsAPI* | [**GetTag**](docs/TagsAPI.md#gettag) | **Get** /{workspaceUuid}/tags/{tagUuid} | Get tag
*TagsAPI* | [**ListTags**](docs/TagsAPI.md#listtags) | **Get** /{workspaceUuid}/tags | List tags
*TagsAPI* | [**UpdateTag**](docs/TagsAPI.md#updatetag) | **Put** /{workspaceUuid}/tags/{tagUuid} | Update tag
*UsersAPI* | [**CreateUser**](docs/UsersAPI.md#createuser) | **Post** /panel/users | Create user
*UsersAPI* | [**DeleteUser**](docs/UsersAPI.md#deleteuser) | **Delete** /panel/users/{userId} | Delete user
*UsersAPI* | [**DeleteUsersBulk**](docs/UsersAPI.md#deleteusersbulk) | **Delete** /panel/users | Delete users (bulk)
*UsersAPI* | [**GetUser**](docs/UsersAPI.md#getuser) | **Get** /panel/users/{userId} | Get user
*UsersAPI* | [**ListUsers**](docs/UsersAPI.md#listusers) | **Get** /panel/users | List users
*UsersAPI* | [**UpdateUser**](docs/UsersAPI.md#updateuser) | **Put** /panel/users/{userId} | Update user
*WorkspacesAPI* | [**AddUserToWorkspace**](docs/WorkspacesAPI.md#addusertoworkspace) | **Post** /panel/workspaces/{workspaceUuid}/users | Add user to workspace
*WorkspacesAPI* | [**CreateWorkspace**](docs/WorkspacesAPI.md#createworkspace) | **Post** /panel/workspaces | Create workspace
*WorkspacesAPI* | [**DeleteWorkspace**](docs/WorkspacesAPI.md#deleteworkspace) | **Delete** /panel/workspaces/{workspaceUuid} | Delete workspace
*WorkspacesAPI* | [**DeleteWorkspacesBulk**](docs/WorkspacesAPI.md#deleteworkspacesbulk) | **Delete** /panel/workspaces | Delete workspaces (bulk)
*WorkspacesAPI* | [**GetWorkspace**](docs/WorkspacesAPI.md#getworkspace) | **Get** /panel/workspaces/{workspaceUuid} | Get workspace
*WorkspacesAPI* | [**GetWorkspaceAICredits**](docs/WorkspacesAPI.md#getworkspaceaicredits) | **Get** /panel/workspaces/{workspaceUuid}/ai-credits | Get workspace AI credits
*WorkspacesAPI* | [**ListMyWorkspaces**](docs/WorkspacesAPI.md#listmyworkspaces) | **Get** /workspaces | List my workspaces
*WorkspacesAPI* | [**ListWorkspaces**](docs/WorkspacesAPI.md#listworkspaces) | **Get** /panel/workspaces | List workspaces
*WorkspacesAPI* | [**RemoveUserFromWorkspace**](docs/WorkspacesAPI.md#removeuserfromworkspace) | **Delete** /panel/workspaces/{workspaceUuid}/users | Remove user from workspace
*WorkspacesAPI* | [**UpdateWorkspace**](docs/WorkspacesAPI.md#updateworkspace) | **Put** /panel/workspaces/{workspaceUuid} | Update workspace
*WorkspacesAPI* | [**UpdateWorkspaceUser**](docs/WorkspacesAPI.md#updateworkspaceuser) | **Put** /panel/workspaces/{workspaceUuid}/users | Update user role in workspace
