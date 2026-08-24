# Awesome Claude dxt with stars

[![Stars](https://img.shields.io/github/stars/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/stargazers) ⭐ 177 | 🐛 9 | 🌐 JavaScript | 📅 2026-07-29
[![Forks](https://img.shields.io/github/forks/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/network/members) ⭐ 177 | 🐛 9 | 🌐 JavaScript | 📅 2026-07-29
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/dxt?style=flat\&logo=reddit\&label=subreddit)](https://www.reddit.com/r/dxt/)
[![Discord](https://img.shields.io/discord/1394197669794025564?logo=discord\&label=discord)](https://discord.gg/N3gtxgJfby)
[![Last Commit](https://img.shields.io/github/last-commit/milisp/awesome-claude-dxt)](https://github.com/milisp/awesome-claude-dxt/commits) ⭐ 177 | 🐛 9 | 🌐 JavaScript | 📅 2026-07-29
[![License](https://img.shields.io/github/license/milisp/awesome-claude-dxt)](LICENSE)

A curated list of awesome (not only Claude) Desktop Extensions, tools, and resources

## What is DXT

[dxt](https://www.anthropic.com/engineering/desktop-extensions) is Desktop Extensions: One-click MCP server installation for Claude Desktop and other Desktop apps

> \[!TIP]
> **⭐ Star the repo and follow [milisp](https://x.com/lisp_mi) on X and [github](https://github.com/milisp) for more**.

## Feature Projects

* [milisp/codexia](https://github.com/milisp/codexia) ⭐ 895 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-20 - The missing GUI for the OpenAI Codex CLI, (FileTree + notepad + git diff) all in a lightweight Tauri desktop app.
* [mcp-linker](https://github.com/milisp/mcp-linker) ⭐ 321 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-17 - mcp manager, add & syncs MCP server configurations across clients like Claude, Cursor

## Contents

* [Official Resources](#official-resources)
* [Community](#community)
* [Contributing](#contributing)
* [Extensions by Category](#extensions-by-category)
  * [Development Tools](#development-tools)
  * [Command Line](#command-line)
  * [File Management](#file-management)
  * [System Tools](#system-tools)
  * [Web Services](#web-services)
  * [Messaging](#messaging)
  * [Databases](#databases)
  * [Analytics](#analytics)
  * [AI Systems](#ai-systems)
  * [MCP Tools](#mcp-tools)
  * [API Integrations](#api-integrations)
  * [Data Analysis](#data-analysis)
  * [Knowledge Base](#knowledge-base)
  * [Media Creation](#media-creation)
  * [Productivity](#productivity)
  * [Professional Apps](#professional-apps)
  * [Finance](#finance)
  * [examples](#examples)
* [Development Tools](#development-tools-1)
* [Packaging & Management Tools](#packaging--management-tools)
* [Documentation & Tutorials](#documentation--tutorials)

## Official Resources

* [DXT Specification](https://github.com/anthropics/dxt) ⭐ 2,085 | 🐛 96 | 🌐 TypeScript | 📅 2026-05-26 - Open-source toolchain and specs
* [Official examples](https://github.com/anthropics/dxt/tree/main/examples) ⭐ 2,085 | 🐛 96 | 🌐 TypeScript | 📅 2026-05-26 - Official examples
* [Desktop Extensions Announcement](https://www.anthropic.com/engineering/desktop-extensions) - Official blog post
* [Submission Form](https://forms.gle/tyiAZvch1kDADKoP9) - Submit to official directory

## Community

* [r/dxt Reddit](https://www.reddit.com/r/dxt)
* [Discord](https://discord.gg/N3gtxgJfby)

## ☕ Support

[![GitHub Stars](https://img.shields.io/github/stars/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/stargazers) ⭐ 177 | 🐛 9 | 🌐 JavaScript | 📅 2026-07-29

If you find this project helpful, please consider starring!

## Contributing

This list is community-maintained. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. Or [translate plan](./translate-plan.md)

## Extensions by Category

All extensions are located in the servers folder, each organized by owner/repo, and containing a `manifest.json` and `user_config.json`. If the `manifest.json` is verified by the community, a `verified.json` file will also be included.

### Real world ${\_\_dirname} examples

If you have any disconnect issue check the `manifest.json` at these useful repos, python and nodejs

* [taylorwilsdon/google\_workspace\_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) ⭐ 3,060 | 🐛 186 | 🌐 Python | 📅 2026-08-18 - Full natural language control over Google Calendar, Drive, Gmail, Docs, Sheets, Slides, Forms, Tasks and Chat through all MCP clients, AI assistants and developer tools

```md
"mcp_config": {
  "command": "uv",
  "args": [
    "run",
    "--directory",
    "${__dirname}",
    "python",
    "${__dirname}/main.py"
  ]
}
```

* [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) ⭐ 920 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-18 - GitHub code search and npm package exploration MCP server

### Development Tools

* [modelcontextprotocol/gitlab](https://github.com/modelcontextprotocol/servers/blob/main/src/gitlab) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - GitLab API, enabling project management
* [modelcontextprotocol/git](https://github.com/modelcontextprotocol/servers/blob/main/src/git) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Tools to read, search, and manipulate Git repositories
* [modelcontextprotocol/sentry](https://github.com/modelcontextprotocol/servers/blob/main/src/sentry) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Retrieving and analyzing issues from Sentry.io
* [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) ⭐ 5,722 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-31 - Magic Component Platform (MCP) is a powerful AI-driven tool that helps developers create beautiful, modern UI components instantly through natural language descriptions. It integrates seamlessly with popular IDEs and provides a streamlined workflow for UI development.
* [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) ⭐ 5,407 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-20 - The [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) is a standard for connecting Large Language Models (LLMs) to external services. This guide will walk you through how to connect AI tools to Lingo.dev using MCP.
* [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ⭐ 4,105 | 🐛 55 | 🌐 TypeScript | 📅 2026-08-24 - Model Context Protocol (MCP) is a [new, standardized protocol](https://modelcontextprotocol.io/introduction) for managing context between large language models (LLMs) and external systems. In this repository, we provide an installer as well as an MCP Server for [Cloudflare's API](https://api.cloudflare.com).
* [chrome-applescript](https://github.com/anthropics/dxt/tree/main/examples/chrome-applescript) ⭐ 2,085 | 🐛 96 | 🌐 TypeScript | 📅 2026-05-26 - Browser automation via AppleScript
* [manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) ⭐ 2,016 | 🐛 94 | 🌐 Go | 📅 2026-08-24 - A powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for any Kubernetes resource, this server provides specialized tools to interact with your cluster.
* [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) ⭐ 1,638 | 🐛 37 | 🌐 TypeScript | 📅 2025-07-09 - This MCP server provides tools and resources for AI assistants to manage n8n workflows and executions, including listing, creating, updating, and deleting workflows, as well as monitoring their execution status.
* [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) ⭐ 1,574 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-08 - Connect to Kubernetes cluster and manage pods, deployments, and services.
* [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) ⭐ 966 | 🐛 39 | 🌐 JavaScript | 📅 2026-01-07 - The server proxies requests from client to JetBrains IDE.
* [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) ⭐ 899 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-07 - Interact with [OpenAPI](https://www.openapis.org/) APIs.
* [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) ⭐ 740 | 🐛 28 | 🌐 Python | 📅 2026-08-07 - Integrate with Docker to manage containers, images, volumes, and networks.
* [semgrep/mcp](https://github.com/semgrep/mcp) ⚠️ Archived - An MCP server for using Semgrep to scan code for security vulnerabilies. Secure your vibe coding!
* [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) ⚠️ Archived - A Model Context Protocol server for Mem0, which helps with managing coding preferences.
* [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) ⭐ 318 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-11 - An MCP Server for your Neovim session.
* [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) ⭐ 306 | 🐛 5 | 🌐 Python | 📅 2026-08-02 - Provides a repo-packing MCP tool with configurable profiles that specify file inclusion/exclusion patterns and optional prompts.
* [modelcontextprotocol/github](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/github) ⚠️ Archived - Repository management, file operations, and GitHub API integration
* [bazinga012/mcp\_code\_executor](https://github.com/bazinga012/mcp_code_executor) ⭐ 212 | 🐛 6 | 🌐 JavaScript | 📅 2025-05-24 - An MCP server that allows LLMs to execute Python code within a specified Conda environment.
* [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) ⭐ 175 | 🐛 15 | 🌐 Python | 📅 2026-03-03 - A MCP Server that connects to [Apache Airflow](https://airflow.apache.org/) using official python client.
* [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) ⭐ 162 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - This repository contains a Model Context Protocol (MCP) server with tools that can access the OpenTelemetry traces and
* [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) ⭐ 147 | 🐛 5 | 🌐 Python | 📅 2026-02-27 - A secure sandboxed Python code execution environment for MCP (Model-Client-Program) architecture.
* [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) ⭐ 135 | 🐛 22 | 🌐 TypeScript | 📅 2026-06-22 - > Universal RPC layer for AI agents across network boundaries and languages
* [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) ⭐ 128 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-30 - Dart MCP Server
* [kubestellar/console (kc-agent)](https://github.com/kubestellar/console) ⭐ 127 | 🐛 46 | 🌐 TypeScript | 📅 2026-08-24 - AI-powered multi-cluster Kubernetes dashboard with a built-in MCP server (`kc-agent`) that exposes live fleet data (pods, deployments, Helm releases, GPU inventory, compliance policies) to any MCP-compatible AI agent — no cluster-side install required.
* [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) ⭐ 127 | 🐛 1 | 🌐 Python | 📅 2025-04-08 - Perform operations on your AWS resources using an LLM.
* [GongRzhe/JSON-MCP-Server](https://github.com/GongRzhe/JSON-MCP-Server) ⚠️ Archived - JSON handling and processing server with advanced query capabilities using JSONPath syntax and support for array, string, numeric, and date operations.
* [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2025-08-15 - 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
* [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) ⭐ 84 | 🐛 7 | 🌐 TypeScript | 📅 2025-03-25 - MCP server for running Postman Collections locally via Newman. Allows for simple execution of Postman Server and returns the results of whether the collection passed all the tests.
* [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) ⭐ 82 | 🐛 2 | 🌐 Python | 📅 2025-04-14 - Interact with large [OpenAPI](https://www.openapis.org/) docs using built-in semantic search for endpoints. Allows for customizing the MCP server prefix.
* [supernovae-st/nika](https://github.com/supernovae-st/nika) ⭐ 56 | 🐛 47 | 🌐 Rust | 📅 2026-08-24 - Read-only oracle for Nika AI workflows: validate `.nika.yaml` files, explain findings, and estimate cost before running — the MCP server ships inside the single Rust binary, with signed `.mcpb` bundles (macOS arm64 + Linux x64) on each release.
* [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) ⭐ 50 | 🐛 7 | 🌐 JavaScript | 📅 2025-03-13 - Allow LLMs to explore large [OpenAPI](https://www.openapis.org/) schemas without bloating the context.
* [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) ⭐ 47 | 🐛 3 | 🌐 JavaScript | 📅 2025-05-26 - Allow LLMs to explore large GraphQL schemas without bloating the context.
* [shanejonas/openrpc-mpc-server](https://github.com/shanejonas/openrpc-mpc-server) ⭐ 43 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-02 - Interact with and discover JSON-RPC APIs via [OpenRPC](https://open-rpc.org/).
* [ko1ynnky/github-actions-mcp-server](https://github.com/ko1ynnky/github-actions-mcp-server) ⚠️ Archived - A Model Context Protocol (MCP) server for interacting with Github Actions.
* [Boston343/starwind-ui-mcp](https://github.com/Boston343/starwind-ui-mcp) ⭐ 35 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-15 - This MCP provides relevant commands, documentation, and other information to allow LLMs to take full advantage of Starwind UI's open source Astro components.
* [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) ⭐ 22 | 🐛 3 | 📅 2026-03-02 - MCP Server for Raygun's API V3 endpoints for interacting with your Crash Reporting and Real User Monitoring applications. This server provides comprehensive access to Raygun's API features through the Model Context Protocol.
* [chargebee/agentkit](https://github.com/chargebee/agentkit) ⚠️ Archived - MCP Server that connects AI agents to Chargebee platform.
* [ognis1205/mcp-server-unitycatalog](https://github.com/ognis1205/mcp-server-unitycatalog) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2025-03-28 - An MCP server that enables LLMs to interact with Unity Catalog AI, supporting CRUD operations on Unity Catalog Functions and executing them as MCP tools.
* [riza-io/riza-mcp](https://github.com/riza-io/riza-mcp) ⭐ 13 | 🐛 3 | 🌐 JavaScript | 📅 2024-12-17 - [Riza](https://riza.io) offers an isolated code interpreter for your LLM-generated code.
* [apimatic/apimatic-validator-mcp](https://github.com/apimatic/apimatic-validator-mcp) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2025-03-19 - This repository provides a Model Context Protocol (MCP) Server for validating OpenAPI specifications using [APIMatic](https://www.apimatic.io/). The server processes OpenAPI files and returns validation summaries by leveraging APIMatic’s API.
* [yanmxa/multicluster-mcp-server](https://github.com/yanmxa/multicluster-mcp-server) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2025-07-08 - The gateway for GenAI systems to interact with multiple Kubernetes clusters.

### Command Line

* [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐ 9,388 | 🐛 217 | 🌐 TypeScript | 📅 2026-08-21 📇 🏠 🍎 🪟 🐧 - A swiss-army-knife that can manage/execute programs and read/write/search/edit code and text files.
* [daxaur/openpaw](https://github.com/daxaur/openpaw) ⭐ 163 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-23 - A CLI tool that adds 39 personal assistant skills to Claude Code — focus mode, task dashboard, smart home, email, calendar, and more.

### File Management

* [file-manager-python](https://github.com/anthropics/dxt/tree/main/examples/file-manager-python) ⭐ 2,085 | 🐛 96 | 🌐 TypeScript | 📅 2026-05-26

### System Tools

* [modelcontextprotocol/time](https://github.com/modelcontextprotocol/servers/blob/main/src/time) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - A Model Context Protocol server that provides time and timezone conversion capabilities. It automatically detects the system's timezone and offers tools for getting current time and converting between timezones.
* [modelcontextprotocol/filesystem](https://github.com/modelcontextprotocol/servers/blob/main/src/filesystem) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Secure file operations with configurable access controls
* [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) ⭐ 568 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-20 - Integration with iTerm2 terminal emulator for macOS, enabling LLMs to execute and monitor terminal commands.
* [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) ⭐ 356 | 🐛 24 | 🌐 Python | 📅 2025-10-20 - Fast file searching capabilities across Windows (using [Everything SDK](https://www.voidtools.com/support/everything/sdk/)), macOS (using mdfind command), and Linux (using locate/plocate command).
* [SimonB97/win-cli-mcp-server](https://github.com/SimonB97/win-cli-mcp-server) ⚠️ Archived - MCP server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells.
* [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) ⭐ 192 | 🐛 9 | 🌐 TypeScript | 📅 2026-03-02 - MCP to interact with Siri Shortcuts on macOS. Exposes all Shortcuts as MCP tools.
* [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) ⭐ 147 | 🐛 5 | 🌐 Python | 📅 2026-02-27 - A Model Context Protocol (MCP) server for executing command-line operations on remote servers via SSH.
* [GongRzhe/terminal-controller-mcp](https://github.com/GongRzhe/terminal-controller-mcp) ⚠️ Archived - A MCP server that enables secure terminal command execution, directory navigation, and file system operations through a standardized interface.
* [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) ⭐ 46 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-09 - This MCP server enables natural language interaction with Keycloak for user and realm management including creating, deleting, and listing users and realms.
* [Descope/descope-mcp-server](https://github.com/descope-sample-apps/descope-mcp-server) ⭐ 34 | 🐛 5 | 🌐 TypeScript | 📅 2025-03-17 - An MCP server to integrate with [Descope](https://descope.com/) to search audit logs, manage users, and more.
* [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) ⭐ 22 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-11 - Interact with Okta API.
* [MichaelAdamGroberman/mac-mcp](https://github.com/MichaelAdamGroberman/mac-mcp) ⭐ 2 | 🐛 1 | 🌐 Swift | 📅 2026-07-01 - Native macOS control via Swift + AppKit + Accessibility + cached OSAKit. 32 typed allow-listed tools across windows, Finder, clipboard, screenshots, mouse/trackpad/keyboard (CGEvent), Mail/Calendar/Messages/Safari/Notes, iTerm/Terminal, and iPhone Mirroring. Code-signed Developer ID + hardened runtime for stable TCC grants. No `run_shell` / `run_applescript` escape hatches. Ships as a one-click `.mcpb`.
* [dinghuazhou/sample-mcp-server-tos](https://github.com/dinghuazhou/sample-mcp-server-tos) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2025-05-20 - A sample MCP server for VolcEngine TOS that flexibly get objects from TOS.

### Web Services

* [modelcontextprotocol/google-maps](https://github.com/modelcontextprotocol/servers/blob/main/src/google-maps) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Location services, directions, and place details

* [modelcontextprotocol/brave-search](https://github.com/modelcontextprotocol/servers/blob/main/src/brave-search) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Web and local search using Brave's Search API

* [modelcontextprotocol/fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - A Model Context Protocol server that provides web content fetching capabilities.

* [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ⭐ 36,424 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-21 - A Model Context Protocol (MCP) server that provides browser automation capabilities using [Playwright](https://playwright.dev). This server enables LLMs to interact with web pages through structured accessibility snapshots, bypassing the need for screenshots or visually-tuned models.

* [mendableai/firecrawl-mcp-server](https://github.com/mendableai/firecrawl-mcp-server) ⭐ 7,308 | 🐛 156 | 🌐 JavaScript | 📅 2026-08-21 - Advanced web scraping with JavaScript rendering, PDF support, and smart rate limiting

* [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) ⭐ 5,633 | 🐛 34 | 🌐 TypeScript | 📅 2025-12-13 - This MCP Server will help you run browser automation and webscraping using Playwright

* [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) ⭐ 4,920 | 🐛 33 | 🌐 TypeScript | 📅 2026-08-21 - A Model Context Protocol (MCP) server lets AI assistants like Claude use the Exa AI Search API for web searches. This setup allows AI models to get real-time web information in a safe and controlled way.

* [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) ⭐ 4,788 | 🐛 144 | 🌐 TypeScript | 📅 2026-08-24 - Implementation of an MCP server for all [Apify Actors](https://apify.com/store).

* [ppl-ai/modelcontextprotocol](https://github.com/ppl-ai/modelcontextprotocol) ⭐ 2,476 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-17 - An MCP server implementation that integrates the Sonar API to provide Claude with unparalleled real-time, web-wide research.

* [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp) ⭐ 2,350 | 🐛 47 | 🌐 JavaScript | 📅 2026-08-20 - Search engine for AI agents (search + extract) powered by Tavily

* [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) ⭐ 1,157 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-24 - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org/)

* [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) ⭐ 814 | 🐛 7 | 🌐 TypeScript | 📅 2026-03-12 - A server that flexibly fetches HTML, JSON, Markdown, or plaintext.

* [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp) ⭐ 790 | 🐛 9 | 🌐 TypeScript | 📅 2025-11-20 - This is Hyperbrowser's Model Context Protocol (MCP) Server. It provides various tools to scrape, extract structured data, and crawl webpages. It also provides easy access to general purpose browser agents like OpenAI's CUA, Anthropic's Claude Computer Use, and Browser Use.

* [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) ⭐ 516 | 🐛 34 | 🌐 JavaScript | 📅 2026-08-06 - Provides tools to search Airbnb and get listing details.

* [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) ⚠️ Archived - An MCP server for Apify's open-source RAG Web Browser [Actor](https://apify.com/apify/rag-web-browser) to perform web searches, scrape URLs, and return content in Markdown.

* [Xquik-dev/x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) ⭐ 187 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-24 - X/Twitter data MCP server & AI agent skill. REST API and 20 extraction tools for profiles, tweets, followers, and more.

* [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) ⭐ 177 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-24 - This is a Model Context Protocol (MCP) server that integrates [AgentQL](https://agentql.com)'s data extraction capabilities.

* [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) ⭐ 173 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - A Model Context Protocol (MCP) server that provides search and crawl functionality using Search1API.

* [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) ⭐ 147 | 🐛 5 | 🌐 Python | 📅 2026-02-27 - A Model Context Protocol (MCP) server for fetching webpages including html/pdf/plain text type content.

* [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) ⭐ 147 | 🐛 5 | 🌐 Python | 📅 2026-02-27 - A Model Context Protocol (MCP) server for TXYZ Search API. Provides tools for academic and scholarly search, general web search, and smart search.

* [pfldy2850/py-mcp-naver](https://github.com/pfldy2850/py-mcp-naver) ⭐ 114 | 🐛 2 | 🌐 Python | 📅 2025-04-02 - This MCP server provides tools to interact with various Naver services, such as searching blogs, news, books, and more.

* [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) ⭐ 111 | 🐛 0 | 🌐 Python | 📅 2026-08-02 - Access text content from bot-protected websites. Fetches HTML/markdown from sites with anti-automation measures using Scrapling.

* [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) ⭐ 101 | 🐛 1 | 🌐 Python | 📅 2026-08-17 - A Model Context Protocol (MCP) server that enables AI assistants like Claude to seamlessly access web data through Oxylabs' powerful web scraping technology.

* [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) ⭐ 93 | 🐛 5 | 🌐 Python | 📅 2025-09-12 - This is a Python-based MCP server that provides OpenAI `web_search` build-in tool.

* [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) ⭐ 78 | 🐛 5 | 🌐 Python | 📅 2025-04-04 - Server implementation for Microsoft Bing Web Search API.

* [RamXX/mcp-tavily](https://github.com/RamXX/mcp-tavily) ⚠️ Archived - An MCP server for Tavily's search & news API, with explicit site inclusions/exclusions

* [adenot/mcp-google-search](https://github.com/adenot/mcp-google-search) ⭐ 68 | 🐛 6 | 🌐 JavaScript | 📅 2025-09-24 - Provides Google Search results via the Google Custom Search API

* [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) ⭐ 59 | 🐛 3 | 🌐 JavaScript | 📅 2025-03-15 - MCP server that performs whois lookup against domain, IP, ASN and TLD.

* [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) ⭐ 51 | 🐛 4 | 🌐 TypeScript | 📅 2025-05-01 - Server for interacting with [Drupal](https://www.drupal.org/project/mcp) using STDIO transport layer.

* [xxxbrian/mcp-rquest](https://github.com/xxxbrian/mcp-rquest) ⭐ 48 | 🐛 3 | 🌐 Python | 📅 2025-03-22 - An MCP server providing realistic browser-like HTTP request capabilities with accurate TLS/JA3/JA4 fingerprints for bypassing anti-bot measures.

* [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) ⭐ 47 | 🐛 2 | 🌐 JavaScript | 📅 2025-01-29 - A Claude Desktop MCP server that helps you track flights in real-time using Flightradar24 data.

* [VectorInstitute/mcp-goodnews](https://github.com/VectorInstitute/mcp-goodnews) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2025-07-17 - A simple MCP server that delivers curated positive and uplifting news stories.

* [delorenj/mcp-server-ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster) ⭐ 25 | 🐛 3 | 🌐 TypeScript | 📅 2025-07-01 - Search for events, venues, and attractions through the Ticketmaster Discovery API

* [mfukushim/map-traveler-mcp](https://github.com/mfukushim/map-traveler-mcp) ⭐ 23 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-03 - Integrates Google Map, Google Street View, PixAI, Stability.ai, ComfyUI API and Bluesky to provide a virtual location simulation in LLM (written in Effect.ts)

* [AshDevFr/discourse-mcp-server](https://github.com/AshDevFr/discourse-mcp-server) ⭐ 5 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-10 - A MCP server to search Discourse posts on a Discourse forum.

* [Rakesh1002/namemyapp-mcp](https://github.com/Rakesh1002/namemyapp-mcp) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-26 - Generate brandable business names with live domain availability and one-click buy URLs. 12 tools: AI naming, domain check, registration, DNS, logos, legal docs, brand & social kits. Remote MCP at `https://mcp.namemy.app/mcp` (OAuth) and `/direct` (bearer); npm: `@namemyapp/mcp`.

* [amap/amap-maps-mcp-server](https://www.npmjs.com/package/@amap/amap-maps-mcp-server) - MCP Server for the AMap Map API.

* [fingertip-com/fingertip-mcp](https://github.com/fingertip-com/fingertip-mcp) - MCP server for Fingertip.com to search and create new sites.

### Messaging

* [modelcontextprotocol/slack](https://github.com/modelcontextprotocol/servers/blob/main/src/slack) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Channel management and messaging capabilities
* [GongRzhe/Gmail-MCP-Server](https://github.com/GongRzhe/Gmail-MCP-Server) ⚠️ Archived - A Model Context Protocol (MCP) server for Gmail integration in Claude Desktop with auto authentication support.
* [idoubi/mcp-server-chatsum](https://github.com/mcpso/mcp-server-chatsum) ⭐ 1,029 | 🐛 10 | 🌐 TypeScript | 📅 2024-12-04 - Query and Summarize chat messages with LLM. by [mcpso](https://mcp.so/)
* [carterlasalle/mac\_messages\_mcp](https://github.com/carterlasalle/mac_messages_mcp) ⭐ 318 | 🐛 0 | 🌐 Python | 📅 2026-07-21 - An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages.
* [v-3/discordmcp](https://github.com/v-3/discordmcp) ⭐ 227 | 🐛 9 | 🌐 TypeScript | 📅 2025-01-21 - A MCP server to connect to Discord guilds through a bot and read and write messages in channels
* [Zilong Xue/claude-post](https://github.com/ZilongXue/claude-post) ⭐ 114 | 🐛 1 | 🌐 Python | 📅 2026-06-01 - ClaudePost enables seamless email management for Gmail, offering secure features like email search, reading, and sending.
* [vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2025-03-12 - Create, manage and publish X/Twitter posts directly through Claude chat.
* [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) ⭐ 44 | 🐛 2 | 🌐 JavaScript | 📅 2025-03-25 - The MCP server that keeps you informed by sending the notification on phone using ntfy
* [ashiknesin/pushover-mcp](https://github.com/ashiknesin/pushover-mcp) ⭐ 42 | 🐛 8 | 🌐 TypeScript | 📅 2025-03-16 - Send instant notifications to your devices using [Pushover.net](https://pushover.net/)
* [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) ⭐ 38 | 🐛 7 | 🌐 Python | 📅 2025-10-14 - The MCP server that interacts with RabbitMQ to publish and consume messages.
* [raoulbia-ai/mcp-server-for-intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-25 - An MCP-compliant server for retrieving customer support tickets from Intercom. This tool enables AI assistants like Claude Desktop and Cline to access and analyze your Intercom support tickets.

### Databases

* [modelcontextprotocol/postgres](https://github.com/modelcontextprotocol/servers/blob/main/src/postgres) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Read-only database access with schema inspection
* [bytebase/dbhub](https://github.com/bytebase/dbhub) ⭐ 3,394 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21 - Universal database MCP server connecting to MySQL, PostgreSQL, SQLite, DuckDB and etc.
* [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) ⭐ 1,514 | 🐛 76 | 🌐 Python | 📅 2026-08-14 - This repository is an example of how to create a MCP server for Qdrant, a vector search engine.
* [designcomputer/mysql\_mcp\_server](https://github.com/designcomputer/mysql_mcp_server) ⭐ 1,366 | 🐛 1 | 🌐 Python | 📅 2026-08-02 - MySQL database integration in Python with configurable access controls and schema inspection
* [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) ⭐ 979 | 🐛 26 | 🌐 Python | 📅 2026-04-10 - This server enables running Cypher graph queries, analyzing complex domain data, and automatically generating business insights that can be enhanced with Claude's analysis when an Anthropic API key is provided.
* [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) ⭐ 979 | 🐛 26 | 🌐 Python | 📅 2026-04-10 - Neo4j graph database server (schema + read/write-cypher) and separate graph database backed memory
* [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) ⭐ 979 | 🐛 26 | 🌐 Python | 📅 2026-04-10 - Neo4j graph database server (schema + read/write-cypher) and separate graph database backed memory
* [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) ⭐ 857 | 🐛 35 | 🌐 Python | 📅 2026-08-21 - An MCP server for ClickHouse.
* [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) ⭐ 587 | 🐛 30 | 🌐 Python | 📅 2025-09-17 - Embeddings, vector search, document storage, and full-text search with the open-source AI application database
* [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) ⭐ 510 | 🐛 6 | 🌐 Python | 📅 2026-08-19 - Query and analyze data with MotherDuck and local DuckDB
* [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) ⭐ 303 | 🐛 9 | 🌐 Python | 📅 2026-08-16 - MCP server implementation that provides Elasticsearch interaction.
* [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) ⭐ 284 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-29 - A Model Context Protocol Server for MongoDB.
* [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) ⭐ 248 | 🐛 16 | 🌐 TypeScript | 📅 2025-10-27 - Server to interact with Firebase services including Firebase Authentication, Firestore, and Firebase Storage.
* [XGenerationLab/xiyan\_mcp\_server](https://github.com/XGenerationLab/xiyan_mcp_server) ⭐ 242 | 🐛 9 | 🌐 Python | 📅 2026-02-11 - An MCP server that supports fetching data from a database using natural language queries, powered by XiyanSQL as the text-to-SQL LLM.
* [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) ⭐ 241 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - This repository contains a MCP server that provides access to Milvus vector database functionality.
* [furey/mongodb-lens](https://github.com/furey/mongodb-lens) ⭐ 206 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-23 - Full Featured MCP Server for MongoDB Databases.
* [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp) ⭐ 195 | 🐛 10 | 🌐 Python | 📅 2026-08-24 - A Model Context Protocol (MCP) server for interacting with Meilisearch through LLM interfaces like Claude.
* [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks) ⭐ 185 | 🐛 7 | 🌐 Python | 📅 2026-08-21 - The StarRocks MCP Server acts as a bridge between AI assistants and StarRocks databases, allowing for direct SQL execution and database exploration without requiring complex setup or configuration.
* [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) ⭐ 185 | 🐛 14 | 🌐 Python | 📅 2025-10-07 - This MCP server enables LLMs to interact with Snowflake databases, allowing for secure and controlled data operations.
* [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) ⚠️ Archived - MCP server for searching and uploading records to Pinecone. Allows for simple RAG features, leveraging Pinecone's Inference API.
* [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) ⭐ 146 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-22 - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
* [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) ⭐ 111 | 🐛 5 | 🌐 JavaScript | 📅 2026-06-19 - A Model Context Protocol (MCP) server implementation that integrates with [Vectorize](https://vectorize.io/) for advanced Vector retrieval and text extraction.
* [oceanbase/mcp-oceanbase](https://github.com/oceanbase/mcp-oceanbase) ⭐ 108 | 🐛 6 | 🌐 Python | 📅 2026-06-09 - MCP Server for OceanBase database and its tools
* [felores/airtable-mcp](https://github.com/felores/airtable-mcp) ⭐ 75 | 🐛 1 | 🌐 JavaScript | 📅 2025-01-27 - Airtable Model Context Protocol Server.
* [da-okazaki/mcp-neo4j-server](https://github.com/da-okazaki/mcp-neo4j-server) ⭐ 59 | 🐛 6 | 🌐 TypeScript | 📅 2026-03-28 - A community built server that interacts with Neo4j Graph Database.
* [JexinSam/mssql\_mcp\_server](https://github.com/JexinSam/mssql_mcp_server) ⭐ 58 | 🐛 9 | 🌐 Python | 📅 2026-08-16 - MCP Server for MSSQL database in Python
* [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2026-03-25 - Query and analyze Azure Data Explorer databases.
* [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) ⭐ 47 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-01 - MCP Server that provides database interaction capabilities through [ArangoDB](https://arangodb.com/).
* [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) ⭐ 44 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-14 - Run queries against InfluxDB OSS API v2.
* [privetin/chroma](https://github.com/privetin/chroma) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2025-01-01 - Vector database server for semantic document search and metadata filtering, built on Chroma
* [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp) ⭐ 41 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-05 - A MCP server for AWS Athena to run SQL queries on Glue Catalog.
* [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) ⭐ 32 | 🐛 18 | 🌐 Python | 📅 2026-06-12 - Interact with the SingleStore database platform
* [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) ⭐ 29 | 🐛 6 | 🌐 Python | 📅 2026-08-16 - A Model Context Protocol (MCP) server implementation for [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) ⭐ 6,565 | 🐛 245 | 🌐 Rust | 📅 2026-08-24.
* [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) ⭐ 26 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-11 - A [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) server for Aiven.
* [prajwalnayak7/mcp-server-redis](https://github.com/prajwalnayak7/mcp-server-redis) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-05-05 - MCP server to interact with Redis Server, AWS Memory DB, etc for caching or other use-cases where in-memory and key-value based storage is appropriate
* [abel9851/mcp-server-mariadb](https://github.com/abel9851/mcp-server-mariadb) ⭐ 20 | 🐛 6 | 🌐 Python | 📅 2025-03-26 - MariaDB database integration with configurable access controls in Python.
* [suhail-ak-s/mcp-typesense-server](https://github.com/suhail-ak-s/mcp-typesense-server) ⭐ 19 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-14 - A Model Context Protocol (MCP) server implementation that provides AI models with access to Typesense search capabilities. This server enables LLMs to discover, search, and analyze data stored in Typesense collections.
* [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) ⭐ 10 | 🐛 5 | 🌐 JavaScript | 📅 2025-09-12 - Interact with an Apache Unomi CDP customer data platform to retrieve and update customer profiles
* [yuanoOo/oceanbase\_mcp\_server](https://github.com/yuanoOo/oceanbase_mcp_server) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-03-26 - (by yuanoOo) A Model Context Protocol (MCP) server that enables secure interaction with OceanBase databases.
* [lloydzhou/bitable-mcp](https://github.com/lloydzhou/bitable-mcp) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2025-11-03 - MCP server provides access to Lark Bitable through the Model Context Protocol. It allows users to interact with Bitable tables using predefined tools.

### Analytics

* [jjsantos01/qgis\_mcp](https://github.com/jjsantos01/qgis_mcp) ⭐ 1,070 | 🐛 16 | 🌐 Python | 📅 2025-10-01 - connects QGIS to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.
* [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) ⭐ 544 | 🐛 10 | 🌐 Python | 📅 2025-03-22 - MCP server for autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort. NOTE: Will execute arbitrary Python code on your machine, please use with caution!
* [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) ⭐ 513 | 🐛 8 | 🌐 Python | 📅 2026-08-05 - Query and analyze Prometheus - open-source monitoring system.
* [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) ⭐ 501 | 🐛 5 | 🌐 Python | 📅 2026-07-07 - The Official Model Context Protocol (MCP) server for Kagi search & other tools.
* [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) ⭐ 147 | 🐛 4 | 🌐 TypeScript | 📅 2026-07-09 - A Model Context Protocol (MCP) server implementation that integrates with Octagon Market Intelligence API.
* [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) ⭐ 127 | 🐛 4 | 🌐 Python | 📅 2025-04-14 - Optimize your AWS spend (including Amazon Bedrock spend) with this MCP server by examining spend across regions, services, instance types and foundation models ([demo video](https://www.youtube.com/watch?v=WuVOmYLRFmI\&feature=youtu.be)).
* [keboola/keboola-mcp-server](https://github.com/keboola/keboola-mcp-server) ⭐ 86 | 🐛 34 | 🌐 Python | 📅 2026-08-24 - Keboola Explorer Server MCP server
* [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) ⚠️ Archived - An MCP server to interact with a Tinybird Workspace from any MCP client.
* [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) ⭐ 78 | 🐛 3 | 🌐 Python | 📅 2026-08-03 - Give your coding agent direct access to up-to date Fantasy Premier League data
* [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) ⭐ 71 | 🐛 4 | 🌐 JavaScript | 📅 2025-02-07 - Interface with the Rijksmuseum API to search artworks, retrieve artwork details, access image tiles, and explore user collections.
* [privetin/dataset-viewer](https://github.com/privetin/dataset-viewer) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2025-04-25 - Browse and analyze Hugging Face datasets with features like search, filtering, statistics, and data export
* [lenwood/cfbd-mcp-server](https://github.com/lenwood/cfbd-mcp-server) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2025-05-06 - An MCP server for the [College Football Data API](https://collegefootballdata.com/).
* [syucream/lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server) ⭐ 26 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-09 - Interact with [Lightdash](https://www.lightdash.com/), a BI tool.
* [asusevski/opendota-mcp-server](https://github.com/asusevski/opendota-mcp-server) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-10-16 - Interact with OpenDota API to retrieve Dota 2 match data, player statistics, and more.

### AI Systems

* [modelcontextprotocol/sequentialthinking](https://github.com/modelcontextprotocol/servers/blob/main/src/sequentialthinking) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Dynamic and reflective problem-solving through thought sequences
* [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) ⭐ 387 | 🐛 12 | 🌐 TypeScript | 📅 2025-06-13 - Server for using HuggingFace Spaces, supporting Open Source Image, Audio, Text Models and more. Claude Desktop mode for easy integration.
* [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) ⭐ 350 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - Model Context Protocol server integrating DeepSeek's advanced language models, in addition to [other useful API endpoints](https://github.com/DMontgomery40/deepseek-mcp-server?tab=readme-ov-file#features) ⭐ 350 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19
* [YanxingLiu/dify-mcp-server](https://github.com/YanxingLiu/dify-mcp-server) ⭐ 280 | 🐛 4 | 🌐 Python | 📅 2025-04-20 - A simple implementation of an MCP server for dify workflows.
* [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) ⭐ 157 | 🐛 8 | 🌐 JavaScript | 📅 2025-05-01 - Interact with any OpenAI SDK Compatible Chat Completions API like OpenAI, Perplexity, Groq, xAI and many more.
* [deepfates/mcp-replicate](https://github.com/deepfates/mcp-replicate) ⚠️ Archived - Search, run and manage machine learning models on Replicate through a simple tool-based interface. Browse models, create predictions, track their status, and handle generated images.
* [ruixingshi/deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp) ⭐ 69 | 🐛 5 | 🌐 JavaScript | 📅 2025-03-25 - A MCP (Model Context Protocol) provider Deepseek reasoning content to MCP-enabled AI Clients, like Claude Desktop. Supports access to Deepseek's thought processes from the Deepseek API service or from a local Ollama server.
* [66julienmartin/MCP-server-Deepseek\_R1](https://github.com/66julienmartin/MCP-server-Deepseek_R1) ⭐ 69 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-09 - A Model Context Protocol (MCP) server implementation connecting Claude Desktop with DeepSeek's language models (R1/V3)
* [66julienmartin/MCP-server-Qwen\_Max](https://github.com/66julienmartin/MCP-server-Qwen_Max) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-16 - A Model Context Protocol (MCP) server implementation for the Qwen models.
* [whataboutyou-ai/eunomia-MCP-server](https://github.com/whataboutyou-ai/eunomia-MCP-server) ⚠️ Archived - Extension of the Eunomia framework that connects Eunomia instruments with MCP servers
* [thirdweb-dev/ai](https://github.com/thirdweb-dev/ai) - Read/write to over 2k blockchains, enabling data querying, contract analysis/deployment, and transaction execution, powered by Thirdweb

### MCP Tools

* [modelcontextprotocol/everything](https://github.com/modelcontextprotocol/servers/blob/main/src/everything) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - This MCP server exercises all the features of the MCP protocol. It is a test server for builders of MCP clients.
* [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) ⭐ 2,726 | 🐛 59 | 🌐 Python | 📅 2026-07-20 - Connect to MCP servers that run on SSE transport, or expose stdio servers as an SSE server.
* [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) ⭐ 1,532 | 🐛 22 | 🌐 JavaScript | 📅 2024-11-26 - This server is a server that installs other MCP servers for you.
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 867 | 🐛 2 | 🌐 Python | 📅 2026-08-23 - Open source (GPL-3.0) autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes, with proof of exploitation.
* [e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) ⚠️ Archived - This repository contains the source code for the [E2B](https://e2b.dev) MCP server.
* [liuyoshio/mcp-compass](https://github.com/liuyoshio/mcp-compass) ⭐ 245 | 🐛 4 | 🌐 JavaScript | 📅 2025-01-07 - Suggest the right MCP server for your needs
* [AIQL/chat-mcp](https://github.com/AI-QL/chat-mcp) ⭐ 242 | 🐛 1 | 🌐 HTML | 📅 2025-09-27 - – An Open Source Cross-platform GUI Desktop application compatible with Linux, macOS, and Windows, enabling seamless interaction with MCP servers across dynamically selectable LLMs, by **[AIQL](https://github.com/AI-QL/chat-mcp) ⭐ 242 | 🐛 1 | 🌐 HTML | 📅 2025-09-27**
* [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) ⭐ 147 | 🐛 5 | 🌐 Python | 📅 2026-02-27 - A MCP (Model Context Protocol) server that interacts with the Materials Project database, allowing for material search, structure visualization, and manipulation.
* [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) ⭐ 111 | 🐛 3 | 🌐 Python | 📅 2025-07-19 - MCP Server for Chronulus AI Forecasting and Prediction Agents
* [tesla0225/mcp-create](https://github.com/tesla0225/mcp-create) ⭐ 98 | 🐛 6 | 🌐 TypeScript | 📅 2025-05-17 - A dynamic MCP server management service that creates, runs, and manages Model Context Protocol servers on-the-fly.
* [fastnai/mcp-fastn](https://github.com/fastnai/mcp-fastn) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2026-06-07 - A remote, dynamic MCP server with a unified API that connects to 1,000+ tools, actions, and workflows, featuring built-in authentication and monitoring.
* [BuyWhere/buywhere-mcp](https://github.com/BuyWhere/buywhere-mcp?utm_source=awesome-claude-dxt\&utm_medium=referral\&utm_campaign=june30_25k\&utm_content=awesome-claude-dxt) ⭐ 9 | 🐛 10 | 🌐 JavaScript | 📅 2026-08-24 - Real-time product search and price-comparison MCP server for AI agents. 11M+ products across Shopee, Lazada, Amazon, Walmart, and 20+ retailers in Singapore, SEA, and US. Free API key with no signup.
* [unifai-network/unifai-mcp-server](https://github.com/unifai-network/unifai-mcp-server) ⭐ 5 | 🐛 0 | 📅 2025-06-13 - Dynamically search and call tools using UnifAI Network

### Knowledge Base

* [modelcontextprotocol/aws-kb-retrieval-server](https://github.com/modelcontextprotocol/servers/blob/main/src/aws-kb-retrieval-server) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Retrieval from AWS Knowledge Base using Bedrock Agent Runtime
* [modelcontextprotocol/memory](https://github.com/modelcontextprotocol/servers/blob/main/src/memory) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - Knowledge graph-based persistent memory system
* [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) ⭐ 21,204 | 🐛 82 | 🌐 Rust | 📅 2026-08-24 - 24/7 local screen & mic recording; MCP server lets agents search OCR, accessibility, and audio transcripts of everything you've seen, said, or heard. Works with Ollama.
* [basicmachines-co/basic-memory](https://github.com/basicmachines-co/basic-memory) ⭐ 3,741 | 🐛 67 | 🌐 Python | 📅 2026-08-24 - Local-first knowledge management system that builds a semantic graph from Markdown files, enabling persistent memory across conversations with LLMs.
* [dmayboroda/minima](https://github.com/dmayboroda/minima) ⭐ 1,046 | 🐛 14 | 🌐 Python | 📅 2026-01-22 - MCP server for RAG on local files
* [StevenStavrakis/obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) ⭐ 726 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-21 - (by Steven Stavrakis) An MCP server for Obsidian.md with tools for searching, reading, writing, and organizing notes.
* [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) ⭐ 380 | 🐛 5 | 🌐 TypeScript | 📅 2026-01-12 - The Model Context Protocol (MCP) Server enables integration between MCP clients and the Graphlit service. This document outlines the setup process and provides a basic example of using the client.
* [adityak74/mcp-scholarly](https://github.com/adityak74/mcp-scholarly) ⭐ 185 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - A MCP server to search for scholarly and academic articles.
* [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) ⭐ 184 | 🐛 6 | 🌐 JavaScript | 📅 2025-01-08 - An MCP server for interacting with your [Anki](https://apps.ankiweb.net/) decks and cards.
* [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) ⭐ 133 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - "primitive" RAG-like web search model context protocol (MCP) server that runs locally using Google's MediaPipe Text Embedder and DuckDuckGo Search. ✨ no APIs required ✨.
* [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp) ⭐ 102 | 🐛 2 | 🌐 Python | 📅 2025-07-27 - MCP (Model Context Protocol) server to manage documents and perform searches using [Needle](https://needle-ai.com) through Claude’s Desktop Application.
* [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) ⚠️ Archived - MCP Server Box is a Python project that integrates with the Box API to perform various operations such as file search, text extraction, AI-based querying, and data extraction. It leverages the `box-sdk-gen` library and provides a set of tools to interact with Box files and folders.
* [apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) ⭐ 92 | 🐛 4 | 🌐 JavaScript | 📅 2026-07-15 - Read and search through your XMind directory containing XMind files.
* [ProgramComputer/NASA-MCP-server](https://github.com/ProgramComputer/NASA-MCP-server) ⭐ 92 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-04 - Access to a unified gateway of NASA's data sources including but not limited to APOD, NEO, EPIC, GIBS.
* [run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) ⚠️ Archived - Integrate the data stored in a managed index on [LlamaCloud](https://cloud.llamaindex.ai/)
* [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) ⭐ 78 | 🐛 7 | 🌐 Python | 📅 2025-12-09 - A sample MCP server for AWS S3 that flexibly fetches objects from S3 such as PDF documents.
* [rember/rember-mcp](https://github.com/rember/rember-mcp) ⭐ 63 | 🐛 3 | 🌐 TypeScript | 📅 2025-03-28 - Create spaced repetition flashcards in Rember to remember anything you learn in your chats
* [hungryrobot1/MCP-PIF](https://github.com/hungryrobot1/MCP-PIF) ⭐ 57 | 🐛 1 | 🌐 Haskell | 📅 2025-10-20 - A Personal Intelligence Framework (PIF), providing tools for file operations, structured reasoning, and journal-based documentation to support continuity and evolving human-AI collaboration across sessions.
* [anshumax/world\_bank\_mcp\_server](https://github.com/anshumax/world_bank_mcp_server) ⭐ 50 | 🐛 1 | 🌐 Python | 📅 2025-08-17 - A server that fetches data indicators available with the World Bank as part of their data API
* [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP) ⭐ 43 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-07-21 - An MCP server implementation for interacting with the Unstructured API. This server provides tools to list sources and workflows.
* [Spathodea-Network/opencti-mcp](https://github.com/Spathodea-Network/opencti-mcp) ⭐ 40 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Interact with OpenCTI platform to retrieve threat intelligence data including reports, indicators, malware and threat actors.
* [skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) ⭐ 35 | 🐛 2 | 🌐 Python | 📅 2026-04-17 - An MCP server designed for interacting with the Rememberizer data source, facilitating enhanced knowledge retrieval.
* [GongRzhe/Langflow-DOC-QA-SERVER](https://github.com/GongRzhe/Langflow-DOC-QA-SERVER) ⚠️ Archived - A Model Context Protocol server for document Q\&A powered by Langflow. It demonstrates core MCP concepts by providing a simple interface to query documents through a Langflow backend.
* [longyi1207/glean-mcp-server](https://github.com/longyi1207/glean-mcp-server) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2025-01-08 - A server that uses Glean API to search and chat.
* [kiwamizamurai/mcp-kibela-server](https://github.com/kiwamizamurai/mcp-kibela-server) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-23 - Interact with Kibela API.
* [kpsunil97/devrev-mcp-server](https://github.com/kpsunil97/devrev-mcp-server) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2024-12-20 - An MCP server to integrate with DevRev APIs to search through your DevRev Knowledge Graph where objects can be imported from diff. sources listed [here](https://devrev.ai/docs/import#available-sources).
* [connerlambden/bgpt-mcp](https://github.com/connerlambden/bgpt-mcp) - Hosted MCP server for searching scientific papers with full-text experimental data. SSE + Streamable HTTP endpoints, 50 free searches, no API key needed.
* [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) - Read and search through your Obsidian vault or any directory containing Markdown notes

### Media Creation

* [modelcontextprotocol/everart](https://github.com/modelcontextprotocol/servers/blob/main/src/everart) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - AI image generation using various models
* [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) ⭐ 26,243 | 🐛 17 | 🌐 Python | 📅 2026-08-24 - Blender integration allowing prompt enabled 3D scene creation, modeling and manipulation.
* [Coding Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) ⭐ 5,349 | 🐛 70 | 🌐 JavaScript | 📅 2026-04-16 - A MCP server providing comprehensive Godot engine integration for project editing, debugging, and scene management.
* [zcaceres/mcp-markdownify-server](https://github.com/zcaceres/mcp-markdownify-server) ⭐ 2,980 | 🐛 24 | 🌐 TypeScript | 📅 2026-08-11 - MCP to convert almost anything to Markdown (PPTX, HTML, PDF, Youtube Transcripts and more)
* [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) ⭐ 1,874 | 🐛 3 | 🌐 C# | 📅 2026-08-10 - An MCP server that enables LLMs to interact with Unity3d Game Engine, supporting access to a variety of the Unit's Editor engine tools (e.g. Console Logs, Test Runner logs, Editor functions, hierarchy state, etc) and executing them as MCP tools or gather them as resources.
* [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) ⭐ 613 | 🐛 27 | 🌐 Python | 📅 2026-03-11 - This MCP allows an LLM to play and use Spotify.
* [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) ⭐ 576 | 🐛 17 | 🌐 Python | 📅 2026-08-15 - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, PDF, DOCX (.docx), csv and more.
* [ZubeidHendricks/youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) ⭐ 565 | 🐛 14 | 🌐 TypeScript | 📅 2026-08-08 - Comprehensive YouTube API integration for video management, Shorts creation, and analytics.
* [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) ⭐ 288 | 🐛 6 | 🌐 Python | 📅 2025-10-09 - A Model Context Protocol Server to add, edit, and search videos with [Video Jungle](https://www.video-jungle.com/).
* [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) ⭐ 236 | 🐛 5 | 🌐 Python | 📅 2025-05-20 - A server that generates mindmaps from input containing markdown code.
* [GongRzhe/Quickchart-MCP-Server](https://github.com/GongRzhe/Quickchart-MCP-Server) ⚠️ Archived - A Model Context Protocol server for generating charts using QuickChart.io
* [quazaai/UnityMCPIntegration](https://github.com/quazaai/UnityMCPIntegration) ⭐ 157 | 🐛 6 | 🌐 C# | 📅 2025-04-15 - Advanced Unity3d Game Engine MCP which supports ,Execution of Any Editor Related Code Directly Inside of Unity, Fetch Logs, Get Editor State and Allow File Access of the Project making it much more useful in Script Editing or asset creation.
* [mamertofabian/elevenlabs-mcp-server](https://github.com/mamertofabian/elevenlabs-mcp-server) ⭐ 118 | 🐛 3 | 🌐 Python | 📅 2025-01-07 - A server that integrates with ElevenLabs text-to-speech API capable of generating full voiceovers with multiple voices.
* [dschuler36/reaper-mcp-server](https://github.com/dschuler36/reaper-mcp-server) ⭐ 117 | 🐛 1 | 🌐 Python | 📅 2026-08-19 - Interact with your [Reaper](https://www.reaper.fm/) (Digital Audio Workstation) projects.
* [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) ⭐ 100 | 🐛 7 | 🌐 Python | 📅 2025-05-16 - Generate visualizations from fetched data using the VegaLite format and renderer.
* [GongRzhe/Image-Generation-MCP-Server](https://github.com/GongRzhe/Image-Generation-MCP-Server) ⚠️ Archived - This MCP server provides image generation capabilities using the Replicate Flux model.
* [Pantani/tdmcp](https://github.com/Pantani/tdmcp) ⭐ 35 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-15 - Build real TouchDesigner node networks from plain language (audio-reactive visuals, feedback loops, particles, generative art, projection mapping) with a create→verify→preview loop. Ships a one-click .dxt for Claude Desktop.
* [MohamedAbdallah-14/prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) ⭐ 18 | 🐛 14 | 🌐 TypeScript | 📅 2026-08-12 - MCP server and CLI that generates production-ready visual assets (app icons, favicons, OG images, logos) by routing each request across 30+ image generation models. Zero API key for first run via Pollinations, Stable Horde, and HuggingFace free tiers.
* [felores/placid-mcp-server](https://github.com/felores/placid-mcp-server) ⭐ 14 | 🐛 2 | 🌐 TypeScript | 📅 2025-03-28 - Generate image and video creatives using Placid.app templates
* [felores/cloudinary-mcp-server](https://github.com/felores/cloudinary-mcp-server) ⭐ 10 | 🐛 2 | 🌐 JavaScript | 📅 2025-03-13 - Cloudinary Model Context Protocol Server to upload media to Cloudinary and get back the media link and details.

### Productivity

* [modelcontextprotocol/gdrive](https://github.com/modelcontextprotocol/servers/blob/main/src/gdrive) ⭐ 89,832 | 🐛 542 | 🌐 TypeScript | 📅 2026-08-20 - File access and search capabilities for Google Drive

* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) ⭐ 5,789 | 🐛 194 | 🌐 Python | 📅 2026-08-20 - Interact with Atlassian Cloud products (Confluence and Jira) including searching/reading Confluence spaces/pages, accessing Jira issues, and project metadata.

* [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) ⭐ 4,132 | 🐛 68 | 🌐 Python | 📅 2026-04-12 - Excel manipulation including data reading/writing, worksheet management, formatting, charts, and pivot table.

* [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) ⭐ 3,398 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-22 - Open-source Claude Code skills for SEO, GEO, Google Ads, and Meta Ads (\~2.9k stars). Connects to live data via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP for site audits, keyword research, ad audits, and wasted-spend detection.

* [nspady/google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) ⭐ 1,174 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-01 - Google Calendar MCP Server for managing Google calendar events. Also supports searching for events by attributes like title and location.

* [abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) ⭐ 392 | 🐛 17 | 🌐 JavaScript | 📅 2025-04-20 - Interact with Todoist to manage your tasks.

* [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) ⭐ 347 | 🐛 20 | 🌐 JavaScript | 📅 2025-05-01 - Allows LLM to interact with Linear's API for project management, including searching, creating, and updating issues.

* [echelon-ai-labs/servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp) ⭐ 292 | 🐛 32 | 🌐 Python | 📅 2026-04-26 - A MCP server to interact with a ServiceNow instance

* [open-strategy-partners/osp\_marketing\_tools](https://github.com/open-strategy-partners/osp_marketing_tools) ⭐ 273 | 🐛 13 | 🌐 Python | 📅 2025-04-23 - Content editing codes, value map, and positioning tools for product marketing.

* [vasylenko/claude-desktop-extension-bear-notes](https://github.com/vasylenko/claude-desktop-extension-bear-notes) ⭐ 206 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-09 - Search, read, create, and update Bear Notes directly from Claude. Local-only with complete privacy.

* [smn2gnt/MCP-Salesforce](https://github.com/smn2gnt/MCP-Salesforce) ⭐ 178 | 🐛 2 | 🌐 Python | 📅 2026-07-29 - Interact with Salesforce Data and Metadata

* [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) ⭐ 168 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-10 - A Model Context Protocol server that enables Make scenarios to be utilized as tools by AI assistants. This integration allows AI systems to trigger and interact with your Make automation workflows.

* [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) ⭐ 157 | 🐛 25 | 🌐 TypeScript | 📅 2026-06-08 - Google Tasks API Model Context Protocol Server.

* [v-3/notion-server](https://github.com/v-3/notion-server) ⭐ 119 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-01 - Notion MCP integration. Search, Read, Update, and Create pages through Claude chat.

* [MohamedAbdallah-14/unslop](https://github.com/MohamedAbdallah-14/unslop) ⭐ 108 | 🐛 1 | 🌐 Python | 📅 2026-08-21 - MCP server and CLI that removes named AI writing tells from text: tricolons, em-dash pileups, hedging stacks, sycophancy openers, overused vocab like "delve" and "crucial". Lint-only audit mode included. Five intensity levels.

* [horizondatawave/hdw-mcp-server](https://github.com/horizondatawave/hdw-mcp-server) ⭐ 63 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-06 - Access to profile data and management of user account with [HorizonDataWave.ai](https://horizondatawave.ai/).

* [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) ⭐ 62 | 🐛 10 | 🌐 TypeScript | 📅 2026-01-17 - Read, update, delete, publish content in your [Contentful](https://contentful.com/) space(s) from this MCP Server.

* [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) ⭐ 40 | 🐛 3 | 🌐 Python | 📅 2026-07-14 - MCP server for eSignatures (<https://esignatures.com>)

* [sakce/mcp-server-monday](https://github.com/sakce/mcp-server-monday) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2025-09-10 - MCP Server to interact with Monday.com boards and items.

* [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server) ⭐ 29 | 🐛 5 | 🌐 Python | 📅 2026-05-13 - This MCP (Model Context Protocol) server provides integration between Fibery and any LLM provider supporting the MCP protocol (e.g., Claude for Desktop), allowing you to interact with your Fibery workspace using natural language.

* [hichana/goalstory-mcp](https://github.com/hichana/goalstory-mcp) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-05 - a Goal Tracker and Visualization Tool for personal and professional development.

* [kenjihikmatullah/productboard-mcp](https://github.com/kenjihikmatullah/productboard-mcp) ⭐ 13 | 🐛 5 | 🌐 TypeScript | 📅 2025-02-26 - Integrate the Productboard API into agentic workflows via MCP.

* [devhub/devhub-cms-mcp](https://github.com/devhub/devhub-cms-mcp) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2025-03-24 - Manage and utilize website content within the DevHub CMS platform

* [transcribe-app/mcp-transcribe](https://github.com/transcribe-app/mcp-transcribe) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-03 - This service provides fast and reliable transcriptions for audio/video files and voice memos. It allows LLMs to interact with the text content of audio/video files.

* [syucream/holaspirit-mcp-server](https://github.com/syucream/holaspirit-mcp-server) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-01 - Interact with [Holaspirit](https://www.holaspirit.com/).

* [LMCP](https://www.local-mcp.com) - Connect your AI to Mail, Calendar, Teams, Outlook, OneDrive, Excel, Word, WhatsApp and 95+ more local tools. Runs 100% locally, no API keys, GDPR compliant. macOS + Windows. [Download .mcpb](https://download.local-mcp.com/local-mcp.mcpb)

### Professional Apps

* [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) ⭐ 15,708 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-07 - Give your coding agent direct access to Figma file data, helping it one-shot design implementation.
* [MFYDev/ghost-mcp](https://github.com/MFYDev/ghost-mcp) ⭐ 225 | 🐛 7 | 🌐 TypeScript | 📅 2026-04-27 - A Model Context Protocol (MCP) server for interacting with Ghost CMS through LLM interfaces like Claude.
* [GongRzhe/TRAVEL-PLANNER-MCP-Server](https://github.com/GongRzhe/TRAVEL-PLANNER-MCP-Server) ⚠️ Archived - Travel planning and itinerary management server integrating with Google Maps API for location search, place details, and route calculations.
* [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) ⭐ 99 | 🐛 6 | 🌐 Python | 📅 2026-06-12 - An MCP server to query and retrieve medical images and for parsing and reading dicom-encapsulated documents (pdf etc.).
* [Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) ⭐ 75 | 🐛 3 | 🌐 TypeScript | 📅 2026-06-07 - This MCP server integrates with The Movie Database (TMDB) API to provide movie information, search capabilities, and recommendations.
* [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) ⭐ 59 | 🐛 3 | 🌐 TypeScript | 📅 2025-08-26 - Access Dutch Railways (NS) real-time train travel information and disruptions through the official NS API.
* [kapilduraphe/webflow-mcp-server](https://github.com/kapilduraphe/webflow-mcp-server) ⭐ 21 | 🐛 3 | 🌐 TypeScript | 📅 2025-03-21 - Interfact with the Webflow APIs

### Finance

* [stripe/agent-toolkit](https://github.com/stripe/agent-toolkit) ⭐ 1,762 | 🐛 77 | 🌐 TypeScript | 📅 2026-08-22 - The Stripe Model Context Protocol server allows you to integrate with Stripe APIs through function calling. This protocol supports various tools to interact with different Stripe services.
* [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) ⭐ 382 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-01 - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
* [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) ⭐ 353 | 🐛 112 | 🌐 TypeScript | 📅 2026-06-05 - This is a Model Context Protocol (MCP) server implementation for Xero. It provides a bridge between the MCP protocol and Xero's API, allowing for standardized access to Xero's accounting and business features.
* [bankless/onchain-mcp](https://github.com/bankless/onchain-mcp) ⭐ 80 | 🐛 10 | 🌐 TypeScript | 📅 2026-05-05 - MCP (Model Context Protocol) server for blockchain data interaction through the Bankless API.
* [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) ⭐ 74 | 🐛 1 | 🌐 Python | 📅 2026-02-28 - MCP server for stock market data API [AlphaVantage](https://www.alphavantage.co/)
* [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) ⭐ 70 | 🐛 2 | 🌐 Python | 📅 2025-12-09 - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.
* [Heurist Network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) ⭐ 66 | 🐛 4 | 🌐 Python | 📅 2026-03-25 - Access specialized web3 AI agents for blockchain analysis, smart contract security, token metrics, and blockchain interactions through the [Heurist Mesh network](https://github.com/heurist-network/heurist-agent-framework/tree/main/mesh) ⭐ 820 | 🐛 35 | 🌐 Python | 📅 2026-07-26.
* [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) ⭐ 57 | 🐛 5 | 🌐 Python | 📅 2025-05-07 - A mcp server for tracking cryptocurrency whale transactions.
* [KukaPay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2025-05-10 - Providing real-time and historical Crypto Fear & Greed Index data.
* [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) ⭐ 44 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-08 - A comprehensive MCP server for tooling interactions (40+) and resource accessibility (60+) plus many useful prompts for interacting with the Algorand blockchain.
* [mektigboy/server-hyperliquid](https://github.com/mektigboy/server-hyperliquid) ⭐ 44 | 🐛 6 | 🌐 TypeScript | 📅 2025-03-06 - An MCP server implementation that integrates the Hyperliquid SDK for exchange data.
* [Kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) ⭐ 41 | 🐛 6 | 🌐 Python | 📅 2025-05-04 - A mcp server that bridges Dune Analytics data to AI agents.
* [longmans/coin\_api\_mcp](https://github.com/longmans/coin_api_mcp) ⭐ 37 | 🐛 5 | 🌐 Python | 📅 2025-02-14 - Provides access to [coinmarketcap](https://coinmarketcap.com/) cryptocurrency data.
* [ramp-public/ramp-mcp](https://github.com/ramp-public/ramp-mcp) ⚠️ Archived - A Model Context Protocol server for retrieving and analyzing data or running tasks for [Ramp](https://ramp.com) using [Developer API](https://docs.ramp.com/developer-api/v1/overview/introduction). In order to get around token and input size limitations, this server implements a simple ETL pipeline + ephemeral sqlite database in memory for analysis by an LLM. All requests are made to demo by default, but can be changed by setting `RAMP_ENV=prd`. Large datasets may not be processable due to API and/or your MCP client limitations.
* [magnetai/mcp-free-usdc-transfer](https://github.com/magnetai/mcp-free-usdc-transfer) ⭐ 21 | 🐛 4 | 🌐 JavaScript | 📅 2025-01-17 - Send USDC on [Base](https://base.org/) for free using Claude AI! Built with [Coinbase CDP](https://docs.cdp.coinbase.com/mpc-wallet/docs/welcome).
* [john-zhang-dev/xero-mcp](https://github.com/john-zhang-dev/xero-mcp) ⭐ 21 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-23 - Enabling clients to interact with Xero system for streamlined accounting, invoicing, and business operations.
* [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2025-05-27 - This MCP server integrates with [Fewsats](https://fewsats.com) and allows AI Agents to purchase anything in a secure way.
* [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-02-17 - A powerful and efficient Blockchain address risk scoring API MCP Server, leveraging the BICScan API to provide comprehensive risk assessments and asset information for blockchain addresses, domains, and decentralized applications (dApps).
* [Adfin-Engineering/mcp-server-adfin](https://github.com/Adfin-Engineering/mcp-server-adfin) ⭐ 11 | 🐛 3 | 🌐 Python | 📅 2025-03-20 - 1. Python 3.10 or higher
* [marctheshark3/ergo-mcp](https://github.com/marctheshark3/ergo-mcp) ⭐ 3 | 🐛 0 | 🌐 Roff | 📅 2025-06-02 - -An MCP server to integrate Ergo Blockchain Node and Explorer APIs for checking address balances, analyzing transactions, viewing transaction history, performing forensic analysis of addresses, searching for tokens, and monitoring network status.
* [araa47/jupiter-mcp](https://github.com/araa47/jupiter-mcp) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2025-08-13 - A Model Context Protocol server for Solana DeFi interactions through Jupiter Exchange. Provides tools for token swaps, limit orders, balance checking, and portfolio management on Solana.

### examples

* [hello-world-node](https://github.com/anthropics/dxt/tree/main/examples/hello-world-node) ⭐ 2,085 | 🐛 96 | 🌐 TypeScript | 📅 2026-05-26 - Basic MCP server with simple time tool
* [Blender](./servers/blender-mcp) - Blender Model Context Protocol Integration

```json
{
  "dxt_version": "0.1",
  "name": "blender-mcp",
  "display_name": "Blender",
  "version": "1.2",
  "description": "Blender Model Context Protocol Integration",
  "author": {
    "name": "ahujasid"
  },
  "server": {
    "type": "python",
    "entry_point": "main.py",
    "mcp_config": {
      "command": "uvx",
      "args": [
        "blender-mcp@1.2"
      ]
    }
  },
  "license": "MIT"
}
```

## Documentation & Tutorials

* [desktop-extensions](https://www.anthropic.com/engineering/desktop-extensions)

## Development Tools

* [Claude code](https://docs.anthropic.com/en/docs/claude-code/overview) - AI tools like Claude Code are particularly good at creating desktop extensions

## Packaging & Management Tools

* [mcp-linker](https://github.com/milisp/mcp-linker) ⭐ 321 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-17 - Cross-platform MCP management tool with planned .dxt support 🚀
* [@anthropic-ai/dxt](https://www.npmjs.com/package/@anthropic-ai/dxt) - Official packaging toolkit
* [@anthropic-ai/mcpb](https://www.npmjs.com/package/@anthropic-ai/mcpb) - Official packaging mcpb toolkit

## About awesome-claude-dxt

Curated by [@milisp](https://github.com/milisp) | Author of [mcp-linker](https://github.com/milisp/mcp-linker) ⭐ 321 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-17

***

**[⬆ Back to Top](#What-is-DXT)**
*Last updated: 09 2025*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
