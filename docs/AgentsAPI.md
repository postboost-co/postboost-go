# \AgentsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApproveAgentProposal**](AgentsAPI.md#ApproveAgentProposal) | **Post** /{workspaceUuid}/agent-proposals/{proposalUuid}/approve | Approve and apply an agent proposal
[**CreateAgent**](AgentsAPI.md#CreateAgent) | **Post** /{workspaceUuid}/agents | Switch on a background agent
[**DeleteAgent**](AgentsAPI.md#DeleteAgent) | **Delete** /{workspaceUuid}/agents/{agentUuid} | Delete a background agent
[**GetAgentRun**](AgentsAPI.md#GetAgentRun) | **Get** /{workspaceUuid}/agent-runs/{runUuid} | Get an agent run with its proposals
[**ListAgentProposals**](AgentsAPI.md#ListAgentProposals) | **Get** /{workspaceUuid}/agent-proposals | List agent proposals (approval queue)
[**ListAgentRuns**](AgentsAPI.md#ListAgentRuns) | **Get** /{workspaceUuid}/agents/{agentUuid}/runs | Run history of an agent
[**ListAgents**](AgentsAPI.md#ListAgents) | **Get** /{workspaceUuid}/agents | List background agents
[**RejectAgentProposal**](AgentsAPI.md#RejectAgentProposal) | **Post** /{workspaceUuid}/agent-proposals/{proposalUuid}/reject | Reject an agent proposal
[**RunAgent**](AgentsAPI.md#RunAgent) | **Post** /{workspaceUuid}/agents/{agentUuid}/run | Run a background agent now
[**UpdateAgent**](AgentsAPI.md#UpdateAgent) | **Put** /{workspaceUuid}/agents/{agentUuid} | Update a background agent



## ApproveAgentProposal

> ApproveAgentProposal200Response ApproveAgentProposal(ctx, workspaceUuid, proposalUuid).AgentProposalDecision(agentProposalDecision).Execute()

Approve and apply an agent proposal



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	proposalUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	agentProposalDecision := *openapiclient.NewAgentProposalDecision() // AgentProposalDecision |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ApproveAgentProposal(context.Background(), workspaceUuid, proposalUuid).AgentProposalDecision(agentProposalDecision).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ApproveAgentProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveAgentProposal`: ApproveAgentProposal200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ApproveAgentProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**proposalUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveAgentProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **agentProposalDecision** | [**AgentProposalDecision**](AgentProposalDecision.md) |  | 

### Return type

[**ApproveAgentProposal200Response**](ApproveAgentProposal200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAgent

> CreateAgent201Response CreateAgent(ctx, workspaceUuid).WorkspaceAgentInput(workspaceAgentInput).Execute()

Switch on a background agent



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	workspaceAgentInput := *openapiclient.NewWorkspaceAgentInput("Type_example") // WorkspaceAgentInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.CreateAgent(context.Background(), workspaceUuid).WorkspaceAgentInput(workspaceAgentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.CreateAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAgent`: CreateAgent201Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.CreateAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspaceAgentInput** | [**WorkspaceAgentInput**](WorkspaceAgentInput.md) |  | 

### Return type

[**CreateAgent201Response**](CreateAgent201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAgent

> DeleteAgent200Response DeleteAgent(ctx, workspaceUuid, agentUuid).Execute()

Delete a background agent



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	agentUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.DeleteAgent(context.Background(), workspaceUuid, agentUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.DeleteAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAgent`: DeleteAgent200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.DeleteAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**agentUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteAgent200Response**](DeleteAgent200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgentRun

> RunAgent202Response GetAgentRun(ctx, workspaceUuid, runUuid).Execute()

Get an agent run with its proposals

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	runUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.GetAgentRun(context.Background(), workspaceUuid, runUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.GetAgentRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgentRun`: RunAgent202Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.GetAgentRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**runUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAgentRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RunAgent202Response**](RunAgent202Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgentProposals

> ListAgentProposals200Response ListAgentProposals(ctx, workspaceUuid).Status(status).PerPage(perPage).Page(page).Execute()

List agent proposals (approval queue)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	status := "status_example" // string |  (optional) (default to "pending")
	perPage := int32(56) // int32 |  (optional) (default to 20)
	page := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ListAgentProposals(context.Background(), workspaceUuid).Status(status).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ListAgentProposals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentProposals`: ListAgentProposals200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ListAgentProposals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAgentProposalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** |  | [default to &quot;pending&quot;]
 **perPage** | **int32** |  | [default to 20]
 **page** | **int32** |  | 

### Return type

[**ListAgentProposals200Response**](ListAgentProposals200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgentRuns

> ListAgentRuns200Response ListAgentRuns(ctx, workspaceUuid, agentUuid).PerPage(perPage).Page(page).Execute()

Run history of an agent



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	agentUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	perPage := int32(56) // int32 |  (optional) (default to 20)
	page := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ListAgentRuns(context.Background(), workspaceUuid, agentUuid).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ListAgentRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentRuns`: ListAgentRuns200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ListAgentRuns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**agentUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAgentRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **perPage** | **int32** |  | [default to 20]
 **page** | **int32** |  | 

### Return type

[**ListAgentRuns200Response**](ListAgentRuns200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgents

> ListAgents200Response ListAgents(ctx, workspaceUuid).Execute()

List background agents



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ListAgents(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ListAgents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgents`: ListAgents200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ListAgents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAgentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListAgents200Response**](ListAgents200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectAgentProposal

> ApproveAgentProposal200Response RejectAgentProposal(ctx, workspaceUuid, proposalUuid).AgentProposalDecision(agentProposalDecision).Execute()

Reject an agent proposal



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	proposalUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	agentProposalDecision := *openapiclient.NewAgentProposalDecision() // AgentProposalDecision |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.RejectAgentProposal(context.Background(), workspaceUuid, proposalUuid).AgentProposalDecision(agentProposalDecision).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.RejectAgentProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectAgentProposal`: ApproveAgentProposal200Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.RejectAgentProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**proposalUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRejectAgentProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **agentProposalDecision** | [**AgentProposalDecision**](AgentProposalDecision.md) |  | 

### Return type

[**ApproveAgentProposal200Response**](ApproveAgentProposal200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunAgent

> RunAgent202Response RunAgent(ctx, workspaceUuid, agentUuid).Execute()

Run a background agent now



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	agentUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.RunAgent(context.Background(), workspaceUuid, agentUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.RunAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunAgent`: RunAgent202Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.RunAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**agentUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**RunAgent202Response**](RunAgent202Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAgent

> CreateAgent201Response UpdateAgent(ctx, workspaceUuid, agentUuid).WorkspaceAgentUpdate(workspaceAgentUpdate).Execute()

Update a background agent



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	agentUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	workspaceAgentUpdate := *openapiclient.NewWorkspaceAgentUpdate() // WorkspaceAgentUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.UpdateAgent(context.Background(), workspaceUuid, agentUuid).WorkspaceAgentUpdate(workspaceAgentUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.UpdateAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAgent`: CreateAgent201Response
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.UpdateAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**agentUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **workspaceAgentUpdate** | [**WorkspaceAgentUpdate**](WorkspaceAgentUpdate.md) |  | 

### Return type

[**CreateAgent201Response**](CreateAgent201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

