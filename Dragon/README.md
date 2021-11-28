# Dragon hotends
The Dragon hotend (TriangleLabs and Phaetus version are nearly identical and fit both) has a strong reputation of being a reasonably priced high qualtiy hotend. Personally i prefer the high flow version as it hasn't shown any of the disadvantages sometimes attributed to a high flow hotend but does have the advantage of being capable of melting al lot of plastic.

# Part fan shrouds
The part fan shroud in this directory fits all extruder versions, high flow as well as standard flow.

2021-11-28 update: 
5015 and 5020 versions of the fan shroud are now available
The "ears" have been opened up as it was found not needed to close as much as earlier versions did. This further improves cooling efficiency.
A secondary channel pushing some air directly downwards below the fan shroud has been added as this region was getting less cooling thus fixing the reduced overhang capability in that region.

![CR-6 5020 part fan shroud](https://user-images.githubusercontent.com/13643644/143776517-cbcf099e-0687-4bb6-a013-04b0f3e28d35.png)

![CR-6 5020 part fan shroud 2](https://user-images.githubusercontent.com/13643644/143776523-497f014b-fd28-4006-ba1f-3c018487c84e.png)

![CR-6 5020 part fan shroud 3](https://user-images.githubusercontent.com/13643644/143776528-6933e415-0acf-47af-9bb0-e5d9749d4664.png)

![CR-6 part fan shroud simulation](https://user-images.githubusercontent.com/13643644/143776937-34ad5a81-86d1-4438-b0e7-ed1afa60f710.png)

On the 2 section analysis the internal flow redirector is visible. A blower fan typically gives a higher output flow towards the circumference versus the inside The devider helps correcting that. The second devider lets some air flow to just below the shroud as this area gets too short cooling time when the hoten dmoves to the left.

The simulation picture shows the effect ot the ears in avoiding a "shadow" directly to the left ot the nozzle. Basically they make the airflow converge again.

I ran the Teaching tech 4-way overhang test to validate my design: https://www.thingiverse.com/thing:3167063

![20211128_173728](https://user-images.githubusercontent.com/13643644/143777775-7f4714e1-eafe-4297-be54-ab6fa59418cc.jpg)
![20211128_173451](https://user-images.githubusercontent.com/13643644/143777779-1cc8d4be-a9ae-40d5-b931-04c762d52269.jpg)
![20211128_173757](https://user-images.githubusercontent.com/13643644/143777800-92ae731e-ab8d-4e25-90d5-e8158084ae26.jpg)

This test produces overhangs up to 80°. Up to 60° the overhangs are perfect, 70° is perfectly useable and even 80° would be usefull if no other way is found and some sagging is accepted (PLA @200 °C, 0.4 mm nozzle, 0.2 mm layer height, 0.45 mm line width, 25 mm/s exterior walls). I tested slower print speeds but that produces lesser results. Using the 5015 the results are less good when printing faster. The 5020 manages up to 50 mm/s with no/barely loss in overhang quality. Beyond 50 mm/s outer layer speed a 10° lesser overhang maximum should be used.

### Print settings:
- layer_height = 0.2
  layer_height_0 = 0.24
  line_width = 0.45
  infill_line_width = 0.4

  bottom_layers = 3
  top_layers = 3
  wall_line_count = 3

  material_bed_temperature = 85
  material_print_temperature = 230

  infill_pattern = gyroid
  infill_sparse_density = 20

  cool_fan_speed = 40
  cool_fan_speed_max = 75
  cool_min_layer_time = 10
  cool_min_layer_time_fan_speed_max = 20
  cool_min_speed = 10

  z_seam_corner = z_seam_corner_weighted
  z_seam_type = back
  z_seam_x = 235
