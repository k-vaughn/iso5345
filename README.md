<table style="border: 1px solid #333;">
  <tr>
    <th style="width: 10%;">Name</th>
	<th style="width: 30%;">Description</th>
	<th style="width: 10%;">Special Attributes</th>
	<th style="width: 10%;">Standards</th>
	<th style="width: 10%;">Syntax</th>
	<th style="width: 10%;">Policy</th>
  </tr>
  <tr>
  	<td>ITS-AID</td>
  	<td>ITS application identifier: The specification or architecture reference should indicate the general service that is provided.</td>
  	<td><ul><li>Ideally, the description should indicate an artefact from a recognized ITS reference architecture</li><li>p-encoding (required)</li><li>Specification (Required, Public access is conditional per policy)</li><li>Uses (Required)</li><li>URL (required for public specifications)</li></ul></td>
  	<td>
  		<ul>
  		<li>ETSI 103 097</li>
  		<li>ETSI 302 636-5-1</li>
  		<li>IEEE 1609.2</li>
  		<li>IEEE 1609.3</li>
  		<li>ISO 16460</li>
  		<li>EN ISO 17423 </li>
  		<li>CEN ISO 17429</li>
  		<li>ISO 21218</li>
  		<li>ISO 22418</li>
  		<li>ISO 24102-1</li>
  		<li>ISO 24102-2</li>
  		<li>ISO 29281-1</li>
  		</ul>
  	</td>
  	<td>INTEGER</td>
  	<td>Policies for ITS-AIDs</td>
  </tr>
  <tr>
    <td>ITS-ATT</td>
    <td>ITS access technology type: The specification must specify how it relates to ISO 21218.</td>
    <td>|Specification (Required, Public access is required)<br />URL (required)</td>
    <td>|ISO 16460<br />ISO 21218<br />ISO 22418<br />ISO 24102-1<br />ISO 24102-3<br />ISO 24102-4<br />ISO 24102-6</td>
    <td>INTEGER (0..255)</td>
    <td>National Body Policy</td>
  </tr>
</table>



|Name|Description|Special Attributes|Standards|Syntax|Policy|
|----|-----------|------------------|---------|------|------|
|ITS-AID|ITS application identifier: The specification or architecture reference should indicate the general service that is provided.|<ul><li>Ideally, the description should indicate an artefact from a recognized ITS reference architecture</li><li>p-encoding (required)</li><li>Specification (Required, Public access is conditional per policy)</li><li>Uses (Required)</li><li>URL (required for public specifications)</li></ul>|<ul><li>ETSI 103 097</li><li>ETSI 302 636-5-1</li><li>IEEE 1609.2</li><li>IEEE 1609.3</li><li>ISO 16460</li><li>EN ISO 17423 </li><li>CEN ISO 17429</li><li>ISO 21218</li><li>ISO 22418</li><li>ISO 24102-1</li><li>ISO 24102-2</li><li>ISO 29281-1</li></ul>|INTEGER|Policies for ITS-AIDs|
|ITS-ATT|ITS access technology type: The specification must specify how it relates to ISO 21218.|Specification (Required, Public access is required)<br />URL (required)|ISO 16460<br />ISO 21218<br />ISO 22418<br />ISO 24102-1<br />ISO 24102-3<br />ISO 24102-4<br />ISO 24102-6|INTEGER (0..255)|National Body Policy|
|ITS-FlowTypeID|
