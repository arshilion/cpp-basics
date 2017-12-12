Dec 12

cpp programming 

	complie a.cpp - should do for result
		
		g++ a.cpp

	excute a.cpp

		./a.out 

	excute a.cpp and make input by text

		./a.out < text.txt


	excute a.cpp and make input and output by txt

		./a.out < text.txt > ouput.txt

	using pipe , simultaniously using other command
	find specific text in result  ( result displayed by string)

		./a.out < text.txt | grep (want word) -v (exception) > output.txt 

	find diff of two files

		diff a.cpp b.cpp
		vimdiff a.cpp b.cpp

	using namespace std;   skip std::

		std::cout changes to cout

	diff between python import, from, as

		import numpy as np
			numpy.ones(4)
			np.ones(4)

		from numpy import ones
			numpy.ones(4)
			ones(4)
	
//	using namespace - delete, using import (change name)






