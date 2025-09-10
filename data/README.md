# ***__title__***

*Original data, code and results related to the study*

---

:bulb::brain: ***Each file and/or folder code corresponds to the script used to generate it, ensuring that all (dataset + script + output) share the same code***

:computer: :brain: :floppy_disk: ***Check [here](../scripts/README.md) to see how the data was processed***

:warning: ***GitHub has restrictions with storing large files, if you believe there are any missing files please contact the authors to obtain them***

---

:thinking::bulb: If you are interested in SFNI data, consider taking a look at that [GitHub repository](https://github.com/aitorvv/SFNI_Spanish_Forest_National_Inventory-ready_to_use/) where further updates to that dataset will be uploaded.

---

## :file_folder: Folder Content



- :open_file_folder: ***1_raw***: initial datasets

  - :sunny: WorldClim data required must be downloaded from its [official website](https://www.worldclim.org/data/index.html)
  - :deciduous_tree::evergreen_tree: Spanish Forest National Inventory (SFNI) data required must be downloaded from its [official website](https://www.miteco.gob.es/es/biodiversidad/temas/inventarios-nacionales/inventario-forestal-nacional.html) or accessed via this [GitHub repository](https://github.com/aitorvv/SFNI_Spanish_Forest_National_Inventory-ready_to_use/) 
     - :deciduous_tree: Acess to the [SFNI2](https://www.miteco.gob.es/es/biodiversidad/servicios/banco-datos-naturaleza/informacion-disponible/ifn2.html)
     - :deciduous_tree: Acess to the [SFNI3](https://www.miteco.gob.es/es/biodiversidad/servicios/banco-datos-naturaleza/informacion-disponible/ifn3.html)
     - :deciduous_tree: Acess to the [SFNI4](https://www.miteco.gob.es/es/biodiversidad/temas/inventarios-nacionales/inventario-forestal-nacional/cuarto_inventario.html)
  - :open_file_folder: ***IFNx*** folders contain the original SFNI datasets
  - :floppy_disk: ***SFNI4_species_codes.csv*** file contains the species names and codes for SFNI4



- :open_file_folder: ***2_processed***: analyzed datasets

  - :deciduous_tree::evergreen_tree: tree and plot data obtained from [iuFOR](https://iufor.uva.es) ([Quantitative silviculture group](https://github.com/iuFOR-QuantitativeForestry)) experimental plots
    - :warning: According to the original paper (*Due to the sensitive nature of the data, raw data would remain available only under serious requests.*), data must be requested from the authors


  - :open_file_folder: ***simanfor*** contains inputs and outputs for all the simulations developed with [SIMANFOR](www.simanfor.es). *Check out them! There are a lot of metrics unexplored in this paper* :wood: :maple_leaf:

    - :seedling: **1_raw** contains the tree and plot original datasets used to perform simulations

    - :seedling: :arrow_right: :deciduous_tree: **2_results** contains the simulation results grouped by the silvicultural scenario
    
  - :open_file_folder: :sunny: **climate**: climate data obtained from [WorldClim data](https://www.worldclim.org/data/index.html); data from the study area in available on this folder

  - :open_file_folder: :sunny: **climate**: data extracted from [AEMET](https://www.aemet.es/es/portada) for different meteorological stations

---

:computer: :brain: :floppy_disk: ***Check [here](../scripts/README.md) to see how the data was processed***