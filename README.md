Problem Statement

		▪ Given a set of care-areas within a die
		▪ Generate placement of Main Field & Sub-Fields layouts
		▪ Such that:
		    ▪ stage movement is minimized
		    ▪ no area is scanned a second time
		    ▪ scanning un-necessary area is minimized

Main Field Layout Optimization Rules

	  ▪ Main Field size is fixed (given as input)
	  ▪ Use minimal number of Main Fields 
	  ▪ Main Fields can overlap with each other

Sub-Field Layout Optimization Rules

	  ▪ Sub-Field size is smaller than the Main Field (given as input)
	  ▪ Use minimal number of Sub-Fields to cover the care area
	  ▪ Sub-Fields cannot overlap as this will cause repeated scan of the same area which will damage the wafer in that area
	  ▪ Sub-Fields cannot extend beyond the Main Field
	  ▪ Minimize the Sub-Field area extending outside the care area
	  ▪ Some problem data-sets given allow for multiple sub-field sizes (given as input)
 
