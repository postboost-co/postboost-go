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
| **Version** | v1.19.0 |

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
*AIAPI* | [**DeleteBrandVoice**](docs/AIAPI.md#deletebrandvoice) | **Delete** /{workspaceUuid}/brand-voice | Delete the brand voice
*AIAPI* | [**GetAIUsage**](docs/AIAPI.md#getaiusage) | **Get** /{workspaceUuid}/usage/ai | AI credit usage
*AIAPI* | [**GetBrandVoice**](docs/AIAPI.md#getbrandvoice) | **Get** /{workspaceUuid}/brand-voice | Get the brand voice
*AIAPI* | [**GetRepurposeRun**](docs/AIAPI.md#getrepurposerun) | **Get** /{workspaceUuid}/ai/repurpose/runs/{runId} | Get a repurpose run
*AIAPI* | [**ImageAltText**](docs/AIAPI.md#imagealttext) | **Post** /{workspaceUuid}/ai/image-alt-text | Generate alt text for a media image using AI
*AIAPI* | [**ImageEdit**](docs/AIAPI.md#imageedit) | **Post** /{workspaceUuid}/ai/image-edit | Edit an existing media image using AI
*AIAPI* | [**ImageGenerate**](docs/AIAPI.md#imagegenerate) | **Post** /{workspaceUuid}/ai/image-generate | Generate social media images from a caption
*AIAPI* | [**ImagePrompt**](docs/AIAPI.md#imageprompt) | **Post** /{workspaceUuid}/ai/image-prompt | Build an optimized image prompt from a social media caption
*AIAPI* | [**ImageVariations**](docs/AIAPI.md#imagevariations) | **Post** /{workspaceUuid}/ai/image-variations | Generate variations of an existing media image
*AIAPI* | [**LearnBrandVoice**](docs/AIAPI.md#learnbrandvoice) | **Post** /{workspaceUuid}/brand-voice/learn | Learn a brand voice from past posts
*AIAPI* | [**RepurposeContent**](docs/AIAPI.md#repurposecontent) | **Post** /{workspaceUuid}/ai/repurpose | Repurpose long-form content into a draft post set with a carousel
*AIAPI* | [**UpdateBrandVoice**](docs/AIAPI.md#updatebrandvoice) | **Put** /{workspaceUuid}/brand-voice | Create or update the brand voice
*AccountGroupsAPI* | [**CreateAccountGroup**](docs/AccountGroupsAPI.md#createaccountgroup) | **Post** /{workspaceUuid}/account-groups | Create an account group
*AccountGroupsAPI* | [**DeleteAccountGroup**](docs/AccountGroupsAPI.md#deleteaccountgroup) | **Delete** /{workspaceUuid}/account-groups/{accountGroupUuid} | Delete an account group
*AccountGroupsAPI* | [**GetAccountGroup**](docs/AccountGroupsAPI.md#getaccountgroup) | **Get** /{workspaceUuid}/account-groups/{accountGroupUuid} | Get an account group
*AccountGroupsAPI* | [**ListAccountGroups**](docs/AccountGroupsAPI.md#listaccountgroups) | **Get** /{workspaceUuid}/account-groups | List account groups
*AccountGroupsAPI* | [**UpdateAccountGroup**](docs/AccountGroupsAPI.md#updateaccountgroup) | **Put** /{workspaceUuid}/account-groups/{accountGroupUuid} | Update an account group
*AccountsAPI* | [**ConnectChannel**](docs/AccountsAPI.md#connectchannel) | **Post** /{workspaceUuid}/accounts/connect/{provider} | Connect a Telegram, Discord or Slack channel
*AccountsAPI* | [**CreateReconnectLink**](docs/AccountsAPI.md#createreconnectlink) | **Post** /{workspaceUuid}/accounts/{accountUuid}/reconnect-links | Create a reconnect link
*AccountsAPI* | [**GetAccount**](docs/AccountsAPI.md#getaccount) | **Get** /{workspaceUuid}/accounts/{accountUuid} | Get account
*AccountsAPI* | [**GetAccountHealth**](docs/AccountsAPI.md#getaccounthealth) | **Get** /{workspaceUuid}/account-health | Account health
*AccountsAPI* | [**ListAccounts**](docs/AccountsAPI.md#listaccounts) | **Get** /{workspaceUuid}/accounts | List accounts
*ActivityAPI* | [**ListApiActivity**](docs/ActivityAPI.md#listapiactivity) | **Get** /{workspaceUuid}/activity | List API activity
*AgentsAPI* | [**ApproveAgentProposal**](docs/AgentsAPI.md#approveagentproposal) | **Post** /{workspaceUuid}/agent-proposals/{proposalUuid}/approve | Approve and apply an agent proposal
*AgentsAPI* | [**CreateAgent**](docs/AgentsAPI.md#createagent) | **Post** /{workspaceUuid}/agents | Switch on a background agent
*AgentsAPI* | [**DeleteAgent**](docs/AgentsAPI.md#deleteagent) | **Delete** /{workspaceUuid}/agents/{agentUuid} | Delete a background agent
*AgentsAPI* | [**GetAgentRun**](docs/AgentsAPI.md#getagentrun) | **Get** /{workspaceUuid}/agent-runs/{runUuid} | Get an agent run with its proposals
*AgentsAPI* | [**ListAgentProposals**](docs/AgentsAPI.md#listagentproposals) | **Get** /{workspaceUuid}/agent-proposals | List agent proposals (approval queue)
*AgentsAPI* | [**ListAgentRuns**](docs/AgentsAPI.md#listagentruns) | **Get** /{workspaceUuid}/agents/{agentUuid}/runs | Run history of an agent
*AgentsAPI* | [**ListAgents**](docs/AgentsAPI.md#listagents) | **Get** /{workspaceUuid}/agents | List background agents
*AgentsAPI* | [**RejectAgentProposal**](docs/AgentsAPI.md#rejectagentproposal) | **Post** /{workspaceUuid}/agent-proposals/{proposalUuid}/reject | Reject an agent proposal
*AgentsAPI* | [**RunAgent**](docs/AgentsAPI.md#runagent) | **Post** /{workspaceUuid}/agents/{agentUuid}/run | Run a background agent now
*AgentsAPI* | [**UpdateAgent**](docs/AgentsAPI.md#updateagent) | **Put** /{workspaceUuid}/agents/{agentUuid} | Update a background agent
*AnalyticsAPI* | [**CreateReportExport**](docs/AnalyticsAPI.md#createreportexport) | **Post** /{workspaceUuid}/reports/exports | Create a report export
*AnalyticsAPI* | [**DownloadReportExport**](docs/AnalyticsAPI.md#downloadreportexport) | **Get** /{workspaceUuid}/reports/exports/{exportUuid}/download | Download a report file
*AnalyticsAPI* | [**GetAccountAnalytics**](docs/AnalyticsAPI.md#getaccountanalytics) | **Get** /{workspaceUuid}/analytics/accounts/{accountUuid} | Get account analytics
*AnalyticsAPI* | [**GetAnalyticsSummary**](docs/AnalyticsAPI.md#getanalyticssummary) | **Get** /{workspaceUuid}/analytics | Get analytics summary
*AnalyticsAPI* | [**GetBestPostingTimes**](docs/AnalyticsAPI.md#getbestpostingtimes) | **Get** /{workspaceUuid}/analytics/best-times | Get best posting times
*AnalyticsAPI* | [**GetPostAnalytics_0**](docs/AnalyticsAPI.md#getpostanalytics_0) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
*AnalyticsAPI* | [**GetPostingTimes**](docs/AnalyticsAPI.md#getpostingtimes) | **Get** /{workspaceUuid}/analytics/posting-times | Get posting times heatmap
*AnalyticsAPI* | [**GetReportBranding**](docs/AnalyticsAPI.md#getreportbranding) | **Get** /{workspaceUuid}/report-branding | Get the report branding
*AnalyticsAPI* | [**GetReportExport**](docs/AnalyticsAPI.md#getreportexport) | **Get** /{workspaceUuid}/reports/exports/{exportUuid} | Get a report export
*AnalyticsAPI* | [**ListReportExports**](docs/AnalyticsAPI.md#listreportexports) | **Get** /{workspaceUuid}/reports/exports | List report exports
*AnalyticsAPI* | [**UpdateReportBranding**](docs/AnalyticsAPI.md#updatereportbranding) | **Put** /{workspaceUuid}/report-branding | Update the report branding
*AnalyticsAPI* | [**UploadReportBrandingLogo**](docs/AnalyticsAPI.md#uploadreportbrandinglogo) | **Post** /{workspaceUuid}/report-branding/logo | Upload the report logo
*CompetitorsAPI* | [**AddCompetitor**](docs/CompetitorsAPI.md#addcompetitor) | **Post** /{workspaceUuid}/competitors | Track a competitor
*CompetitorsAPI* | [**DeleteCompetitor**](docs/CompetitorsAPI.md#deletecompetitor) | **Delete** /{workspaceUuid}/competitors/{competitorId} | Stop tracking a competitor
*CompetitorsAPI* | [**GetCompetitor**](docs/CompetitorsAPI.md#getcompetitor) | **Get** /{workspaceUuid}/competitors/{competitorId} | Get a competitor
*CompetitorsAPI* | [**ListCompetitors**](docs/CompetitorsAPI.md#listcompetitors) | **Get** /{workspaceUuid}/competitors | List competitors
*HashtagGroupsAPI* | [**CreateHashtagGroup**](docs/HashtagGroupsAPI.md#createhashtaggroup) | **Post** /{workspaceUuid}/hashtag-groups | Create a hashtag group
*HashtagGroupsAPI* | [**DeleteHashtagGroup**](docs/HashtagGroupsAPI.md#deletehashtaggroup) | **Delete** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Delete a hashtag group
*HashtagGroupsAPI* | [**GetHashtagGroup**](docs/HashtagGroupsAPI.md#gethashtaggroup) | **Get** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Get a hashtag group
*HashtagGroupsAPI* | [**ListHashtagGroups**](docs/HashtagGroupsAPI.md#listhashtaggroups) | **Get** /{workspaceUuid}/hashtag-groups | List hashtag groups
*HashtagGroupsAPI* | [**UpdateHashtagGroup**](docs/HashtagGroupsAPI.md#updatehashtaggroup) | **Put** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Update a hashtag group
*InboxAPI* | [**ApproveInboxReplyDraft**](docs/InboxAPI.md#approveinboxreplydraft) | **Post** /{workspaceUuid}/inbox/drafts/{draftId}/approve | Approve and send a reply draft
*InboxAPI* | [**CreateInboxReplyDraft**](docs/InboxAPI.md#createinboxreplydraft) | **Post** /{workspaceUuid}/inbox/conversations/{conversationId}/drafts | Draft a reply
*InboxAPI* | [**DeleteInboxReplyDraft**](docs/InboxAPI.md#deleteinboxreplydraft) | **Delete** /{workspaceUuid}/inbox/drafts/{draftId} | Withdraw a reply draft
*InboxAPI* | [**GetInboxConversation**](docs/InboxAPI.md#getinboxconversation) | **Get** /{workspaceUuid}/inbox/conversations/{conversationId} | Get an inbox conversation
*InboxAPI* | [**GetInboxReplyDraft**](docs/InboxAPI.md#getinboxreplydraft) | **Get** /{workspaceUuid}/inbox/drafts/{draftId} | Get a reply draft
*InboxAPI* | [**ListInboxConversations**](docs/InboxAPI.md#listinboxconversations) | **Get** /{workspaceUuid}/inbox/conversations | List inbox conversations
*InboxAPI* | [**ListInboxReplyDrafts**](docs/InboxAPI.md#listinboxreplydrafts) | **Get** /{workspaceUuid}/inbox/drafts | List reply drafts
*InboxAPI* | [**RejectInboxReplyDraft**](docs/InboxAPI.md#rejectinboxreplydraft) | **Post** /{workspaceUuid}/inbox/drafts/{draftId}/reject | Reject a reply draft
*InboxAPI* | [**UpdateInboxConversation**](docs/InboxAPI.md#updateinboxconversation) | **Patch** /{workspaceUuid}/inbox/conversations/{conversationId} | Update an inbox conversation
*InboxAPI* | [**UpdateInboxReplyDraft**](docs/InboxAPI.md#updateinboxreplydraft) | **Put** /{workspaceUuid}/inbox/drafts/{draftId} | Edit a reply draft
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
*MediaAPI* | [**UploadMediaBase64**](docs/MediaAPI.md#uploadmediabase64) | **Post** /{workspaceUuid}/media/base64 | Upload media (base64 JSON)
*MentionsAPI* | [**CreateMention**](docs/MentionsAPI.md#createmention) | **Post** /{workspaceUuid}/mentions | Create mention
*MentionsAPI* | [**DeleteMention**](docs/MentionsAPI.md#deletemention) | **Delete** /{workspaceUuid}/mentions/{mentionId} | Delete mention
*MentionsAPI* | [**GetMention**](docs/MentionsAPI.md#getmention) | **Get** /{workspaceUuid}/mentions/{mentionId} | Get mention
*MentionsAPI* | [**ListMentions**](docs/MentionsAPI.md#listmentions) | **Get** /{workspaceUuid}/mentions | List mentions
*MentionsAPI* | [**UpdateMention**](docs/MentionsAPI.md#updatemention) | **Put** /{workspaceUuid}/mentions/{mentionId} | Update mention
*PostingScheduleAPI* | [**GetPostingSchedule**](docs/PostingScheduleAPI.md#getpostingschedule) | **Get** /{workspaceUuid}/posting-schedule | Get the posting schedule
*PostingScheduleAPI* | [**GetRecommendedPostingTimes**](docs/PostingScheduleAPI.md#getrecommendedpostingtimes) | **Get** /{workspaceUuid}/posting-schedule/recommended | Get recommended posting times
*PostingScheduleAPI* | [**ListQueueSlots**](docs/PostingScheduleAPI.md#listqueueslots) | **Get** /{workspaceUuid}/queue/slots | List upcoming queue slots
*PostingScheduleAPI* | [**ResetAccountPostingSchedule**](docs/PostingScheduleAPI.md#resetaccountpostingschedule) | **Delete** /{workspaceUuid}/posting-schedule/{accountId} | Reset an account schedule
*PostingScheduleAPI* | [**UpdatePostingSchedule**](docs/PostingScheduleAPI.md#updatepostingschedule) | **Put** /{workspaceUuid}/posting-schedule | Set the posting schedule
*PostsAPI* | [**AddPostToQueue**](docs/PostsAPI.md#addposttoqueue) | **Post** /{workspaceUuid}/posts/add-to-queue/{postUuid} | Add post to queue
*PostsAPI* | [**ApprovePost**](docs/PostsAPI.md#approvepost) | **Post** /{workspaceUuid}/posts/approve/{postUuid} | Approve post
*PostsAPI* | [**CreatePost**](docs/PostsAPI.md#createpost) | **Post** /{workspaceUuid}/posts | Create post
*PostsAPI* | [**CreateRecyclingRule**](docs/PostsAPI.md#createrecyclingrule) | **Post** /{workspaceUuid}/recycling-rules | Create a recycling rule
*PostsAPI* | [**CreateRssFeed**](docs/PostsAPI.md#createrssfeed) | **Post** /{workspaceUuid}/rss-feeds | Add an RSS feed
*PostsAPI* | [**DeletePost**](docs/PostsAPI.md#deletepost) | **Delete** /{workspaceUuid}/posts/{postUuid} | Delete post
*PostsAPI* | [**DeletePostsBulk**](docs/PostsAPI.md#deletepostsbulk) | **Delete** /{workspaceUuid}/posts | Delete posts (bulk)
*PostsAPI* | [**DeleteRecyclingRule**](docs/PostsAPI.md#deleterecyclingrule) | **Delete** /{workspaceUuid}/recycling-rules/{ruleUuid} | Delete a recycling rule
*PostsAPI* | [**DeleteRssFeed**](docs/PostsAPI.md#deleterssfeed) | **Delete** /{workspaceUuid}/rss-feeds/{feedUuid} | Delete an RSS feed
*PostsAPI* | [**GetPost**](docs/PostsAPI.md#getpost) | **Get** /{workspaceUuid}/posts/{postUuid} | Get post
*PostsAPI* | [**GetPostAnalytics**](docs/PostsAPI.md#getpostanalytics) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
*PostsAPI* | [**GetRecyclingRule**](docs/PostsAPI.md#getrecyclingrule) | **Get** /{workspaceUuid}/recycling-rules/{ruleUuid} | Get a recycling rule
*PostsAPI* | [**GetRssFeed**](docs/PostsAPI.md#getrssfeed) | **Get** /{workspaceUuid}/rss-feeds/{feedUuid} | Get an RSS feed
*PostsAPI* | [**ListPosts**](docs/PostsAPI.md#listposts) | **Get** /{workspaceUuid}/posts | List posts
*PostsAPI* | [**ListRecyclingRules**](docs/PostsAPI.md#listrecyclingrules) | **Get** /{workspaceUuid}/recycling-rules | List recycling rules
*PostsAPI* | [**ListRecyclingRuns**](docs/PostsAPI.md#listrecyclingruns) | **Get** /{workspaceUuid}/recycling-rules/{ruleUuid}/runs | List a recycling rule&#39;s runs
*PostsAPI* | [**ListRssFeeds**](docs/PostsAPI.md#listrssfeeds) | **Get** /{workspaceUuid}/rss-feeds | List RSS feeds
*PostsAPI* | [**PollRssFeed**](docs/PostsAPI.md#pollrssfeed) | **Post** /{workspaceUuid}/rss-feeds/{feedUuid}/poll | Check an RSS feed now
*PostsAPI* | [**RecyclePost**](docs/PostsAPI.md#recyclepost) | **Post** /{workspaceUuid}/posts/{postUuid}/recycle | Recycle a post on an interval
*PostsAPI* | [**RetryPostAccount**](docs/PostsAPI.md#retrypostaccount) | **Post** /{workspaceUuid}/posts/retry/{postUuid}/{accountUuid} | Retry publishing to one account
*PostsAPI* | [**SchedulePost**](docs/PostsAPI.md#schedulepost) | **Post** /{workspaceUuid}/posts/schedule/{postUuid} | Schedule post
*PostsAPI* | [**UpdatePost**](docs/PostsAPI.md#updatepost) | **Put** /{workspaceUuid}/posts/{postUuid} | Update post
*PostsAPI* | [**UpdateRecyclingRule**](docs/PostsAPI.md#updaterecyclingrule) | **Put** /{workspaceUuid}/recycling-rules/{ruleUuid} | Update, pause or resume a recycling rule
*PostsAPI* | [**UpdateRssFeed**](docs/PostsAPI.md#updaterssfeed) | **Put** /{workspaceUuid}/rss-feeds/{feedUuid} | Update, pause or resume an RSS feed
*PostsAPI* | [**ValidatePost**](docs/PostsAPI.md#validatepost) | **Post** /{workspaceUuid}/posts/validate | Validate post (dry run)
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
*TemplatesAPI* | [**CreateTemplate**](docs/TemplatesAPI.md#createtemplate) | **Post** /{workspaceUuid}/templates | Create a template
*TemplatesAPI* | [**DeleteTemplate**](docs/TemplatesAPI.md#deletetemplate) | **Delete** /{workspaceUuid}/templates/{templateId} | Delete a template
*TemplatesAPI* | [**GetTemplate**](docs/TemplatesAPI.md#gettemplate) | **Get** /{workspaceUuid}/templates/{templateId} | Get a template
*TemplatesAPI* | [**ListTemplates**](docs/TemplatesAPI.md#listtemplates) | **Get** /{workspaceUuid}/templates | List templates
*TemplatesAPI* | [**UpdateTemplate**](docs/TemplatesAPI.md#updatetemplate) | **Put** /{workspaceUuid}/templates/{templateId} | Update a template
*UsersAPI* | [**CreateUser**](docs/UsersAPI.md#createuser) | **Post** /panel/users | Create user
*UsersAPI* | [**DeleteUser**](docs/UsersAPI.md#deleteuser) | **Delete** /panel/users/{userId} | Delete user
*UsersAPI* | [**DeleteUsersBulk**](docs/UsersAPI.md#deleteusersbulk) | **Delete** /panel/users | Delete users (bulk)
*UsersAPI* | [**GetUser**](docs/UsersAPI.md#getuser) | **Get** /panel/users/{userId} | Get user
*UsersAPI* | [**ListUsers**](docs/UsersAPI.md#listusers) | **Get** /panel/users | List users
*UsersAPI* | [**UpdateUser**](docs/UsersAPI.md#updateuser) | **Put** /panel/users/{userId} | Update user
*WebhooksAPI* | [**CreateWebhookSubscription**](docs/WebhooksAPI.md#createwebhooksubscription) | **Post** /{workspaceUuid}/webhooks/subscriptions | Subscribe a webhook
*WebhooksAPI* | [**DeleteWebhookSubscription**](docs/WebhooksAPI.md#deletewebhooksubscription) | **Delete** /{workspaceUuid}/webhooks/subscriptions/{subscriptionUuid} | Unsubscribe a webhook
*WebhooksAPI* | [**ListWebhookSubscriptions**](docs/WebhooksAPI.md#listwebhooksubscriptions) | **Get** /{workspaceUuid}/webhooks/subscriptions | List webhook subscriptions
*WorkspacesAPI* | [**AddUserToWorkspace**](docs/WorkspacesAPI.md#addusertoworkspace) | **Post** /panel/workspaces/{workspaceUuid}/users | Add user to workspace
*WorkspacesAPI* | [**CreateApiKey**](docs/WorkspacesAPI.md#createapikey) | **Post** /{workspaceUuid}/api-keys | Create a scoped API key
*WorkspacesAPI* | [**CreateResellerClient**](docs/WorkspacesAPI.md#createresellerclient) | **Post** /{workspaceUuid}/clients | Create a client workspace
*WorkspacesAPI* | [**CreateWorkspace**](docs/WorkspacesAPI.md#createworkspace) | **Post** /panel/workspaces | Create workspace
*WorkspacesAPI* | [**DeleteApiKey**](docs/WorkspacesAPI.md#deleteapikey) | **Delete** /{workspaceUuid}/api-keys/{apiKeyId} | Revoke a scoped API key
*WorkspacesAPI* | [**DeleteWorkspace**](docs/WorkspacesAPI.md#deleteworkspace) | **Delete** /panel/workspaces/{workspaceUuid} | Delete workspace
*WorkspacesAPI* | [**DeleteWorkspacesBulk**](docs/WorkspacesAPI.md#deleteworkspacesbulk) | **Delete** /panel/workspaces | Delete workspaces (bulk)
*WorkspacesAPI* | [**GetWorkspace**](docs/WorkspacesAPI.md#getworkspace) | **Get** /panel/workspaces/{workspaceUuid} | Get workspace
*WorkspacesAPI* | [**GetWorkspaceAICredits**](docs/WorkspacesAPI.md#getworkspaceaicredits) | **Get** /panel/workspaces/{workspaceUuid}/ai-credits | Get workspace AI credits
*WorkspacesAPI* | [**GetXUsage**](docs/WorkspacesAPI.md#getxusage) | **Get** /{workspaceUuid}/usage/x | X (Twitter) usage
*WorkspacesAPI* | [**ListApiKeys**](docs/WorkspacesAPI.md#listapikeys) | **Get** /{workspaceUuid}/api-keys | List scoped API keys
*WorkspacesAPI* | [**ListMyWorkspaces**](docs/WorkspacesAPI.md#listmyworkspaces) | **Get** /workspaces | List my workspaces
*WorkspacesAPI* | [**ListResellerClients**](docs/WorkspacesAPI.md#listresellerclients) | **Get** /{workspaceUuid}/clients | List client workspaces
*WorkspacesAPI* | [**ListWorkspaces**](docs/WorkspacesAPI.md#listworkspaces) | **Get** /panel/workspaces | List workspaces
*WorkspacesAPI* | [**RemoveUserFromWorkspace**](docs/WorkspacesAPI.md#removeuserfromworkspace) | **Delete** /panel/workspaces/{workspaceUuid}/users | Remove user from workspace
*WorkspacesAPI* | [**UpdateWorkspace**](docs/WorkspacesAPI.md#updateworkspace) | **Put** /panel/workspaces/{workspaceUuid} | Update workspace
*WorkspacesAPI* | [**UpdateWorkspaceUser**](docs/WorkspacesAPI.md#updateworkspaceuser) | **Put** /panel/workspaces/{workspaceUuid}/users | Update user role in workspace

---

## Links

- Docs and quick start: https://postboost.co/docs/quickstart
- API reference: https://postboost.co/docs/api
- MCP server for AI agents: https://postboost.co/docs/mcp
- All PostBoost open-source projects: https://github.com/postboost-co
- Awesome PostBoost: https://github.com/postboost-co/awesome-postboost

## Authentication

Create an API token in PostBoost under **Settings → Access Tokens** and pass it as a Bearer token. Never commit tokens; read them from an environment variable such as `POSTBOOST_API_TOKEN`.

## Contributing

This Go SDK is generated from the [PostBoost OpenAPI spec](https://postboost.co/docs/api). Bugs and feature requests: open an issue in [postboost-go](https://github.com/postboost-co/postboost-go/issues). Generated code is overwritten on every release, so fixes usually land in the spec or the generator templates; see [CONTRIBUTING.md](CONTRIBUTING.md).

Security issues: see [SECURITY.md](SECURITY.md). Questions: hi@postboost.co.

## License

MIT, see [LICENSE](LICENSE).

---

## Links

- Docs and quick start: https://postboost.co/docs/quickstart
- API reference: https://postboost.co/docs/api
- MCP server for AI agents: https://postboost.co/docs/mcp
- All PostBoost open-source projects: https://github.com/postboost-co
- Awesome PostBoost: https://github.com/postboost-co/awesome-postboost

## Authentication

Create an API token in PostBoost under **Settings → Access Tokens** and pass it as a Bearer token. Never commit tokens; read them from an environment variable such as `POSTBOOST_API_TOKEN`.

## Contributing

This Go SDK is generated from the [PostBoost OpenAPI spec](https://postboost.co/docs/api). Bugs and feature requests: open an issue in [postboost-go](https://github.com/postboost-co/postboost-go/issues). Generated code is overwritten on every release, so fixes usually land in the spec or the generator templates; see [CONTRIBUTING.md](CONTRIBUTING.md).

Security issues: see [SECURITY.md](SECURITY.md). Questions: hi@postboost.co.

## License

MIT, see [LICENSE](LICENSE).
