<template>
<div class="d-flex flex-column justify-center align-center">
    <h1 class="align-self-start">username</h1>
    <div class="table">
  <v-data-table
    :headers="headers"
    :items="originDestination"
    item-key="supplying_dc_location"
    class="elevation-1"
  ></v-data-table>
  </div>
  </div>
</template>
<script>

export default {
    name:"origin",
    data: () => ({
      originDestination: [
        {
		"supplying_dc_location": "Chennai - Poonamalee",
		"delivery_type_dry_f_v_combi": "Combi",
		"format_sm_hm": "SM",
		"store_code": 1164,
		"store_name": "Annanagar West",
		"dry_loading_slot": 0.916666667,
		"f_v_loading_slot": 0.041666667,
		"dc_leaving_time": 0.25,
		"max_return_back_to_dc_time": 0.583333333,
		"does_the_vehicle_return_in_same_day": "Yes",
		"tag_local_upc": "Local",
		"city_zone": "CHENNAI",
		"store_latitude": 13,
		"store_longitude": 80.19605,
		"delivery_slot": "06:00 AM - 08:45 AM",
		"type_of_vehicle_used": "2.5MT",
		"highest_capacity_vehicle_which_can_be_used": "5.5MT",
		"remarks_1": "Parking restriction at Store",
		"remarks_2": "7.5 MT vehicle is not able to parking in store"
	},{
		"supplying_dc_location": "Chennai - Poonamalee",
		"delivery_type_dry_f_v_combi": "Combi",
		"format_sm_hm": "SM",
		"store_code": 3607,
		"store_name": "Orikkai Kancheepuram",
		"dry_loading_slot": 0.5,
		"f_v_loading_slot": 0.041666667,
		"dc_leaving_time": 0.25,
		"max_return_back_to_dc_time": 0.583333333,
		"does_the_vehicle_return_in_same_day": "Yes",
		"tag_local_upc": "SEMI UPC",
		"city_zone": "KANCHEEPURAM",
		"store_latitude": 13,
		"store_longitude": 79.7068418,
		"delivery_slot": "06:00 AM - 08:45 AM",
		"type_of_vehicle_used": "5.5MT",
		"highest_capacity_vehicle_which_can_be_used": "7.5MT"
	},{
		"supplying_dc_location": "Chennai - Poonamalee",
		"delivery_type_dry_f_v_combi": "Combi",
		"format_sm_hm": "SM",
		"store_code": 3561,
		"store_name": "Thiruvanamalai 3",
		"dry_loading_slot": 0.916666667,
		"f_v_loading_slot": 0.041666667,
		"dc_leaving_time": 0.041666667,
		"max_return_back_to_dc_time": 0.041666667,
		"does_the_vehicle_return_in_same_day": "No",
		"tag_local_upc": "UPC",
		"city_zone": "THIRUVANNAMALAI",
		"store_latitude": 12,
		"store_longitude": 79.07806,
		"delivery_slot": "06:00 AM - 08:45 AM",
		"type_of_vehicle_used": "5.5MT",
		"highest_capacity_vehicle_which_can_be_used": "7.5MT"
	}
      ],
      headers: [
        {
          text: 'supplying_dc_location',
          align: 'start',
          sortable: false,
          value: 'supplying_dc_location',
        },
        {
          text: 'delivery_type_dry_f_v_combi',
          sortable: false,
          value: 'delivery_type_dry_f_v_combi',
        },
         {
          text: 'format_sm_hm',
          sortable: false,
          value: 'format_sm_hm',
        },
        {
          text: 'store_code',
          sortable: false,
          value: 'store_code',
        },
        {
          text: 'store_name',
          sortable: false,
          value: 'store_name',
        },
        {
          text: 'dry_loading_slot',
          value: 'dry_loading_slot',
        },
        {
          text: 'f_v_loading_slot',
          
          value: 'f_v_loading_slot',
        },
        {
          text: 'dc_leaving_time',
          
          value: 'dc_leaving_time',
        },
        {
          text: 'max_return_back_to_dc_time',
          value: 'max_return_back_to_dc_time',
        },
        {
          text: 'does_the_vehicle_return_in_same_day',
          sortable: false,
          value: 'does_the_vehicle_return_in_same_day',
        },
        {
          text: 'tag_local_upc',
          sortable: false,
          value: 'tag_local_upc',
        },
        {
          text: 'city_zone',
          sortable: false,
          value: 'city_zone',
        },
        {
          text: 'store_latitude',
          value: 'store_latitude',
        },
        {
          text: 'store_longitude',
          value: 'store_longitude',
        },
        {
          text: 'delivery_slot',
          sortable: false,
          value: 'delivery_slot',
        },
        {
          text: 'type_of_vehicle_used',
          sortable: false,
          value: 'type_of_vehicle_used',
        },
        {
          text: 'highest_capacity_vehicle_which_can_be_used',
          sortable: false,
          value: 'highest_capacity_vehicle_which_can_be_used',
        },
        {
          text: 'remarks_1',
          sortable: false,
          value: 'remarks_1',
        },
        {
          text: 'remarks_2',
          sortable: false,
          value: 'remarks_2',
        }
      ],
    }),
}
</script>

<style scoped>
.table{
    margin-top:70px;
    width:90%;
}
</style>