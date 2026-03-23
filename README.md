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
| **Version** | v1.0.0 |

## Quick start

```go
import postboost "github.com/postboost-co/postboost-go"

cfg := postboost.NewConfiguration()
cfg.AddDefaultHeader("Authorization", "Bearer "+apiToken)
client := postboost.NewAPIClient(cfg)

posts, _, err := client.PostsAPI.ListPosts(ctx, "YOUR_WORKSPACE_UUID").Execute()
```

## License

MIT
