<template>
    <div class="d-flex flex-column justify-center align-center">
    <h1 class="align-self-start ml-5 pt-5">username</h1>
    <div class="vendortable">
    <v-data-table
    :headers="headers"
    :items="vendorDetails"
    item-key="dc_location"
    class="elevation-1"
  ></v-data-table>
  </div>
  </div>
</template>
<script>

export default {
    name:"vehicle",
    data:() =>({
        vendorDetails:[
            {
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R7562",
		"vehicle_payload_capacity": "1MT",
		"payload": 1000,
		"length": 1,
		"width": 1,
		"height": 1,
		"volume_cft": 1,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R6248",
		"vehicle_payload_capacity": "1MT",
		"payload": 1000,
		"length": 1,
		"width": 1,
		"height": 1,
		"volume_cft": 1,
		"usage_zone": "SM - SEMI UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN65F3238",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 5.6,
		"width": 5.4,
		"height": 5.8,
		"volume_cft": 175.392,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN20BE1117",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 5.8,
		"width": 5.7,
		"height": 5.9,
		"volume_cft": 195.05400000000003,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN20BA6922",
		"vehicle_payload_capacity": "2.5MT",
		"payload": 2500,
		"length": 6.4,
		"width": 5.1,
		"height": 6,
		"volume_cft": 195.84,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14M4795",
		"vehicle_payload_capacity": "2.5MT",
		"payload": 2500,
		"length": 6.2,
		"width": 5.7,
		"height": 5.8,
		"volume_cft": 204.97200000000001,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22DB3831",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.8,
		"width": 5.3,
		"height": 5.3,
		"volume_cft": 415.73199999999997,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN12P1047",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.5,
		"width": 5.6,
		"height": 5.4,
		"volume_cft": 438.47999999999996,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN18K4984",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.5,
		"width": 5.6,
		"height": 5.4,
		"volume_cft": 438.47999999999996,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN28AC8004",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.5,
		"width": 5.6,
		"height": 5.4,
		"volume_cft": 438.47999999999996,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22AE8004",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.5,
		"width": 5.6,
		"height": 5.4,
		"volume_cft": 438.47999999999996,
		"usage_zone": "SM - SEMI UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22BK5540",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.3,
		"width": 5.7,
		"height": 5.6,
		"volume_cft": 456.45600000000002,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22BE9124",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.6,
		"width": 5.6,
		"height": 5.7,
		"volume_cft": 466.03199999999998,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN032422",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.8,
		"width": 5.6,
		"height": 5.7,
		"volume_cft": 472.416,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN19C5463",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.8,
		"width": 5.6,
		"height": 5.7,
		"volume_cft": 472.416,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN09AK7898",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.2,
		"width": 5.7,
		"height": 5.5,
		"volume_cft": 476.52,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN11A8800",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15,
		"width": 5.7,
		"height": 5.6,
		"volume_cft": 478.79999999999995,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN07AJ6361",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.1,
		"width": 5.8,
		"height": 5.5,
		"volume_cft": 481.69,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN32V8704",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.7,
		"width": 5.7,
		"height": 5.8,
		"volume_cft": 485.98199999999991,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN04AU1107",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.1,
		"width": 5.8,
		"height": 5.6,
		"volume_cft": 490.44799999999998,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN49R4441",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 14.8,
		"width": 5.8,
		"height": 6.1,
		"volume_cft": 523.62400000000002,
		"usage_zone": "SM - SEMI UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN18D4042",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.2,
		"width": 5.7,
		"height": 6.3,
		"volume_cft": 545.83199999999999,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN29AE9484",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.1,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 561.87099999999998,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14F7024",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.2,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 565.59199999999987,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN12Q4768",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.2,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 565.59199999999987,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14W9226",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14W7797",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN02X8008",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14W7754",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14U3601",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14Q9529",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.1,
		"volume_cft": 573.03399999999999,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN22CC4389",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.2,
		"width": 6.02,
		"height": 6.3,
		"volume_cft": 576.47519999999997,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14M9667",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.1,
		"height": 6.2,
		"volume_cft": 582.428,
		"usage_zone": "SM-LOCAL",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN25AQ6665",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.4,
		"width": 6.3,
		"height": 6.1,
		"volume_cft": 591.82199999999989,
		"usage_zone": "SM- SEMI UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14U3650",
		"vehicle_payload_capacity": "5.5 MT",
		"payload": 5500,
		"length": 15.3,
		"width": 6.2,
		"height": 6.3,
		"volume_cft": 597.61800000000005,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN37CM2361",
		"vehicle_payload_capacity": "7.5MT",
		"payload": 7500,
		"length": 18.3,
		"width": 6.4,
		"height": 5.9,
		"volume_cft": 691.00800000000004,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R6216",
		"vehicle_payload_capacity": "7.5MT",
		"payload": 7500,
		"length": 18.5,
		"width": 6.4,
		"height": 5.9,
		"volume_cft": 698.56000000000006,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14R1836",
		"vehicle_payload_capacity": "7.5MT",
		"payload": 7500,
		"length": 18.3,
		"width": 6.5,
		"height": 5.9,
		"volume_cft": 701.80500000000006,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN14V9648",
		"vehicle_payload_capacity": "7.5MT",
		"payload": 7500,
		"length": 18.3,
		"width": 6.3,
		"height": 6.1,
		"volume_cft": 703.26900000000001,
		"usage_zone": "SM-UPC",
		"format": "SM"
	},{
		"dc_location": "Chennai - Poonamalee",
		"dry_f_v": "COMBI",
		"transporter_name": "RAJ TRANSPORT",
		"vehicle_no": "TN12AB6636",
		"vehicle_payload_capacity": "7.5MT",
		"payload": 7500,
		"length": 18.4,
		"width": 6.6,
		"height": 6.1,
		"volume_cft": 740.78399999999988,
		"usage_zone": "SM-UPC",
		"format": "SM"
	}
],
headers: [
        {
          text: 'dc_location',
          align: 'start',
          sortable: false,
          value: 'dc_location',
        },
        {
          text: 'dry_f_v',
          sortable: false,
          value: 'dry_f_v',
        },
         {
          text: 'transporter_name',
          sortable: false,
          value: 'transporter_name',
        },
        {
          text: 'vehicle_no',
          sortable: false,
          value: 'vehicle_no',
        },
        {
          text: 'vehicle_payload_capacity',
          sortable: false,
          value: 'vehicle_payload_capacity',
        },
        {
          text: 'payload',
          value: 'payload',
        },
        {
          text: 'length',
          
          value: 'length',
        },
        {
          text: 'width',
          
          value: 'width',
        },
        {
          text: 'height',
          value: 'height',
        },
        {
          text: 'volume_cft',
          value: 'volume_cft',
        },
        {
          text: 'usage_zone',
          sortable: false,
          value: 'usage_zone',
        },
        {
          text: 'format',
          sortable: false,
          value: 'format',
        }
      ],
    })
}
</script>
<style scoped>
.vendortable{
    margin:50px;
    width:"80%";
}
</style>
