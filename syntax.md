## The syntax

The following syntax is used to formulate bridge data.

- Cards in a suit are marked with their number (2 to 8), T=10, (J)ack, (Q)ueen, (K)ing, (A)ce, always uppercase.
- Never put spaces or seperator when describing a set of cards in a suit. Good: `AK832`. Bad: `A K 8 3 2` or `A,K,8,3,2`.
- Use the backtick \` to visually distinguish the set of cards.
- The (x) means «exactly one unspecified card». Ex: `AKxxx` means Ace followed by King followed by exactly three other cards.
- The star (\*) means, zero or more cards. Ex `AK*` means Ace followed by King followed by any number of cards.
- bolds leads. Ex: `K[J]Txx`
- Name the files in lowcase. Fill spaces with dashes and extension of file should be .md .
- Format of all.md file: 3 status (*OK*, *To confirm* and *To discuss*), after modifying the file, the modifier should change the status of partner to *To confirm*, if partner agrees, change the status from *To confirm* to *OK*, otherwise change the status from *To confirm* to *To discuss*
