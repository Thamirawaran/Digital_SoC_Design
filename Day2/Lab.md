Lab Screenshots
Run floorplan
> ![SS4](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/7a6a1109-c0e5-4fa1-a03e-b13ce6f1dbfd)

> ![SS5](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/5043508c-2612-4378-bc13-8cc0940edf4c)

> ![SS7](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/38105c70-ee4d-4cc3-92af-faca2d1c2cb2)

> ![SS8](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/6a6a0e84-0b2d-4e5e-bafc-c6f6cf3ddb8a)

> ![SS9](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/45ad5776-a4bb-42e7-afd1-330a9349a348)

Floorplan def in magic
> ![SS10](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/94c81ea1-3af1-4ba3-84d3-01e043943efa)

> ![SS11](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/acc981f7-4573-4af0-a1f7-97de028b099d)

> ![SS12](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/25070e5b-8db5-47ea-bb07-cb4403e185ff)

> ![SS13](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/0327ef1f-1b7f-46cb-95a0-2660b33c9631)

> ![SS14](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/4304e0c7-593a-434b-81f3-dd719dc866e2)

Placement def in magic
> ![SS15](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/4d7d7c45-cf4a-4cf6-aa2e-29dd215603c6)

> ![SS16](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/48fab395-79da-45ff-8aee-943759fd4034)

>[!NOTE]
># Now we can run floorplan
>%run_floorplan
># Change directory to generated floorplan inorder to open floorplan.def file
cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/17-03_12-06/results/floorplan/

># Load the floorplan def in magic tool
magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def &
># Congestion aware placement by default
>run_placement
># Change directory to placement inorder to open placement.def file
>cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/17-03_12-06/results/placement/

># Command to load the placement def in magic tool
>magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &
