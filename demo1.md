# Demo 1

## Steps

1. `git clone git@github.com:c0tton-fluff/caido-mcp-server.git`
1. `go build -ldflags "-X github.com/c0tton-fluff/caido-mcp-server/v4/internal/buildinfo.version=$(git describe --tags)" -o caido-mcp-server ./cmd/caido-mcp-server`
1. `CAIDO_URL=http://localhost:8080 caido-mcp-server login`
1. `cat ~/.caido-mcp/token.json`
1. `claude mcp add caido -e CAIDO_URL=http://127.0.0.1:8082 -- /Users/sytten/Projects/Defcon/caido-mcp-server/caido-mcp-server serve`
1. `claude mcp list`
1. `claude`
1. `What caido projects do I have`
