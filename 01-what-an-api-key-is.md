# What an API key is

An API key is a secret string that identifies you to an AI provider and authorizes usage billed to your account. In a bring-your-own-key setup, you paste your own key into a tool so the tool's requests run on your provider account at the provider's rates.

## The key as a credential

An API key works like a password for programmatic access. When a tool sends a request to the provider using your key, the provider knows the request is yours and bills the usage to your account. Anyone who has the key can use it and run up charges, which is why a key is a secret to be protected exactly like a password.

## Why BYOK uses your own key

In a bundled tool, the tool uses its own provider account and charges you a price that includes a markup on the usage. In bring-your-own-key, you supply your own key, so the usage is billed to you by the provider directly at their rates, and the tool charges only for its software. The key is the mechanism that routes the cost to your account instead of the tool's.

## What you control with your own key

Holding your own key means you control the provider account behind it: the spending limits, the usage history, the model access, and the ability to revoke the key at any time. This is the practical benefit of BYOK beyond cost: visibility and control over usage sit with you, not with a tool whose internals you cannot see. The key is what makes that control yours.

## The responsibility that comes with it

The flip side of control is responsibility. Because the key bills to your account, protecting it and capping its spend are your job. A bundled tool hides this responsibility along with the markup; BYOK trades the markup for the duty of managing the key. The rest of this reference is about doing that part well.
