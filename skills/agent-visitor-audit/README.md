# Agent visitor audit

A read-only skill for exploring whether a visitor using an AI agent can find the public information needed for a specific task. Give it a URL and a concrete question, such as finding a product's price and return policy. It reports what was observed, where the journey became difficult and what could not be verified.

This is an evidence-based review, not a certification, security audit or guarantee that every agent can access the site. The result depends on the tools and access available to the agent performing it.

## Try it

1. Copy [SKILL.md](SKILL.md) into a folder named `agent-visitor-audit` in your project's agent skills directory, or give its path to a compatible coding agent.
2. Ask the agent to follow it with a URL and a specific visitor task:

   > Follow agent-visitor-audit/SKILL.md. On https://example.com/, check whether a visitor can find information about the service and contact the business. Show the pages you checked, the evidence and anything you could not verify.

3. Review the report and its limitations. The example domain is a placeholder; replace it with a site you intend to inspect. The skill uses public read-only access and does not submit forms or place orders.

Companion article: [Your next website visitor might be an AI agent](https://ndimitratos.com/articles/your-next-website-visitor-might-be-an-ai-agent/).
