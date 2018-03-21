'pw' is a simple wrapper for 'lpass', the LastPass command-line interface. It simplifies the lookup of credentials as follows:

1. Instead of 'lpass show -G google', you can just type 'pw google'.
2. If there's more than one matching account, 'pw' presents a simple menu to choose the right one. If there's just one, it selects the one automatically.
3. Then it dumps non-sensitive data to the console, including URL and username.
4. Finally, it copies the appropriate password to the clipboard, which is both more convenient and more secure than dumping it to the console for shoulder surfers to see.

Dependencies:
 * fish
 * lpass
 * egrep
