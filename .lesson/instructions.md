# Instructions  

This exercise is entirely optional!! Now that we've learned a little about segwit, we can convert our legacy TXs and addresses to the new styles. The only differences here are formatting of witness data and some segwit specific opcodes, it's pretty quick using the bitcoin-cli. Post your bitcoin-cli logs and script data in the logs.txt file so Kody can help you, post the TXIDs for the successful testnet TXs in the submission.txt file.

  ## Steps
  1. Complete HW 1, you'll need a P2SH script that you know how to spend to and from
  2. Convert it to a P2WSH (you can do this with the bitcoin-cli by running decodescript, or do it manually for fun :) ).
  3. Lock some coins to the P2WSH address

EXTRA CREDIT!!!

  4. Convert your P2WSH to a P2SH-P2WSH (you can use the cli to convert from the P2SH or the P2WSH, they should convert to the same P2SH-P2WSH address).
  5. Spend the coins OUT of  the P2WSH address, TO the P2SH-P2WSH address.
  6. Spend the coins OUT of the P2SH-P2WSH back to yourself.
