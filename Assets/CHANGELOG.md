EPPZEasing
----------

* 0.0.1

	+ Basic class hieararchy up
		+ `EPPZEasing` base class (empty implementations)
		+ Static pooling for easing instances
	+ Basic Members
		+ `EPPZEasing_Linear`
		+ `EPPZEasing_Ease_In`		
		+ `EPPZEasing_Ease_In_2`		
		+ `EPPZEasing_Ease_In_3`		
		+ `EPPZEasing_Ease_Out`		
		+ `EPPZEasing_Ease_Out_2`		
		+ `EPPZEasing_Ease_Out_3`		
	+ Lovely test scene
		+ `EPPZEasing_Samples`
			+ Object holds up some samples for inputs 0.0f - 1.0f
		+ `EPPZEasing_Samples_Renderer`
			+ Looky prefab that renders samples for easings
			+ Comes with editor script that keep renderers updated on inspector changes