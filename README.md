# Echo

Example [Echo](https://echo.labstack.com/) app. Echo is a high-performance, minimalist web framework for Go.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `8000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
go mod download

# run in dev mode
go run .

# build for production
go build -o app . && ./app
```
