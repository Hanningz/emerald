---
title: Gateway System
---
description: Example Gateway Application Object describing base system

LWM2M MODEL

Object Version: urn:oma:lwm2m:ext:1022:1

SHA1 Checksum: 917d11c244a7271a054a68b1cf1d47c618ca562f

Resource Fields: 

Example Usage: Outline how to interact with this object, if needed.

XML

JSON: 

code:

UCI model

OpenWRT gateway native data model for the whole gateway

URL: file://localhost/etc/config/system

config



<table>
    <thead>
	<tr>
	    <th>Resource</th>
	    <th>ID</th>
		<th>Access Type</th>
		<th>Multiple Instances</th>
		<th>Mandatory</th>
		<th>Type</th>
		<th>Range/Enumeration</th>
		<th>Units</th>
		<th>Description</th>
	</tr>
	</thead>
<tbody>
	<tr>
        <td>Hostname</td>
        <td>0</td>
        <td>R,W</td>
        <td>No</td>
        <td>Optional</td>
        <td>String</td>
        <td></td>
        <td></td>
        <td>Hostname of the System</td>
	</tr>
	<tr>
		<td>Timezone</td>
		<td>1</td>
		<td>R,W</td>
		<td>No</td>
		<td>Optional</td>
		<td>String</td>
		<td></td>
		<td></td>
		<td>The timezone used in the system</td>
	</tr>
	<tr>
		<td>DNS Server List</td>
		<td>2</td>
		<td>R,W</td>
		<td>No</td>
		<td>Optional</td>
		<td>String</td>
		<td></td>
		<td></td>
		<td>List of DNS Servers used by this system</td>
	</tr>
	<tr>
		<td>NTP Server List</td>
		<td>3</td>
		<td>R,W</td>
		<td>No</td>
		<td>Optional</td>
		<td>String</td>
	    <td></td>
		<td></td>
		<td>List of NTP Servers used by this system</td>
	</tr>
</tbody>
</table>

