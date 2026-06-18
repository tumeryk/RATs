# Repository of AI Tools ( RATs )

This repository maintains a curated list of AI tools commonly accessed by enterprise workforces. As organizations adopt Generative AI, they face important security and governance decisions: whether to allow employee access to external AI applications, and how to manage the risks associated with that access.

Unregulated use of AI tools can lead to Data Loss, exposure of Personally Identifiable Information (PII), leakage of confidential company information, and inadvertent sharing of intellectual property. This repository helps enterprises evaluate these tools and decide which AI services should be allowed, restricted, or blocked.

By integrating this list with DNS-based controls or the Tumeryk Chrome Extension, organizations can enforce safe access policies across their workforce. Combined with the Tumeryk AI Trust Score Platform, companies can further implement advanced AI policy enforcement, ensuring that only trusted and compliant AI services are used within the enterprise.

## File

`ai-tools.json` — curated enterprise platforms at the top (~108 entries), followed by the full bulk catalog (~19k `"AI Tool"` entries). Edit the JSON directly when updating the curated list.

## JSON format (do not change field names)

```json
{
  "service_name": "<SERVICE NAME>",
  "service_category": "<SERVICE CATEGORY>",
  "url": "<FULL URL>"
}
```

Curated categories include: `General AI Assistant`, `AI Search Engine`, `AI Code Assistant`, `AI Character Chat`, `AI Companion`, `AI Image Generation`, `AI Video Generation`, `AI Voice & Audio`, `AI Productivity`, and others. Bulk catalog entries use `"AI Tool"`.

