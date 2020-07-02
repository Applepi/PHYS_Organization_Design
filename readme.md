This is a repository of Neogi Lab Equipment and the status of the work on them

For these instruments I plan on trying to implement them using [pyMeasure](https://github.com/ralph-group/pymeasure) this should allow an object oriented approach to these instruments that will allow for a more streamlined coding experience. Documentation can be found [here](https://pymeasure.readthedocs.io/en/latest/).

Other Libraries that should be investigated for ease of implementation:

[HoloViz](https://github.com/holoviz/holoviz); [netCDF](https://unidata.github.io/netcdf4-python/netCDF4/index.html)/[xarray](http://xarray.pydata.org/en/stable/)/[Dask](https://github.com/dask/dask)

I'm not sure what the priority of integrating this implementation is? I think getting the instruments working with a python interface is likely the priority and any graphing features should be handled as needed.

--Planning--

Data Acquisition: [pyMeasure](https://github.com/ralph-group/pymeasure)

User interface: [Panel](https://github.com/holoviz/panel)

--Style Guides--

These should be use for projects moving forward.

https://www.python.org/dev/peps/pep-0008/

https://www.python.org/dev/peps/pep-0257/

Good overview of classes

https://python-textbok.readthedocs.io/en/1.0/Classes.html

|   Manufacturer:	|   Model (Click for current working repo):	|   Communications Protocol (Click for manual):	|   Status:	|  Priority (According to Trace): 	|
|---	|---	|---	|---	|---	|
|   Spectra-Physics	|   Mai-Tai	|   [RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/315A%20Rev.%20A%20Mai%20Tai%20WB%20User's%20Manual.pdf)	|   Not started	|   *	|
|   Spectra-Physics	|   Opal	|   [?](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/234A%20Rev.%20E%20Opal%20User's%20Manual.pdf)	|   Not started	|   *	|
|   Horiba	|   Triax 320	|   [GPIB/RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/TRIAX_Getting_Started_Manual.pdf)	|   Not started	|   ****	|
|   Horiba	|   CCD2000 |   [GPIB/RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/SpectrumOneCCD2000.pdf)	|   Not started	|   ****	|
|   Thorlabs	|   K10CR1	|   [USB](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/K10CR1_M-ManualforKinesis.pdf)	|   Not started	|   *	|
|   Thorlabs	|   KPZ101	|   [USB](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/KPZ101-KPZ101ManualforKinesis.pdf)	|   Not started	|   *	|
|   Thorlabs	|   KSG101	|   [USB](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/KSG101-KSG101ManualforKinesis.pdf)	|   Not started	|   *	|
|   Thorlabs	|   SC-10	|   [RS232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/SC10-Manual.pdf)	|   Not started	|   *****	|
|   NI	|   BNC-2121	|   [PCI](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/NI_BNC-2121.pdf)	|   Not started	|   *** |	
|   NI	|   DAQBoard	|   [USB](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/NIDAQ.pdf)	|  Not started 	|   **	|
|   Arduino	|   [UNO + GRBL Board](https://github.com/Applepi/pymeasure/tree/dev/grbl)	|   [USB to RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/2.70_arduino_grbl_instructions_2.pdf)	|   Not started	|   *	|
|   Newport	|   ESP300	|   [GPIB/RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/ESP300-User-Manual.pdf)	|   Not started	|   ****	|
|   Newport	|   1830-C	|   [RS-232](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/1830-C%20Manual.pdf)	|   Not started	|   *	|
|   Stellarnet	|   BLUE-WAVE (Needs Specifics)	|   [USB](https://github.com/Applepi/PHYS_Organization_Design/blob/master/manuals/StellarNet-BLUE-Wave-SPEC.pdf)	|   Not started	|   *****	|
