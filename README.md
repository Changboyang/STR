# Spatio-temporal-tendency-reasoning-for-human-body-pose-and-shape-estimation-from-videos

## Related Experiments:
1. Our method is tested on the crowded dataset 3DPW-Crowd. **MPJPE: 89.9(ours)vs.97.3(tcmr); PA-MPJPE: 60.8(ours)vs.62.3(tcmr); MPVPE: 113.5(ours)vs.125.1(tcmr)**.

2. We compared the parameter size and training time with TCMR. **Parameters: 108.89M vs. 127.19M; training time: about 1.5h vs. 1.8h**.

## Integration strategy:
3. In the integration strategy, we also did experiments using only the self-integration phase or only the cross-integration with 
**PA-MPJPE of 62.7(self) vs. 62.3(cross) vs. 61.6(ours)**.

4. We investigate experiments on alternative ensemble strategies for common feature aggregation. **PA-MPJPE: 62.6 (plain aggregate) vs. 61.6 (ours)**.

## STE:
5. We investigate experiments where SENet replaces STE. **PA-MPJPE: 62.5 (SENet) vs. 61.6 (STE)**.


## TTR:
6. We did a comparative experiment of related GRU and TTR. Experimental results **PA-MPJPE: 62.7(GRU) vs. 61.6(TTR), Accel: 9.0(GRU) vs. 8.4(TTR)**.

7. we conducted ablation experiments inside the TTR. We divide the input of TTR into 1, 2, 4, and 8 sub-fragments. **PA-MPJPE: 62.7 (Undivided) vs. 62.0 (2 fragments) vs.  61.6 (TTR:4 fragments) vs. 62.6 (8 fragments)**.
