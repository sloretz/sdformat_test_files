# SDFormat Test files

**MOVED: https://github.com/ros/sdformat_urdf this repo is out of date with that one.**

This package contains a list of SDFormat files for testing tools that work with SDFormat models and worlds.

## Models

### Geometry

* `geometry_box`
  * Single link using `<box>` geometry
* `geometry_cylinder`
  * Single link using `<cylinder>` geometry
* `geometry_mesh_collada`
  * Single link using `<mesh>` geometry with a COLLADA mesh
* `geometry_mesh_obj`
  * Single link using `<mesh>` geometry with an OBJ mesh
* `geometry_mesh_scaled`
  * Single link using `<mesh>` geometry with an STL mesh scaled differently in each dimension
* `geometry_mesh_stl`
  * Single link using `<mesh>` geometry with an STL mesh
* `geometry_plane`
  * Single link using `<plane>` geometry
* `geometry_sphere`
  * Single link using `<sphere>` geometry
* `geometry_heightmap`
  * Single link using `<heightmap>` geometry

### Materials

* `material_ogre_script` TODO
  * Single link using an ogre script file to color it
* `material_shader` TODO
  * Single link using vertex and pixel shaders to color it
* `material_blinn_phong`
  * Single link using ambient/diffuse/specular/emissive components to color it
* `material_pbr` TODO
  * Single link using physics based rendering to color it
* `material_dynamic_lights`
  * Two visuals: one with dynamic lighting enabled and the other disabled

### Joints

* `joint_continuous`
  * Two links with a continuous joint between them.
* `joint_revolute`
  * Two links with a revolute joint between them.
* `joint_gearbox` TODO
  *
* `joint_revolute2`
  *
* `joint_prismatic`
  *
* `joint_ball`
  *
* `joint_screw`
  *
* `joint_universal`
  *
* `joint_fixed`
  *

### Links

* `link_kinematic` TODO
  *
* `link_self_collide` TODO
  *
* `link_gravity` TODO
  *

### Kinematic structures

* `graph_loop`
  * Three links joined by revolute joints to form a stiff triangle
* `graph_four_bar`
  * four links joined a loop to form a four bar linkage
* `graph_tree`
  * A tree of links with the canonical link as the root
* `graph_tree_non_canonical_root`
  * A tree of links were the canonical link is not the root
* `graph_chain`
  * A chain of links with the canonical link as the root
* `graph_chain_non_canonical_root`
  * A chain of links were the canonical link is not the root

### Poses and Frames

* `pose_chain`
  * A model with 4 links and 3 joints in a chain all having poses with translation and rotation.
* `pose_model`
  * A model with an offset pose
* `pose_link`
  * A link with an offset pose
* `pose_link_all`
  * A link with an offset pose that has a collision, inertial and visual with offset poses as well.
* `pose_link_in_frame`
  * A link with an offset pose specified in a frame on the model
* `pose_visual`
  * A visual with an offset pose
* `pose_visual_in_frame`
  * A visual with an offset pose specified in a frame on the model
* `pose_collision`
  * A collision with an offset pose
* `pose_collision_in_frame`
  * A collision with an offset pose specified in a frame on the model
* `pose_inertial`
  * An inertial with an offset pose
* `pose_inertial_in_frame`
  * An inertial with an offset pose specified in a frame on the model
* `pose_joint`
  * A joint with an offset pose
* `pose_joint_in_frame`
  * A joint with an offset pose specified in a frame on the model

TODO Learn enough about frames to know what examples to make for them
