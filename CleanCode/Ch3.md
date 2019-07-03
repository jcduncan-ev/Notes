#Functions#
##Main Ideas##
- TO Paragraphs for Abstraction Levels
- Single Responsibility Principle (SRP) 
- Open Closed Principle (OCP) 	
- It's all about writing the story of the program through code

##Tips##
- TO paragraphs
	[] TO {verb_action}, we do x, y, z. Therefore, x,y,z belong in this TO function, anything deeper should be its own function
		[] TO x, we do a, b, c. Therefore, a,b,c belong in this TO function, anything deeper should be its own function
			[] TO a, we do e, f, g.
		[] TO y, we do h, i, j.
		[] TO z, we do k, l, m.
- Functions should be <20, ~4-5
- Never use switch statements and avoid in-depth if/then
- If/then should be a single line
- Minimize arguments inputed to functions


- Clean Code mandates the use of state-holders like Redis
- multiple methods (e.g Writing streams: one for writing, one for reading, one for writing&reading)
- 2/3 arguments may be better expressed as a separate class
- avoid output arguments
- Error handling counts as a separate thing; avoid error codes
- 
