# Keeping keys safe

Keep API keys out of client-side code, public repositories, screenshots, and chat with third parties. Store them where only you and your tools can reach them, and revoke any key that is ever exposed.

## Never in the front end

A key placed in client-side JavaScript, HTML, or a public build is visible to anyone who views the page or its source. Keys belong on the server side or behind a proxy, never in code that ships to the browser. If a tool asks you to paste a key into something that runs in the browser and is publicly accessible, treat that as a red flag for that tool's design.

## Never in public places

Keys must stay out of public repositories, public screenshots, recorded videos, and messages to third parties. Automated scanners actively look for exposed keys in public code and can find and abuse them within minutes of a commit. A key that touches any public surface should be considered compromised and rotated immediately, even if you deleted it right after.

## Store them deliberately

Keep keys in a password manager, a platform secret store, or an environment variable that is not committed to a repository, rather than loose in a document or a note. The goal is that the key lives in one controlled place, is pasted only into the tools that need it, and is never copied into casual storage. Treating a key with the same care as a password is the right mental model.

## Rotate and revoke

If a key is ever exposed, or you simply no longer use it, revoke it on the provider platform and generate a fresh one. Rotation is cheap and instant, and it is the correct response to any doubt about a key's safety. A revoked key cannot be abused no matter who has it. Make rotation a routine habit rather than an emergency measure, and an exposure becomes a minor cleanup rather than a billing event.
