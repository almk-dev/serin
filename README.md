# serin
Keyboard layout based on Canary

##### column-staggered
```
w l y p k q f o u , \
m r s t g b n a e i /
z j c d v x h ' ; .
```
##### row-staggered
```
w l y p k q f o u , [ ] \
 m r s t g b n a e i /
  z j c d v x h ' ; .
```
## changes
This layout attempts to be a more balanced improvement on [Canary](https://github.com/Apsu/Canary).

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
Serin generally improves on Canary, with similar SFBs, scissors, and rolls, but greatly reduced LSBs and redirects.

|Metric | Canary | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SFBs | 0.66% | 0.71% | +0.05% |
| LSBs | 1.75% | 0.80% | -0.95% |
| Scissors | 0.42% | 0.53% | +0.11% |
| Rolls | 50.37% | 49.23% | -1.14% |
| Redirects | 6.95% | 5.44% | -1.51%|
| SPES[^1] | 1.738 | 1.731 | -0.007 |

### colemak-dh
Serin greatly improves on Colemak-DH, particularly in LSBs, redirects, and the `YOU` trigram.

|Metric | Colemak-DH | Serin | Difference |
| ----- | ---------: | ----: | ---------: |
| SFBs | 0.91% | 0.71% | -0.20% |
| LSBs | 1.27% | 0.80% | -0.470% |
| Scissors | 0.15% | 0.53% | +0.38% |
| Rolls | 49.21% | 49.23% | +0.02% |
| Redirects | 9.22% | 5.44% | -3.78%|
| SPES[^1] | 1.726 | 1.731 | +0.005 |

## stats
![Screenshot 2025-02-22 at 2 27 10 PM](https://github.com/user-attachments/assets/a0d1748f-f58f-4602-9aa9-9703d31c7f4f)

![Screenshot 2025-02-22 at 2 28 00 PM](https://github.com/user-attachments/assets/e8af5906-9289-45bf-9115-a1d83ec75dcb)

![Screenshot 2025-02-22 at 2 26 34 PM](https://github.com/user-attachments/assets/a24a5e33-1f19-413f-b8fe-c5b7c62e1336)

![Screenshot 2025-02-22 at 2 28 40 PM](https://github.com/user-attachments/assets/82c71889-abf9-428d-b4a4-465815e6ef4f)

[^1]: SteveP's [Layout Analysis Tool](https://colemakmods.github.io/mod-dh/analyze.html) Effort Score
