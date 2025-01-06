# AlexaSkillsRepo

Created a custom alexa skill called chat demo that makes a synchronous invocation to the ChatGPT API using an API Key.

Invocation Name
chat demo

Intent
HelloWorldIntent

Slot
catchAll //takes user command as input and sends it to OpenAI

Specifications
"language": "JavaScript/NodeJs",
"model" : "gpt-4o-mini",
"ask-sdk-core": "^2.7.0",
"ask-sdk-model": "^1.19.0",
"aws-sdk": "^2.326.0",
"sync-request": "6.1.0"
