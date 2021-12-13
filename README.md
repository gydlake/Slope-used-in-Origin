# Slope-used-in-Origin
Purpose   : Show the slope and delta_x and delta_y between two selected points in a graph. Used in Origin software.

How to use: In Origin software, click View:Toolbars... to open the Customize dialog box.
	    Click Button Groups, click New button in Button Group to open the Create Button Group dialog box.
	    Group Name: p2slope (or other name you like), Number of Buttons: 1, Bitmap:p2slope.bmp (or your own icon).
			      Click OK to return to Customize dialog box. The group name will be shown in the Groups list box.
			      Click p2slope in the list box, an icon is shown in Buttons. 
			      Click the button icon and then click Settings... in Button to open the Button Settings dialog box. 
			      Click Browse... in File Name to select p2slope.ogs. Section Name: Main. Keep empty in Argument List.
			      Write something in "Tool Tip Text:" and "Status Bar Text:" as you like. 
			      Click OK to return to Customize dialog box. Drag the button in Buttons to insert it to the toolbar.
			      Click Close to close the Customize dialog box.
			      When one graph is active, clicking the button in the toolbar, a Script Window: LabTalk window will appear.
			      Double-clicking one point then another point in the graph (the points can be in the curve or not), 
            the slope and delta_x and delta_x will show in Script Window.
			      To continue with other 2-points, you need click the button again first, then double-click the points.
            
References: https://www.originlab.com/doc/Quick-Help/Two-Points-Slope

It is very helpful to my research work when analysising data in Origin. Hope it is useful to other researchers.
