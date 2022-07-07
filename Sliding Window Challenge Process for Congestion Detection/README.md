# [Sliding Window Challenge Process for Congestion Detection](https://arxiv.org/abs/2201.09009)

Authors: Ayelet Lotem, Sarah Azouvi, Patrick McCorry, Aviv Zohar

|**Jargon**|**Definitions**|**Source**| 
|:------:|---------------------------|:-----:|
| Challenge-Response | An implementation of a pattern in which some party must respond to a challenge within a fixed time limit | This paper |
| Challenge window| Time period between $T_c$ and $T_{rd}$, where a challenge that takes effect at time $T_c$ and a response deadline $T_{rd}$ which is the latest time by which response to the challenge will be accepted| This paper |
| Congestion | A phenomenon where there’s a spike in the number of transactions waiting in the mempool, and this paper uses the price of entering a transaction to the blockchain as a reliable signal for congestion. Congestion is often changing and is usually correlated when considering several consecutive blocks | This paper |
| Robustness |  A term captures the security of the protocol against either attack | This paper |
| Congestion Robust | Given an adversary with a relative computational power $\alpha$, his probability of winning a congestion attack, i.e., of successfully manipulating a period of $n$ blocks into a congested period is less than $q$ | This paper |
| Uncongestion Robust | Given an adversary with a relative computational power $\alpha$, his probability of winning an uncongestion attack, i.e., of successfully manipulating a period of $n$ blocks into an uncongested period is less than $q$ | This paper |
| Efficiency of Protocols | Concise proof size and Concise refresh information | This paper |

