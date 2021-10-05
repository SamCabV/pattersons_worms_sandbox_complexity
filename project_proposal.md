# Recreating Paterson’s Worms
# Alana Huitric and Sam Cabrera
# Abstract

We plan to investigate the patterns and behaviors of Paterson’s Worms by re-writing it in python. Paterson’s worms are a type of cellular automata that are often mentioned along with Turing machines, Langston’s Ant and turmites. Due to the triangular grid in its original implementation, we will have to overcome the programming challenges this will hold in representation as well as figuring out how the patterns the original worms create resemble that of prehistoric sea-worms. We will extend this idea by implementing a user interface with to the worms program, making it easier to visualize and use, and eventually we will implement a 3D, 8-vertex version of the worms, to observe the difference between different ruleset groups when more degrees of freedom are given to the worm. 

# Annotated Bibliography
[Paterson’s Worm](https://dspace.mit.edu/bitstream/handle/1721.1/6210/AIM-290.pdf) by Micheal Beeler:  This paper from MIT in 1973 describes the rules of the mathematical idealization of prehistoric worm trail patterns. To do this, it proposes an automation that operates on a triangular grid, with each vertex having 6 edges at which to approach. The worm automatons function by exploring new vertices, one at a time, with different rule sets resulting in different directions from interactions with vertices. It also discusses the cases that could not be computed with the technology at the time as they seemed to go on forever.

# Experiments
The first thing we would like to replicate from these papers would be the original Paterson’s worms on a triangular grid. This includes some form of animation to better study and visualize the behavior of different worms. In addition to this, we can use various parameters, such as node number visited and path length to validate the behavior to that of the paper. 

As an extension, we will implement a UI to better interact with the creation and observation of worms. Beyond this, we want to implement an 3D version of langston’s worm, with nodes at the vertices of a hexagonal prism tesselation of 3D space such as:
*PLACE image here of honey combs*
The worm will now have 8 possible directions to move, having the same 6 hexagonal directions, and moving up and down a plane:
*insert behavior pic here*


# Experimental Results
We will test the patterson’s worm code by running specific rulesets provided in the paper and checking that various different configurations match:

For Ruleset (0,4,2,3), the ending worm should look like this: 

For further validation, this table presents various ending lengths and node counts for various rulesets:


# Result Interpretation
One of the methods of analysis for the worms in the paper is calculating the coefficient of *path length/number of nodes visited*. This coefficient seems to grow as the length of the worm (and somewhat the number of generations the worm lives). We can use this to further analyze how certain general types of rulesets function.
We can apply these ideas to the 3D extension and similarly use it to characterize ruleset behaviors. 

# Causes for Concern
Due to the abstract nature of this model, even with the above results interpretation it may still be a somewhat unsatisfying result. Which does not necessarily make it wrong however we want to make sure there will be enough material in this project that we are learning something from it.



# Next Steps
	# Alana:
	- Researching implementation of Paterson’s worms especially the rules needed for a successful implementation
	- Start pseudocode classes for running the worms

	# Sam
      -	Figure out how we can efficiently implement a hexagonal lattice for a worms implementation
      -	Find an efficient way to visualize and animate an implementation of worms
