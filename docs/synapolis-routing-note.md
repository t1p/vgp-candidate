# Synapolis Routing Note

For city / assembly publication, the correct delivery path is not the local Telegram topic and not Grist `Crr_feedback`.

## Canonical control thread
- `https://t.me/c/37222190439/65`

## Currently verified transport
[✓ verified on 2026-04-23 from local AI Nation docs]
- Grist doc: `Echo External Memory` (`8tr2cqDjxtKA9RzGSaVDS5`)
- table: `Table1`
- fields: `A=sender`, `B=recipient`, `C=message`

## Working rule
Before publishing initiative materials intended for city / assembly processing:
1. review the Telegram gateway thread;
2. inspect the expected route and latest operator instruction;
3. use the verified transport (currently AI Nation Grist Mailbox `Table1`, unless explicitly overridden);
4. report the exact destination used.

## Anti-pattern
Do not confuse AI Nation Grist Mailbox with Grist `Crr_feedback`, and do not treat the source Telegram topic as delivery.
