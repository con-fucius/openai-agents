# Email-Sending Agent with OpenAI Agents SDK

This notebook demonstrates a simple but powerful email-sending agent built with the OpenAI Agents SDK and integrated with external services.

## Key Features

- Send formatted emails through a conversational interface
- Integration with Resend.com for email delivery
- Custom model provider using Nebius AI (Meta Llama 3.1)
- Asynchronous execution for responsive operation

## Components

1. **Custom Model Provider**: Configures the agent to use Nebius AI models
2. **Email-Sending Tool**: Function tool for composing and sending emails
3. **Agent Configuration**: Instructions for handling email requests
4. **Runner Setup**: Executes the agent with the appropriate configuration

## Technical Implementation

- Demonstrates how to create a custom model provider for non-OpenAI models
- Shows how to implement practical function tools for real-world tasks
- Illustrates asynchronous API integration patterns
- Provides a template for creating single-purpose utility agents

## Usage

The notebook contains a complete example that:
1. Sets up dependencies and API connections
2. Defines the email-sending tool
3. Creates and configures an agent
4. Processes a user request to send an email

This serves as a practical reference for implementing agents with external service integration.