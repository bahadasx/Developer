---
layout: post
title: BLS Numbers
created: 1359483400
description: This Dataset contains historic data (last 10 years) for the most common economic indicators.
---

```
http://api.dol.gov/V1/statistics/BLS_Numbers
```

<p>This Dataset contains historic data (last 10 years) for the most common economic indicators. More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://bls.gov&amp;exitTitle=BLS&amp;fedpage=yes">http://bls.gov</a></p>

<a href ="http://api.dol.gov/V1/statistics/BLS_Numbers/$metadata" class="button radius button_dataset">Browse Metadata</a>
<a href ="https://devtools.dol.gov/APISampler/Home/Index1?datasetName=BLS%20Numbers" class="button radius button_dataset">Explore This Data</a>

## Dataset Tables  
- [averageHourlyEarnings](#averageHourlyEarnings)
- [consumerPriceIndex](#consumerPriceIndex)
- [employmentCostIndex](#employmentCostIndex)
- [exportPriceIndex](#exportPriceIndex)
- [importPriceIndex](#importPriceIndex)
- [payrollEmployment](#payrollEmployment)
- [producerPriceIndex](#producerPriceIndex)
- [productivity](#productivity)
- [unemploymentRate](#unemploymentRate)
- [averageHourlyEarnings12MonthChange](#averageHourlyEarnings12MonthChange)
- [averageHourlyEarnings1MonthChange](#averageHourlyEarnings1MonthChange)
- [averageHourlyEarnings1MonthNetChange](#averageHourlyEarnings1MonthNetChange)
- [consumerPriceIndex12MonthChange](#consumerPriceIndex12MonthChange)
- [consumerPriceIndex1MonthChange](#consumerPriceIndex1MonthChange)
- [exportPriceIndex12MonthChange](#exportPriceIndex12MonthChange)
- [exportPriceIndex1MonthChange](#exportPriceIndex1MonthChange)
- [importPriceIndex12MonthChange](#importPriceIndex12MonthChange)
- [importPriceIndex1MonthChange](#importPriceIndex1MonthChange)
- [payrollEmployment12MonthChange](#payrollEmployment12MonthChange)
- [payrollEmployment12MonthNetChange](#payrollEmployment12MonthNetChange)
- [payrollEmployment1MonthChange](#payrollEmployment1MonthChange)
- [payrollEmployment1MonthNetChange](#payrollEmployment1MonthNetChange)
- [producerPriceIndex12MonthChange](#producerPriceIndex12MonthChange)
- [producerPriceIndex1MonthChange](#producerPriceIndex1MonthChange)
- [unemploymentRate12MonthChange](#unemploymentRate12MonthChange)
- [unemploymentRate1MonthChange](#unemploymentRate1MonthChange)

<h3 id="averageHourlyEarnings">averageHourlyEarnings Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth</a></p>
<table summary="Average Hourly Earnings - BLS Numbers">
	<caption>Average Hourly Earnings</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="consumerPriceIndex">consumerPriceIndex Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth</a></p>
<table summary="Consumer Price Index - BLS Numbers">
	<caption>Consumer Price Index</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="employmentCostIndex">employmentCostIndex Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CIS1010000000000Q&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CIS1010000000000Q</a></p>
<table summary="Employment Cost Index - BLS Numbers">
	<caption>Employment Cost Index</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Quarters - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="exportPriceIndex">exportPriceIndex Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth</a></p>
<table summary="Export Price Index - BLS Numbers">
	<caption>Export Price Index</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="importPriceIndex">importPriceIndex Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth</a></p>
<table summary="Import Price Index - BLS Numbers">
	<caption>Import Price Index</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="payrollEmployment">payrollEmployment Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth</a></p>
<table summary="Payroll Employment - BLS Numbers">
	<caption>Payroll Employment</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,0)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="producerPriceIndex">producerPriceIndex Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth</a></p>
<table summary="Producer Price Index - BLS Numbers">
	<caption>Producer Price Index</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="productivity">productivity Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/PRS85006092&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/PRS85006092</a></p>
<table summary="Productivity - BLS Numbers">
	<caption>Productivity</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - (A)Annual and (Q)Quarters - Primary Key</td>
			<td>varchar(5)</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="unemploymentRate">unemploymentRate Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/LNS14000000&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/LNS14000000</a></p>
<table summary="Unemployment Rate - BLS Numbers">
	<caption>Unemployment Rate</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="averageHourlyEarnings12MonthChange">averageHourlyEarnings12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth</a></p>
<table summary="Average Hourly Earnings 12 Month Change - BLS Numbers">
	<caption>Average Hourly Earnings 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="averageHourlyEarnings1MonthChange">averageHourlyEarnings1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth</a></p>
<table summary="Average Hourly Earnings One Month Change - BLS Numbers">
	<caption>Average Hourly Earnings One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="averageHourlyEarnings1MonthNetChange">averageHourlyEarnings1MonthNetChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0500000003?output_view=net_1mth</a></p>
<table summary="Average Hourly Earnings One Month Net Change - BLS Numbers">
	<caption>Average Hourly Earnings One Month Net Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="consumerPriceIndex12MonthChange">consumerPriceIndex12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth</a></p>
<table summary="Consumer Price Index 12 Month Change - BLS Numbers">
	<caption>Consumer Price Index 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="consumerPriceIndex1MonthChange">consumerPriceIndex1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CUSR0000SA0?output_view=pct_1mth</a></p>
<table summary="Consumer Price Index One Month Change - BLS Numbers">
	<caption>Consumer Price Index One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="exportPriceIndex12MonthChange">exportPriceIndex12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth</a></p>
<table summary="Export Price Index 12 Month Change - BLS Numbers">
	<caption>Export Price Index 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="exportPriceIndex1MonthChange">exportPriceIndex1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIQ?output_view=pct_1mth</a></p>
<table summary="Export Price Index One Month Change - BLS Numbers">
	<caption>Export Price Index One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="importPriceIndex12MonthChange">importPriceIndex12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth</a></p>
<table summary="Import Price Index 12 Month Change - BLS Numbers">
	<caption>Import Price Index 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="importPriceIndex1MonthChange">importPriceIndex1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/EIUIR?output_view=pct_1mth</a></p>
<table summary="Import Price Index One Month Change - BLS Numbers">
	<caption>Import Price Index One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="payrollEmployment12MonthChange">payrollEmployment12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth</a></p>
<table summary="Payroll Employment 12 Month Change - BLS Numbers">
	<caption>Payroll Employment 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="payrollEmployment12MonthNetChange">payrollEmployment12MonthNetChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth</a></p>
<table summary="Payroll Employment 12 Month Net Change - BLS Numbers">
	<caption>Payroll Employment 12 Month Net Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="payrollEmployment1MonthChange">payrollEmployment1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth</a></p>
<table summary="Payroll Employment One Month Change - BLS Numbers">
	<caption>Payroll Employment One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="payrollEmployment1MonthNetChange">payrollEmployment1MonthNetChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/CES0000000001?output_view=net_1mth</a></p>
<table summary="Payroll Employment One Month Net Change - BLS Numbers">
	<caption>Payroll Employment One Month Net Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value (in thousands)</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="producerPriceIndex12MonthChange">producerPriceIndex12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth</a></p>
<table summary="Producer Price Index 12 Month Change - BLS Numbers">
	<caption>Producer Price Index 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="producerPriceIndex1MonthChange">producerPriceIndex1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/WPSSOP3000?output_view=pct_1mth</a></p>
<table summary="Producer Price Index One Month Change - BLS Numbers">
	<caption>Producer Price Index One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="unemploymentRate12MonthChange">unemploymentRate12MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/LNS14000000&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/LNS14000000</a></p>
<table summary="Unemployment Rate 12 Month Change - BLS Numbers">
	<caption>Unemployment Rate 12 Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>

<h3 id="unemploymentRate1MonthChange">unemploymentRate1MonthChange Table</h3>
<p>More information and details about the data provided can be found at <a href="http://www.dol.gov/cgi-bin/leave-dol.asp?exiturl=http://data.bls.gov/timeseries/LNS14000000&amp;exitTitle=BLS&amp;fedpage=yes">http://data.bls.gov/timeseries/LNS14000000</a></p>
<table summary="Unemployment Rate One Month Change - BLS Numbers">
	<caption>Unemployment Rate One Month Change</caption>
	<thead>
		<tr>
			<th scope="col">Column Name</th>
			<th scope="col">Column Description</th>
			<th scope="col">Data Type</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">year</th>
			<td>Year - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">period</th>
			<td>Period - Months - Primary Key</td>
			<td>int</td>
		</tr>
		<tr>
			<th scope="row">value</th>
			<td>Value</td>
			<td>numeric(8,3)</td>
		</tr>
		<tr>
			<th scope="row">type</th>
			<td>Type - Preliminary(p), Revised(r), Final(F)</td>
			<td>char(1)</td>
		</tr>
	</tbody>
</table>
