# Multi-Agent System with OpenAI Agents SDK

This notebook demonstrates a comprehensive implementation of a multi-agent system using the OpenAI Agents SDK. It showcases how to build and orchestrate complex agent workflows with specialized roles, shared context, and inter-agent communication.

## Key Features

- **Authentication System**: User verification with context persistence
- **Multilingual Support**: Specialized English and Swahili language agents
- **Agent Routing**: Central routing agent for request delegation
- **Product Information**: Product details retrieval with permission checks
- **Feedback Processing**: Tools for sending emails and creating CRM tickets

## Components

1. **Authentication Agent**: Verifies user credentials securely
2. **Router Agent**: Directs requests to appropriate specialized agents
3. **Language Agents**: Handle communication in specific languages
4. **Product Agents**: Access and provide product information
5. **Feedback Agent**: Process customer feedback via multiple channels

## Advanced SDK Concepts

- Agent handoffs for delegation between specialists
- Context management for stateful interactions
- Converting agents to tools for specialized capabilities
- Type-safe function tools with Pydantic models
- Security boundaries for data access

## Usage

The notebook contains multiple runnable demos:
- `standalone_auth_agent()` - Authentication only
- `router_and_auth_agent()` - Authentication with language routing
- `router_with_product_info()` - Full system with product information
- `router_with_product_feedback()` - Complete system with feedback handling

Each demo accepts user messages and shows the progression of processing through multiple agents.