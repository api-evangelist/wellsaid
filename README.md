# WellSaid Labs (wellsaid)

WellSaid Labs is an AI text-to-speech voice platform. Its REST API renders natural-sounding speech from text using studio-quality voice avatars, supporting synchronous clip creation, low-latency audio streaming, and word-level timing with subtitles, authenticated with an X-Api-Key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wellsaid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wellsaid/refs/heads/main/apis.yml)

## Tags

- AI
- Text to Speech
- Voice
- Audio
- TTS

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### WellSaid Text-to-Speech API

Render text to speech using studio-quality voice avatars. Create clips asynchronously (POST /tts/clips), list and retrieve rendered clips, and combine multiple clips into a single file with custom pauses.

- **Human URL:** [https://docs.wellsaidlabs.com/reference/getting-started-with-your-api](https://docs.wellsaidlabs.com/reference/getting-started-with-your-api)
- **Base URL:** `https://api.wellsaidlabs.com/v1`

#### Tags

- Text to Speech
- Audio
- Clips

#### Properties

- [Documentation](https://docs.wellsaidlabs.com/reference/getting-started-with-your-api)
- [API Reference](https://docs.wellsaidlabs.com/reference)
- [OpenAPI](openapi/wellsaid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellsaid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellsaid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellSaid Streaming TTS API

Low-latency streaming text-to-speech (POST /tts/stream) that returns an audio/mpeg (MP3) stream as the render is produced, plus word-timing renders (POST /tts/word-timing) returning audio with JSON/SRT/VTT subtitle timing.

- **Human URL:** [https://docs.wellsaidlabs.com/reference/ttsstream](https://docs.wellsaidlabs.com/reference/ttsstream)
- **Base URL:** `https://api.wellsaidlabs.com/v1`

#### Tags

- Streaming
- Text to Speech
- Audio

#### Properties

- [Documentation](https://docs.wellsaidlabs.com/reference/ttsstream)
- [API Reference](https://docs.wellsaidlabs.com/reference)
- [OpenAPI](openapi/wellsaid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellsaid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellsaid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WellSaid Voices and Speakers API

List available voice avatars (GET /tts/avatars) with their speaker_id, name, accent, and speaking style for selecting a voice, plus respelling suggestions and replacement libraries that shape pronunciation across renders.

- **Human URL:** [https://docs.wellsaidlabs.com/reference/available-voice-avatars](https://docs.wellsaidlabs.com/reference/available-voice-avatars)
- **Base URL:** `https://api.wellsaidlabs.com/v1`

#### Tags

- Voices
- Speakers
- Avatars

#### Properties

- [Documentation](https://docs.wellsaidlabs.com/reference/available-voice-avatars)
- [API Reference](https://docs.wellsaidlabs.com/reference)
- [OpenAPI](openapi/wellsaid-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellsaid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellsaid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/wellsaid-labs)
- [LinkedIn](https://www.linkedin.com/company/wellsaid-labs)
- [Website](https://wellsaidlabs.com)
- [Documentation](https://docs.wellsaidlabs.com)
- [Plans](plans/wellsaid-plans-pricing.yml)
- [Rate Limits](rate-limits/wellsaid-rate-limits.yml)
- [Fin Ops](finops/wellsaid-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
