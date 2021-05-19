<template>
    <div>
        <div class="d-flex flex-column justify-center align-center">
    <h1 class="align-self-start">username</h1>
    <div class="table">
  <v-data-table
    :headers="headers"
    :items="contractDetails"
    item-key="transporter_name"
    class="elevation-1"
  ></v-data-table>
  </div>
  </div>
    </div>
</template>

<script>
export default {
    name:"contract",
    data:()=>({
        contractDetails:[
            {
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R7562",
		"contract_type": "per trip"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN14R6248",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN65F3238",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN20BE1117",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN20BA6922",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN14M4795",
		"contract_type": "per trip"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN22DB3831",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN12P1047",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN18K4984",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN28AC8004",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN22AE8004",
		"contract_type": "per trip"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN22BK5540",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22BE9124",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN032422",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN19C5463",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN09AK7898",
		"contract_type": "per trip"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN11A8800",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN07AJ6361",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN32V8704",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN04AU1107",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN49R4441",
		"contract_type": "per trip"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN18D4042",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN29AE9484",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN14F7024",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN12Q4768",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN14W9226",
		"contract_type": "per trip"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN14W7797",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN02X8008",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14W7754",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN14U3601",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN14Q9529",
		"contract_type": "per trip"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN22CC4389",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14M9667",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN25AQ6665",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN14U3650",
		"contract_type": "market vehicle"
	},{
		"transporter_name": "PQR TRANSPORT",
		"vehicle_no": "TN37CM2361",
		"contract_type": "per trip"
	},{
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R6216",
		"contract_type": "per kilometre"
	},{
		"transporter_name": "ABC TRANSPORT",
		"vehicle_no": "TN14R1836",
		"contract_type": "fixed + variable"
	},{
		"transporter_name": "XYZ TRANSPORT",
		"vehicle_no": "TN14V9648",
		"contract_type": "fixed + variable with minimum kilometre guarantee"
	}
],
headers: [
        {
          text: 'transporter_name',
          align: 'start',
          sortable: false,
          value: 'transporter_name',
        },
        {
          text: 'vehicle_no',
          sortable: false,
          value: 'vehicle_no',
        },
         {
          text: 'contract_type',
          sortable: false,
          value: 'contract_type',
        }
        ]
    })
}
</script>
