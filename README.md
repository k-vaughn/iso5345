# ISO 5345: ITS Identifier Code Lists - PROTOTYPE SITE
This site is designed as a prototype of a future site that will publish the Identifier Code Lists recognized by International Organization for Standardization (ISO) Technical Committee (TC) 204, _Intelligent transport systems_ (ITS). The contents of the current site are intended to demonstrate how this site will work. **Values shown on this site are likely to contain a mixture of real and imaginary assignments and these values should not be considered normative in any way.**

[Index](index.html)

## ISO 5345 'Intelligent tranport systems – Identifiers'

Within information exchanges, there is often a need to unambiguously and concisely represent information. One way to achieve this is to define an identifier that can be used to map between a concise expression (e.g., an integer value) to a complex meaning (e.g., the reference to a country, a standard, a protocol). The identifier might be an integer, a hierarchical structure (e.g., an ASN.1 OBJECT IDENTIFIER), or any other concise representation of a more complex concept (e.g., a two-character country code). 

The mappings of concise expressions to precise meanings is provided with the use of a code list. A code list is presented as a table with columns representing different attributes of each identifier and each row representing the assignment of a precise meaning to a specific identifier (i.e., concise expression). 

Separate code lists allow the same code (e.g., an integer value of '1') to be assigned different meanings in different contexts. ISO/TC 204 has identified the need for multiple code lists; it is the resposibility of each standard to identify the particualr code list to be used in any context that relies upon identifiers.

Some code lists are relatively static and are only updated when the text of the standard is updated. However, within ITS, there are several code lists that need to be updated in a more timely manner. ISO/TC 204 developed ISO 5345 to define the process for maintaining code lists that need to be updated more frequently. This website provides [a prototype of what the official code lists might look like for] the official code lists that are maintained per ISO 5345.

## Maintenance agency

ISO has established a maintenance agency (MA) relevant to ISO 5345, which consists of members the ISO/TC 204. XXXXXX is the appointed Maintenance Agency Secretariat (MAS). XXXXXX has assigned “the accomplishment of the secretariat of the Maintenance Agency” and the undertaking of related tasks to YYYYYY. Among other things, YYYYYY (a __supra-national__ not-for-profit organization) is responsible for all communications with the public, including accepting applications for identifier assignments. More information on Maintenance Agencies for ISO standards can be found [here](https://www.iso.org/maintenance_agencies.html#5345).

Interested parties who wish to request an identifier assignment in any of the code lists provided on this site are invited to email to zzzzzz@yyyyyy.org.

## Use of langauge
All fields contained within the code lists are provided in English.

## Code Lists

<table style="width: 1000px">
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
|[ITS-AID](its-aid.md)|ITS application identifier: The specification or architecture reference should indicate the general service that is provided.|<ul><li>Ideally, the description should indicate an artefact from a recognized ITS reference architecture</li><li>p-encoding (required)</li><li>Specification (Required, Public access is conditional per policy)</li><li>Uses (Required)</li><li>URL (required for public specifications)</li></ul>|<ul><li>ETSI 103 097</li><li>ETSI 302 636-5-1</li><li>IEEE 1609.2</li><li>IEEE 1609.3</li><li>ISO 16460</li><li>EN ISO 17423 </li><li>CEN ISO 17429</li><li>ISO 21218</li><li>ISO 22418</li><li>ISO 24102-1</li><li>ISO 24102-2</li><li>ISO 29281-1</li></ul>|INTEGER|Policies for ITS-AIDs|
|ITS-ATT|ITS access technology type: The specification must specify how it relates to ISO 21218.|Specification (Required, Public access is required)<br />URL (required)|ISO 16460<br />ISO 21218<br />ISO 22418<br />ISO 24102-1<br />ISO 24102-3<br />ISO 24102-4<br />ISO 24102-6|INTEGER (0..255)|National Body Policy|
|ITS-FlowTypeID|




