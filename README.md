# Snapshot Ensemble with SGDR

This repo contains pytorch implementation of Snapshot Ensemble and Stochastic Gradient Descent with Warm Restarts on City Name Dataset.

Compared to the best single model and a simple voting ensemble of 5 best models, my snapshot ensemble model with 10 snapshots improved f1-score by 0.019(vs. single) and 0.14(vs. simple ensemble). 

!(snapshot ensemble model)[/images/snapshot_ensemble.png]
!(individual snapshot test f1-score)[/images/test_f1score.png]

## performance comparison

<table class="tg">
  <tr>
    <th class="tg-yw4l"></th>
    <th class="tg-yw4l">Test Accuracy</th>
    <th class="tg-yw4l">Test f1-score</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Best Single Model</td>
    <td class="tg-yw4l">0.581</td>
    <td class="tg-yw4l">0.566</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Simple Voting Ensemble</td>
    <td class="tg-yw4l">0.589</td>
    <td class="tg-yw4l">0.571</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Snapshot Esemble</td>
    <td class="tg-yw4l">0.596</td>
    <td class="tg-yw4l">0.585<br></td>
  </tr>
</table>

## blog post
<a href="http://jsideas.net/python/2018/03/14/snapshot_ensemble.html">Snapshot Ensemble with SGDR</a>

## Reference
1) <a href='https://arxiv.org/pdf/1704.00109.pdf'>SNAPSHOT ENSEMBLES: TRAIN 1, GET M FOR FREE</a>  
2) <a href='https://arxiv.org/pdf/1608.03983.pdf'>SGDR: Stochastic Gradient Descent with Warm Restarts</a>

