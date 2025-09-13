# Tokenization — pitch+duration

- Grid: 1/16 (PPQ=480 ⇒ step=120)
- Tokens: P36..P84, durations D{1..8} (in 1/16 steps), plus REST
- Control tokens: `<MODE=…><METER=…><LEN=…><BOS>/<EOS>`
- Ornaments < 1/32 merged; dynamics ignored/binned
- Splits by *piece* (80/10/10). Transpositions only in *train*
