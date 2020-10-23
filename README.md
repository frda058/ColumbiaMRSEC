# ColumbiaMRSEC
Creating an input generator for Fritz-Haber Institute ab-initio molecular simulations (FHI-aims) in Avogadro2

This produces: 
* geometry.in
* control.in
     - with options for light and tight molecules


Instructions:
1. Download the fhi_aims.py file and save it to the appropriate folder on Avogadro.
On a Mac, go to Applications and right-click on Show Package Contents.
Avogadro2 -> "Show Package Contents" -> lib -> "avogadro2" -> scripts -> inputGenerators

2. Open Avogadro2 and create your molecule. On the header, click on Quantum -> Input Generators. You should see FHI-aims.

3. You can input the following parameters: charge, relativistic, relax geometry, spin, and xc.

4. Add the molecule name by typing it next to "Molecule".

5. Before adding the atoms for the control.in file, check either: light or tight

6. Add the atoms present in your molecule by clicking on the drop-down for Atom (1-8).

7. Save the input files by clicking "Write Files to Disk".
