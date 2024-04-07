# SnakesTimerResFix
S(ﮎ)nakesTimerResFix allows the user to modify the TimerResolution in Windows 10 22h2+.


The **driver only works in test mode** due to the lack of EV certificate signing:
<div class="highlight highlight-source-shell">
  <pre><code><span class="pl-s1"><span class="pl-c1">bcdedit</span> <span class="pl-s"><span class="pl-pds">/</span>set<span class="pl-pds"> </span>testsigning<span class="pl-pds"> </span>on</span></span></code></pre>
  <button class="btn btn-sm BtnGroup-item" data-clipboard-text="bcdedit /set testsigning on"></button>
</div>
