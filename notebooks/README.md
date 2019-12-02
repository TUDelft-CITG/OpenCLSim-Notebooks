## Example notebooks

The benefit of OpenCLSim is the generic set-up. This set-up allows the creation of complex logistical flows. You can run the following examples locally or as an [Azure notebook](https://notebooks.azure.com/joris-denuijl/projects/OpenCLSim).

1. **Basic Hopper Operation** - Example of a trailing suction hopper dredge shipping sediment from origin to destination site.
2. **Energy Use** - Example of estimating fuel use on a project by keeping track of energy useage for each step of the production cycle.
3. **Tracking Dredging Spill** - Example of a project where sediment spill limits influence project progress.
4. **Building a Layered Dike** - Example of a construction challenge, with four separate activites, where each activity depends on the progress of the other activities.
5. **Dredging Vessel Operation on route** - Example of a trailing suction hopper dredge shipping sediment from origin to destination site while following a graph path.
6. **Container Transfer Hub** - Example of a container transfer hub, where very large container vessels deliver containers, while smaller vessels take care of the distribution to the hinterland. Traffic follows a graph path.
7. **Temporary site** - Example of a project site that is used as temporary storage. It is filled and emptied after a short while, the simulation should continue until the final project rule is satisfied.
8. **Vessel on dynamic route** - Example of a vessel using dynamic routing from the [HALEM](https://pypi.org/project/halem/) python package.

### Coupling the notebooks to BI visualisation tools

The output is visualized in the notebooks, but the output is also saved to external csv files. These csv files can be loaded into other visualisation tools, including free Desktop Business Intelligence tools Qlik Sense Desktopand PowerBI Desktop. The column names of the csv files have been designed to allow simple recreation of the OpenCSLIm datamodel by just loading the data. Both Qlik Sense and PowerBI use the actual column names to create connections between the tables. The tables also mimic the tables in planning tools like PrimaVera and MS projecs, to allow for easy comparison.

#### Qlik Sense
[Qlik Sense](https://www.qlik.com/us/try-or-buy/download-qlik-sense) can be downloaded for free. You need to make an account. For loading the data in Qlik Sense, copy the *.qvs* load script into the data load editor. We recommend to add this [Qlik extention](https://github.com/SimoneSilini/Reboot-Timeline) to vizualize planning, using these steps to install custom components:
* Open a Windows Explorer window and navigate to ..\Users\<UserName>\Documents\Qlik\Sense\Extensions.
* Create a new folder and give it a suitable name.
* Copy the files that you downloaded to the new folder. Unzip the contents from github.
* There should be at least one JavaScript file and one QEXT file, but there can be more files.

#### PowerBI
[Microsoft PowerBI](https://powerbi.microsoft.com/en-us/desktop/) can be downloaded for free. We recommend to add the extention visual [as Timeline ](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381377).
