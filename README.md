# veo-verse-prompt
An open-source (Apache 2.0) collection of video prompts for Google's Veo. Share
and discover creative prompts for Veo, including those for current and anticipated future versions like Veo 2 and Veo 3.

## Directory structure
Video metadata is stored in JSONC files organized by Veo version.

Example:

```
veo/futuristic-cityscape.jsonc
```

Each JSONC file contains fields such as:

```jsonc
{
  "title": "...",
  "description": "...",
  "prompt": "...",
  "version": "...",
  "uploadDate": "...",
  "author": "...",
  "videoUrl": "..."
  // optional comments
}
```
