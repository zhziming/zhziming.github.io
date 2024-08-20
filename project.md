---
layout: page
permalink: /project/index.html
title: Projects
---

## Industrial Experiences

- <table>
    <tr>
        <td class="imger" vertical-align="middle"><img src="../images/rca.jpg" style="width:2500px; height:200px"/></td>
        <td><b>AIOps system focusing on root cause analysis:</b> <br> The framework includes anomaly detection and root cause analysis. The anomaly detection module is composed of Siamese Log Autoencoder and Subgraph detection module based on expert rules. The root cause analysis part is composed of graph neural networks and random walk algorithms.
        </td>
    </tr>
  </table>

- <table>
    <tr>
        <td class="imger" vertical-align="middle"><img src="../images/llm.jpg" style="width:3500px; height:200px"/></td>
        <td><b>Large Language Model for Development Efficiency:</b> The general large langauge model of Qwen-Alibaba is enhanced with a document knowledge base to handle specific downstream DevOps problems. Following the chain of thought framework with some practical tricks such as self-consistency, the model is able to switch to multiple context tasks with minimal amount of fine-tuning data requirements. 
        </td>
    </tr>
  </table>

<style type="text/css">
  imger {
    display: block;
  }

  .imger {
    border-radius: 20px;
    display: inline-block;
    overflow: hidden;
    position: relative;
  }

  .imger:before {
    border-radius: 20px;
    bottom: 0;
    box-shadow: inset 0 0 1px 1px #100;
    content: " ";
    left: 0;
    position: absolute;
    right: 0;
    top: 0;
    z-index: 1;
  }
</style>

<style type="text/css">
  td {
    padding: 0 15px;
  }
</style>
