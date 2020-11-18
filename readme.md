# ISO 5345: ITS Identifier Code Lists - PROTOTYPE SITE
This site is designed as a prototype of a future site that will publish the Identifier Code Lists recognized by International Organization for Standardization (ISO) Technical Committee (TC) 204, _Intelligent transport systems_ (ITS). The contents of the current site are intended to demonstrate how this site will work. **Values shown on this site are likely to contain a mixture of real and imaginary assignments and these values should not be considered normative in any way.**

## Background

Within information exchanges, there is often a need to unambiguously and concisely represent information. One way to achieve this is to define an identifier that can be used to map between a concise expression (e.g., an integer value) to a complex meaning (e.g., the reference to a country, a standard, a protocol). The identifier might be an integer, a hierarchical structure (e.g., an ASN.1 OBJECT IDENTIFIER), or any other concise representation of a more complex concept (e.g., a two-character country code). 

The mappings of concise expressions to precise meanings is provided with the use of a code list. A code list is presented as a table with columns representing different attributes of each identifier and each row representing the assignment of a precise meaning to a specific identifier (i.e., concise expression). 

Separate code lists allow the same code (e.g., an integer value of '1') to be assigned different meanings in different contexts. ISO/TC 204 has identified the need for multiple code lists; it is the resposibility of each standard to identify the particualr code list to be used in any context that relies upon identifiers.

Some code lists are relatively static and are only updated when the text of the standard is updated. However, within ITS, there are several code lists that need to be updated in a more timely manner. ISO/TC 204 developed ISO 5345 to define the process for maintaining code lists that need to be updated more frequently. This website provides [a prototype of what the official code lists might look like for] the official code lists that are maintained per ISO 5345.

## List maintenance

ISO has established a maintenance agency (MA) relevant to ISO 5345, which consists of members the ISO/TC 204. XXXXXX is the appointed Maintenance Agency Secretariat (MAS). XXXXXX has assigned “the accomplishment of the secretariat of the Maintenance Agency” and the undertaking of related tasks to YYYYYY. Among other things, YYYYYY (a __supra-national__ not-for-profit organization) is responsible for all communications with the public, including accepting applications for identifier assignments. More information on Maintenance Agencies for ISO standards can be found [here](https://www.iso.org/maintenance_agencies.html#5345).

Interested parties who wish to request an identifier assignment in any of the code lists provided on this site are invited to email to zzzzzz@yyyyyy.org.

## Identifier types

### [ITS-AID](its-aid.md)

ITS application identifier (ITS-AID)

An ITS-AID provides a globally unique identifier for an ITS application specification. The list of ITS-AID values is provided [here](its-aid.md). 

<table style="width: 1000px">
  <tr>
    <th>Identifier Type</th>
	<th>Special Attributes</th>
	<th>Standards</th>
	<th>Syntax</th>
	<th>Policy</th>
  </tr>
  <tr>
  	<td>ITS-AID</td>
  	<td>
  		<table>
  			<tr><td>Architecture reference (O)</td></tr>
  			<tr><td>p-encoding (M)</td></tr>
  			<tr><td>Specification (M, 1)</td></tr>
  			<tr><td>Uses (M)</td></tr>
  			<tr><td>URL &#40;C, 3)</td></tr>
  		</table>
  	</td>
  	<td>
  		<table>
  		<tr><td>ETSI 103 097</td></tr>
  		<tr><td>ETSI 302 636-5-1</td></tr>
  		<tr><td>IEEE 1609.2</td></tr>
  		<tr><td>IEEE 1609.3</td></tr>
  		<tr><td>ISO 16460</td></tr>
  		<tr><td>EN ISO 17423 </td></tr>
  		<tr><td>CEN ISO 17429</td></tr>
  		<tr><td>ISO 21218</td></tr>
  		<tr><td>ISO 22418</td></tr>
  		<tr><td>ISO 24102-1</td></tr>
  		<tr><td>ISO 24102-2</td></tr>
  		<tr><td>ISO 29281-1</td></tr>
  		</table>
  	</td>
  	<td>INTEGER</td>
  	<td>Policies for ITS-AIDs</td>
  </tr>
</table>

### ITS-ATT

blah, blah, blah 

## Specifications for identifier types

The following table identifies details about each identifier type. The precise meaning of each column is defined in ISO 5345. Requests for new identifiers must provide values for all Special Attributes that are marked mandatory (M) or conditional \(C), when the stated conditions apply.

<table style="width: 1000px">
  <tr>
    <th>Identifier Type</th>
	<th>Special Attributes</th>
	<th>Standards</th>
	<th>Syntax</th>
	<th>Policy</th>
  </tr>
  <tr>
    <td>ITS-ATT</td>
    <td>
		<table>
			<tr><td>Specification (M, 2)</td></tr>
			<tr><td>URL (M)</td></tr>
		</table>
	</td>
    <td>
		<table>
		<tr><td>ISO 16460</td></tr>
		<tr><td>ISO 21218</td></tr>
		<tr><td>ISO 22418</td></tr>
		<tr><td>ISO 24102-1</td></tr>
		<tr><td>ISO 24102-3</td></tr>
		<tr><td>ISO 24102-4</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
    <td>INTEGER (0..255)</td>
    <td>National Body Policy</td>
  </tr>
</table>

1 - Public access is conditional per Policy attribute

2 - Public access is required

3 - Required for public specifications



