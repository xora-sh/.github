## Xora Runs FFmpeg Without Managing the Infrastructure

[Xora](https://xora.sh/) puts FFmpeg behind a production-ready API for developers, automated workflows, and AI agents. Submit your own FFmpeg arguments or choose a ready-made recipe, and let Xora handle media processing in the cloud.

### Flexible Media Processing

Xora supports standard FFmpeg arguments, codec flags, filter graphs, and multiple inputs. For common tasks, it offers recipes for video compression, thumbnails, trimming, concatenation, and audio extraction. Probe mode provides enriched media metadata before processing, while reusable presets simplify recurring jobs.

### Built for Automation

Xora provides job tracking, structured errors, idempotency keys, and webhooks to help developers build reliable media workflows. Its OpenAPI specification, `llms.txt` reference, and remote MCP server also support integration with AI agents.

By handling infrastructure such as workers, CPU resources, temporary storage, queues, retries, and autoscaling, Xora lets developers use FFmpeg without managing the systems behind it.
