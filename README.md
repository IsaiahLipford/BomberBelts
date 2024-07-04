# BomberBelts
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~Adding AI Scripts~~~~~~~~~~~~~~~~

	-To add an AI script to the AI list, put it in the "Assets/Resources/AI Scripts" directory.

	-A sample AI and a template for others' AI have been provided in that directory.

	-Additionally, all Characters in the levels SHOULD NOT have an AI script attached to them or things will break.
		(Not really break, but the 2 scripts will be running at the same time producing odd results)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~Creating New Levels~~~~~~~~~~~~~~~

	-To add a new level to the level list, put it in the "Assets/Resources/Levels" directory.

	-For convenience, there is a Level Generator script located in "Resources/Game Scripts" that will automatically
	generate all of the necessary objects for a level and make almost all of the necessary assignments.

	-To use, attach the script to any gameObject and assign the necessary prefabs. Don't worry about anything below the
	"Belt Spacing" field. Use Update to make changes and Clear to delete all instantiated objects.

	-Once these objects are created, feel free to alter them in (mostly) anyway. However, they will get reset when
	Update is pressed.

	-The GameScript gameObject created by the generator will require assigning the win screens to get working fully.

	-Changes to prefabs will require that the level generator be updated.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~Modifying Game Rules~~~~~~~~~~~~~~

	-All of the game rules are held in the GameScript gameObject. 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~Other Stuff~~~~~~~~~~~~~~~~~~

	-For the purposes of just writing an AI and running the tournament, you should only need to load up the Menu scene 
	in the editor and play from there.
