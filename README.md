# Repo Debugger — Repository Debugging Agent

An AI agent built on TrueForge that inspects GitHub repositories, diagnoses bugs, and applies fixes only after human approval.

## What it does

1. Takes a GitHub repository URL and error description
2. Inspects repo structure and relevant files using GitHub MCP tools
3. Identifies root cause with evidence
4. Proposes a fix
5. Asks for human approval before making any changes
6. Applies fix only after approval

## Built with

- TrueForge (agent harness)
- Gemini Flash (model)
- GitHub MCP (tools)
- Qodo (code review)

## How to run

1. Install TrueForge: `npx @truefoundry/trueforge`
2. Open `http://localhost:8790`
3. Add Gemini API key in Settings → Models
4. Add GitHub token in Settings → Connectors
5. Load the `repo-debugger` agent from Agents Library
6. Give it a repo URL and error description

## Agent Harness Hackathon — WeMakeDevs
