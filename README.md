## Storebot

Usage:
 * `/store <key> <value>` - stores `value` under `key` for the user who runs the command
 * `/retrieve <user> <key>` - prints the stored value by `user` for `key`
 * `/usage` - print usages statistics

### Notes

 * This is not designed to store more than a few megabytes or so. Idk what discords max slash command data size is anyways so in practice this may be dificult to do anyways.
 * There is no way to delete value, but you can overwrite things obviously.
 * Storage is global, not on a per server basis.