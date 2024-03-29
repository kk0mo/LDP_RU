The results presented in this repo compare our specific algorithms with the algorithm proposed in [Tao et al (2022)](https://proceedings.mlr.press/v151/tao22a.html), namely `LDPRSE`, which is proposed for the setting of LDP + heavy-tailed rewards in online MABs.

Hence, our comparisons were made in the online MAB setting under weak corruption. The findings are organized into two columns, demonstrating the impact of varying alpha (corruption) values on performance as epsilon (privacy) increases.
These results highlight the advantages of our algorithms over `LDPRSE` in the situations where there exist additional corruptions.

- **Left Column (Alpha = 2%)**: As epsilon increases (i.e., weaker privacy protection), _we observe that the performance not only aligns with our theoretical results (e.g., the gap between LTC and CTL becomes smaller) but also consistently surpasses `LDPRSE`. This showcases the effectiveness of our approach under low corruption settings.
- **Right Column (Alpha = 7%)**: For this larger corruption setting, our algorithms continue to outperform `LDPRSE`, under different choices of $\epsilon$.

<table>
  <tr>
    <td><img src="pics/a2e1.png" alt="Alt text 1" width="100%"></td>
    <td><img src="pics/a7e1.png" alt="Alt text 2" width="100%"></td>
  </tr>
  <tr>
    <td><img src="pics/a2e3.png" alt="Alt text 4" width="100%"></td>
    <td><img src="pics/a7e3.png" alt="Alt text 5" width="100%"></td>
  </tr>
  <tr>
    <td><img src="pics/a2e7.png" alt="Alt text 3" width="100%"></td>
    <td><img src="pics/a7e7.png" alt="Alt text 6" width="100%"></td>
  </tr>
</table>

