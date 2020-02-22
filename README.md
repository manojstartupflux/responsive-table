<!-- creating table style through css -->

<!DOCTYPE html>
<html>
<head>
<style>

	.divTable{
		border: 2px solid #000;
	}
.divTable{
	display: table;
	width: 100%;
}
.divTableRow {
	display: table-row;
}
.divTableHeading {
	background-color: #EEE;
	display: table-header-group;

}
.divTableCell, .divTableHead {
	border: 1px solid #999999;
	display: table-cell;
	text-align: center;
	padding: 3px 10px;
}
.divTableHeading {
	background-color: #EEE;
	display: table-header-group;
	font-weight: bold;
}
.divTableFoot {
	background-color: #EEE;
	display: table-footer-group;
	font-weight: bold;
}
.divTableBody {
	display: table-row-group;
}
</style>	
</head>
<body>


<!-- creating table through html -->

<div class="divTable">
<div class="divTableBody">
<div class="divTableRow">
<div class="divTableCell">Name</div>
<div class="divTableCell">Education</div>
<div class="divTableCell">Address</div>
<div class="divTableCell">Date of Birth</div>
<div class="divTableCell">State</div>
<div class="divTableCell">Zip Code</div>
<div class="divTableCell">Countty</div>
</div>
<div class="divTableRow">
<div class="divTableCell">Nanoj</div>
<div class="divTableCell">MCA</div>
<div class="divTableCell">Noida</div>
<div class="divTableCell">22-07-87</div>
<div class="divTableCell">UP</div>
<div class="divTableCell">201301</div>
<div class="divTableCell">India</div>
</div>
<div class="divTableRow">
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
</div>
<div class="divTableRow">
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
</div>
<div class="divTableRow">
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
<div class="divTableCell">&nbsp;</div>
</div>
</div>
</div>
</body>
</html>
