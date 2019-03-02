# godot-TileMapZ
Modified standard TileMap that allows for individual z_index assignment.
This module is intended for godot 3.1.

It decreases tile id pool from 2^24 to 2^21.
It allows assigning z_lvl in range of int8_t.

To use this module call additional function:
  void set_cell_z(int pos_x, int pos_y, int z_index)
  int get_cell_z(int pos_x, int pos_y)
  
