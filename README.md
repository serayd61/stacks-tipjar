# Stacks Tip Jar

Creator monetization platform on Stacks blockchain. Accept tips and donations with on-chain tracking.

## Features

- **Creator Profiles**: Register with name and bio
- **Tip Messages**: Send tips with optional messages
- **Stats Tracking**: Track tips sent and received
- **Leaderboards**: See top tippers and creators

## Functions

```clarity
(register-creator (name) (bio))
(update-profile (name) (bio))
(send-tip (creator) (amount) (message))
```

## Usage

```clarity
;; Register as creator
(contract-call? .tipjar register-creator u"Alice" u"Building on Stacks")

;; Send a tip
(contract-call? .tipjar send-tip 'SP1234... u1000000 (some u"Great work!"))
```

## License

MIT



---
## Tip Jar on Stacks
- ✅ Accept STX tips
- ✅ Track contributions
- ✅ Deployed on mainnet
