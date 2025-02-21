# serin
Keyboard layout based on Canary

##### column-staggered
```
w l y p v z f o u , \
m r s t g b n a e i /
q j c d k x h ' ; .
```
##### row-staggered
```
w l y p v z f o u , [ ] \
 m r s t g b n a e i /
  q j c d k x h ' ; .
```
## changes
This layout attempts to be a more balanced version of [Canary](https://github.com/Apsu/Canary), with only four letter changes.

I wanted to accomplish the following:
- Retain the core "feel" of Colemak-DH, including the `T`/`N` homing keys
- Retain Canary's solution for the `Y` key in Colemak-DH and, by proxy, the uncomfortable `YOU` trigram
- Improve on Canary's LSBs without sacrificing too much in other metrics
- Improve on Canary's left/right usage ratio
  - Serin arrives at a 44.65:55.35 ratio, compared to Canary's 43.67:56.33 ratio
- Improve on Canary's workload imbalance across the fingers, and reduce disproportionate burden on index fingers
  - Serin greatly reduces the relative spike found in the 4th and 8th columns, allowing for a more even finger distribution
- Improve on Canary's redirects

## comparisons
### canary
Serin generally improves on Canary, with similar SBFs, scissors, and rolls, but greatly reduced LSBs and redirects.

|Metric | Canary | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SBFs | 0.66% | 0.77% | +0.11% |
| LSBs | 1.75% | 1.07% | -0.68% |
| Scissors | 0.42% | 0.53% | +0.11% |
| Rolls | 50.37% | 49.26% | -1.11% |
| Redirects | 6.95% | 5.31% | -1.64%|
| SPES[^1] | 1.738 | 1.729 | -0.009 |

### colemak-dh
Serin greatly improves on Colemak-DH, particularly in LSBs, redirects, and the `YOU` trigram.

|Metric | Colemak-DH | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SBFs | 0.91% | 0.77% | -0.14% |
| LSBs | 1.27% | 1.07% | -0.20% |
| Scissors | 0.15% | 0.53% | +0.38% |
| Rolls | 49.21% | 49.26% | +0.05% |
| Redirects | 9.22% | 5.31% | -3.91%|
| SPES[^1] | 1.726 | 1.729 | +0.003 |

## mods
- The `K`/`V` keys can be swapped for slighty better skip bigram stats and easier access to the `V` shortcut
  - However, this is in exchange for words with the `PK` bigram becoming harder

## stats
![Screenshot 2025-02-20 at 11 09 23 PM](https://github.com/user-attachments/assets/8aa8fc1e-de0f-448a-b792-85b087b06210)

![Screenshot 2025-02-20 at 11 09 53 PM](https://github.com/user-attachments/assets/87c3af71-2432-4fd1-afa1-6a42adfd88b0)

![Screenshot 2025-02-20 at 11 10 36 PM](https://github.com/user-attachments/assets/f2a2d4c6-bcaa-4256-90cf-b3d57987dcb6)

![Screenshot 2025-02-20 at 10 54 40 PM](https://github.com/user-attachments/assets/94675965-a2ba-4001-a240-876e59099271)


[^1]: SteveP's [Layout Analysis Tool](https://colemakmods.github.io/mod-dh/analyze.html) Effort Score
