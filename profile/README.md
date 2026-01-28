## mcpchecker

MCPChecker is a testing framework for MCP (Model Context Protocol) servers. It helps you verify that:
- Your tools are **discoverable** by AI agents
- Tool descriptions are **clear and actionable**
- Agents can **correctly use** your tools
- Your server handles **edge cases** properly

Think of it as integration testing for AI tool use.

### Getting Started

Check out [our quickstarts](https://github.com/mcpchecker/quickstarts) to dive right in and try out the framework!

### Available (official) Extensions

mcpchecker supports extensions to the core framework, allowing you to create domain specific operations for
your evaluations. Check out the official extensions created by the community below:
- [Kubernetes Extension](https://github.com/mcpchecker/kubernetes-extension)

To create your own, feel free to read up on the protocol docs or to use any of the available SDKs listed below:
- [Go SDK](https://github.com/mcpchecker/mcpchecker/tree/main/pkg/extension/sdk)
- [Extension Protocol Docs](https://github.com/mcpchecker/mcpchecker/blob/main/docs/specs/extension-protocol.md)
