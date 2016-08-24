---
title: "LS-DYNA 3 Car Example"
---
---

A 3 car collision simulation.

![Car2Car](https://prod-rescale-resources.s3.amazonaws.com/en/software-examples/ls-dyna/3-vehicle.png)

---

TO UPDATE: (On tutorials@rescale.com acct - LS-DYNA 3 Car Example)

[Import Job Setup](https://platform.rescale.com/tutorials/ls-dyna-3-car/clone/)

[Get Job Results](https://platform.rescale.com/tutorials/ls-dyna-3-car/share/)

---
<center>
<table class="table">
	<tr>
		<td>Simulation Code</td>
		<td>LS-DYNA R9.0.0</td>
	</tr>
	<tr>
		<td>Analysis Type</td>
		<td>FEA</td>
	</tr>
	<tr>
		<td>Description</td>
		<td>This is a 3 car collision simulation, where a compact car is hit from the rear by a van and collides into a midsize car. This is a modified version of the simulation which was shortened to have an end time of 0.020s. NCAC is responsible for the vehicle models and this simulation was put together by Mike Berger, consultant to LSTC.</td>
	</tr>
	<tr>
		<td>Suggested Hardware</td>
		<td>Onyx / 8 cores</td>
	</tr>
	<tr style="command-row">
		<td>Command</td>
		<td><pre>ls-dyna -i 3cars_shell2_20ms.k -p single</pre></td>
	</tr>
	<tr>
		<td>Estimated Run Time</td>
		<td>22 minutes</td>
	</tr>
</table>
</center>

