# A 3D heat map for exploring patterns of co-relationships minerals with open data

The demo system http://tickmap.nkn.uidaho.edu/D3Cube is optimized to run in Chrome and Safari. In particular, to visualize the big 72^3 3D heat map, it is recommended to use Chrome. For other use cases with smaller datasets, Safari will be fine.  

By 02/23/203, there are eight datasets on the demo system:
1) A 30*30*30 3D matrix for mineral species numbers. The value in each cell represents the number of minerals species that contain the three element X, Y and Z.
2) A 30*30*30 3D matrix for mineral species fractions. The value in each cell represents the fraction of mineral species containing Z that also contain both X and Y.
3) A 72*72*72 3D matrix for mineral species. The value in each cell is the result of a chi-squared test to show the effect of the presence of element Z on the correlation between elements X and Y in mineral species?’

All datasets are derived from the Mindat.org database. 

The general workflow is as below:
1) Go to https://goo.gl/UNbdok. A user can load one of the three datasets by click a button. Once the dataset is loaded, the corresponding elements in the dataset will be highlighted in the periodic table.
2) The user can select elements to be listed along each axis in the output cube matrix, First click the input box for an axis then make selections by clicking nodes in the periodic table. The selected elements will show up in the input box of that axis. The option is same for the input box of all the three axes.
3) When the data selection is done, the user can download the selected dataset (csv format) or visualize it in a cube matrix by clicking the corresponding buttons. The visualization function will
    
open a new page. In the new page, the user can interact with the visualization result in various ways: rotate, zoom in, zoom out, or change the distance between cubes along each axis, do a logarithmic transformation to improve visualization pattern, etc.
4) For each loaded dataset, the user can also click the ‘Visualize All Elements’ button to visualize everything in the raw data, which however is not recommended because that will take a lot of computation power and may crash the memory of your computer, especially for the 72*72*72 dataset.
5) On the main user interface, the user can click Clear All to clear the current element selections and start a new session.
The demo system is still under development. You are welcome to contact Marshall Ma (max@uidaho.edu) for suggestions and comments.
This work was partially supported by the W. M. Keck Foundation through the grant “The Co- Evolution of the Geo- and Biospheres: An Integrated Program for Data-Driven Abductive Discovery in Earth Sciences”, the National Science Foundation (NSF) through the NSF Idaho EPSCoR Program (No. IIA-1301792), and the University of Idaho ORED Seed Grant. Additional support was provided by the Deep Carbon Observatory, the Alfred P. Sloan Foundations, an anonymous foundation, and the Carnegie Institution for Science.
  
