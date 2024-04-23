Lab Screenshots
Run "picorv32a" design synthesis
> ![SS1](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/806fdcc3-9c1d-4974-a69f-dc69bc2c143a)
> ![SS2](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/8ab7f2da-d471-418a-a352-b3d3fe58a8d6)

$$Flop ratio = Number of D flip flops \over Total Number of cells$$

$$Flop ratio = 1613 \over 14876 = 0.10843$$

$$Percentage of DFF's = Flop ratio*100$$

$$Percentage of DFF's = 10.843$$

> ![SS3](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/125fbc5f-11da-41ec-a339-3a4e2bb60c71)
> ![SS4](https://github.com/Thamirawaran/VSD_SoC_Design/assets/107134124/7a6a1109-c0e5-4fa1-a03e-b13ce6f1dbfd)
> [!NOTE]
># Change directory to openlane flow directory
>cd Desktop/work/tools/openlane_working_dir/openlane

># alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'
>docker #invoke docker

># invoke the openlane flow in the Interactive mode
>./flow.tcl -interactive

># input the required packages for proper functionality of the openlane flow
>package require openlane 0.9

># prepare the design creating some necessary files and directories for running a specific design "picorv32a"
>prep -design picorv32a

># run synthesis
>run_synthesis

># Exit from openlane flow
>exit

# Exit from OpenLANE flow docker sub-system
exit
