---
title: "STAR-CCM+ Example"
---
---

An example of non-adiabatic combustion


<center>

</center>


---

[Import Job Setup](https://platform.rescale.com/tutorials/starccm-combustion-example/clone/)

[Get Job Results](https://platform.rescale.com/tutorials/starccm-combustion-example/share/)

---
<center>
<table class="table">
	<tr>
		<td>Simulation Code</td>
		<td>CD-adapco STAR-CCM+ v11.04.012</td>
	</tr>
	<tr>
		<td>Analysis Type</td>
		<td>Combustion</td>
	</tr>
	<tr>
		<td>Description</td>
		<td>Non-Adiabatic Combustion with Star-CCM+ on Rescale.</td>
	</tr>
	<tr>
		<td>Suggested Hardware</td>
		<td>Onyx / 2 cores</td>
	</tr>
	<tr style="command-row">
		<td>Command</td>
		<td><pre>starccm+ -power -rsh ssh -np 2 -machinefile $HOME/machinefile -batch nonAdiabaticPpdfEquilib.java</pre></td>
	</tr>
	<tr>
		<td>Estimated Run Time</td>
		<td>6 minutes</td>
	</tr>
</table>
</center>

