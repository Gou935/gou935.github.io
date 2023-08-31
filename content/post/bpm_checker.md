---
title: "Bpm_checker"
date: 2023-08-24T22:58:43+08:00
draft: false
---

<script defer src="https://pyscript.net/alpha/pyscript.js"></script>
<link rel="stylesheet" href="https://raw.githubusercontent.com/Cat-Computing-Universe/PyLab/main/demo/demo.css" />
<script src="https://code.jquery.com/jquery-3.5.0.js"></script>
<py-env>
  - numpy
  - matplotlib
</py-env>
<b>pyscript REPL（已安裝numpy和matplotlib）</b>
<br>
<div>
  <div>
    <py-repl id="my-repl" auto-generate="true" std-out="output" std-err="output">
import numpy as np
from matplotlib import pyplot as plt
print("Hello, world!")
    </py-repl>
  </div>
  <div style="justify-content: right;display: flex;align-items: right;">
    <button class="button_reset" type="button">清除輸出</button>
  </div>
  <b>輸出：</b>
  <div style="justify-content: center;display: flex;align-items: center;">
    <div id="output" style="width: 100%;margin: 2rem;"></div>
  </div>
  <script src="https://raw.githubusercontent.com/Cat-Computing-Universe/PyLab/main/demo/demo.js"></script>
</div>
