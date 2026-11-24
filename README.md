# Job Clerk extension for Gemini CLI

Search and read public physician job adverts in Germany from [Job Clerk](https://jobclerk.de),
with the employer's original text and a link to the source. Search its medical events calendar for upcoming courses, congresses and webinars. No account or API key is needed.

```bash
gemini extensions install https://github.com/ainergiz/jobclerk-gemini-extension
```

Then ask, for example:

- Find upcoming night-duty courses for internal medicine and link to the calendar.
- Find cardiology training posts (Assistenzarzt) in Berlin.
- Which jobs in Bavaria mention a Berufserlaubnis? Show the evidence.
- Which filters are available for jobs in Hamburg?

The extension connects to the public MCP server at `https://jobclerk.de/mcp`. It is read-only.
[Documentation](https://jobclerk.de/fuer-agenten) · [Privacy](https://jobclerk.de/datenschutz) · [Imprint](https://jobclerk.de/impressum)
