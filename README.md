# serin
Keyboard layout based on Colemak-DH

##### column-staggered
```
v l y p j z f o u ; \
m r s t g b n a e i '
q w c d k x h , . /
```
##### row-staggered
```
v l y p j z f o u ; [ ] \
 m r s t g b n a e i '
  q w c d k x h , . /
```
## changes
This layout attempts to be a more balanced version of [Colemak-DH](https://colemakmods.github.io/mod-dh/) and [Canary](https://github.com/Apsu/Canary).

I wanted to accomplish the following:
- Retain the core "feel" of Colemak-DH, including the `T`/`N` homing keys and punctuation key placement
- Retain Canary's solution for the `Y` key in Colemak-DH and, by proxy, the uncomfortable `YOU` trigram
- Improve on Canary's LSBs without sacrificing too much in other metrics
- Improve on Canary's left/right usage ratio
  - Serin arrives at a 44.65:55.35 ratio, compared to Canary's 43.67:56.33 ratio
- Improve on Canary's workload imbalance across the fingers, and reduce disproportionate burden on index fingers
  - Serin greatly reduces the relative spike found in the 4th and 8th columns, allowing for a more even finger distribution
- Improve on Canary's (and thus Colemak-DH's) redirects
- Improve on Canary's shortcut, CLI, and Vim friendliness
  - Serin has easier `W` access for tab and window management
  - Serin has easier `cd`, `rm`, and `wc` access for CLI usage
  - Serin has easier `:wq`, `c[i]w`, and `d[i]w` access for Vim usage

## comparisons
All comparisons are done with normalized puntuation keys across each layout.
### colemak-dh
Serin generally performs better than Colemak-DH, particularly in LSBs, redirects, and the `YOU` trigram.

|Metric | Colemak-DH | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SBFs | 0.91% | 0.92% | +0.01% |
| LSBs | 1.27% | 0.83% | -0.44% |
| Scissors | 0.15% | 0.53% | +0.38% |
| Rolls | 49.21% | 48.96% | -0.25% |
| Redirects | 9.22% | 5.48% | -3.74%|
| SPES[^1] | 1.726 | 1.723 | -0.003 |

### canary
Serin is somewhat better than Canary, with similar or slightly worse SBFs, scissors, and rolls, but greatly reduced LSBs and redirects.

|Metric | Colemak-DH | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SBFs | 0.75% | 0.92% | +0.17% |
| LSBs | 1.77% | 0.83% | -0.94% |
| Scissors | 0.41% | 0.53% | +0.12% |
| Rolls | 50.16% | 48.96% | -1.2% |
| Redirects | 6.96% | 5.48% | -1.48%|
| SPES[^1] | 1.736 | 1.723 | -0.013 |

## mods
- The `J`/`Z` keys can be swapped with nearly zero impact to stats, if the `Z` shortcut is prefered on the left-hand side
- The `K`/`V` keys can be swapped for slighty worse SBFs but significantly better LSBs and easier access to the `V` shortcut
- The `E`/`A` keys can be swapped to optimize for SteveP's [Layout Analysis Tool](https://colemakmods.github.io/mod-dh/analyze.html), yielding a SPES[^1] of 1.717
  - However, this results in a less balanced workload across the fingers, and performs worse on other analyzers

## stats
![Screenshot 2025-02-18 at 2 38 02 PM](https://github.com/user-attachments/assets/178798e7-8cec-479b-9d28-e4671a50e3be)

![Screenshot 2025-02-18 at 2 39 19 PM](https://github.com/user-attachments/assets/c537f8c1-55fe-45e7-bd69-2f40db6b6806)

![Screenshot 2025-02-18 at 2 38 51 PM](https://github.com/user-attachments/assets/a6ca94f8-11a7-4955-98b0-e622f0fadd0b)

![Screenshot 2025-02-18 at 2 53 20 PM](https://github.com/user-attachments/assets/2e937aaf-c1f2-4634-bfae-9298e6fbc133)

[^1]: SteveP's [Layout Analysis Tool](https://colemakmods.github.io/mod-dh/analyze.html) Effort Score
