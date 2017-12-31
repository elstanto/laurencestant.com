---
title: Tools/Converters
date: 2017-11-06 17:29:57
---
<script src="/scripts/index.js">
</script>
This page contains various javascipt unit converters for radio engineering.
#### RF Power
<form>
<div class="form-row">
    <div class="col">
        <input class="form-control" type="number" id="dbm_val" onchange="power_convert(this.id, this.value)" />
        dBm
    </div>
    <div class="col">
        <input class="form-control" type="number" id="watt_val" onchange="power_convert(this.id, this.value)" />
        W
    </div>
    <div class="col">
        <input class="form-control"  type="number" id="rtw_val" onchange="power_convert(this.id, this.value)" />
        sqrt(W)
    </div>
</div>
</form>
