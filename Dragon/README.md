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
