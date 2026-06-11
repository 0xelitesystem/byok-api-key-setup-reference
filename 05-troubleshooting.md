# Troubleshooting

Most BYOK setup problems come down to a key pasted incorrectly, a key on the wrong account, no funded balance, a hit spending cap, or the wrong model selected. Check those before assuming the tool is broken.

## The key is rejected

If a tool says the key is invalid, first confirm it was pasted completely, with no extra spaces or missing characters, since keys are long and easy to truncate. Confirm the key has not been revoked and that it belongs to the account you funded. If in doubt, generate a fresh key, paste it carefully, and try again. A mistyped or stale key is the most common cause.

## Requests fail with a billing or quota message

A failure that mentions billing, quota, or insufficient funds usually means the account has no funded balance, or the spending cap has been reached. Check the provider dashboard for the current balance and whether the cap was hit. If the cap was reached, that is the safety limit doing its job; raise it deliberately only if the spend was legitimate. Add credit if the balance is empty.

## Usage costs more than expected

If the bill climbs faster than expected, the cause is usually the model selected or the size of the requests, not a fault in the key. A larger model costs more per token, and long prompts or long outputs use more tokens. Check which model the tool is using and whether prompts are larger than needed. The cap and alerts you set earlier are what keep this from becoming a surprise.

## When to suspect the tool

Suspect the tool itself only after ruling out the key, the account, the balance, the cap, and the model. If those all check out and requests still fail, look at the tool's own settings, such as which provider or endpoint it is configured for. Working through the cheap checks first, in order, isolates the cause faster than assuming the worst and saves the most time.
