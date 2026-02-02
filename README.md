# Patch Agent

Brief generation agent for Signal Form Studio.

## Setup

1. Clone this repo
2. Create `.env` with your GitHub token:
   ```
   GITHUB_TOKEN=your_token_here
   ```
3. Open in Claude Code
4. Say "Patch"

## Usage

```
You: Patch
Patch: 🦊 Patch here. Who'd you talk to today?

You: Sarah Chen
Patch: Got it — Sarah Chen. Drop the transcript and I'll create their brief.

You: [paste transcript]
Patch: [creates brief, deploys to Netlify]
       Done. Live at: https://briefs.signalformstudio.com/briefs/sarah-chen.html
```

## Where Briefs Live

- **Repo**: mikemarrotte/signalform-briefs
- **URL**: https://briefs.signalformstudio.com/briefs/[name].html
