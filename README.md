# External_sorting
C code

By performing  external sort we can use  multiple disk drives parallelly (in order to improve sequential read and write speed), 
and it will increase the speed of both hardware and software.   External sorting is a term for a class of sorting algorithms that can handle massive amounts of data. It  is required 
when the data being sorted do not fit into the main memory of a computing device (usually RAM) and instead they must reside in the slower external memory
(usually a hard drive). External sorting typically uses a hybrid sort-merge strategy.In the sorting phase, chunks of data small enough to fit in main memory are read, sorted, and 
written out to a temporary file. In the merge phase, the sorted sub-files are combined into a single larger file. External Sorting will access items in sequential order and 
it also minimizes the access times.External Sorting is a stable sorting technique.
			This external sorting program contains the functions showData,splitData and sortData. it also contains an input text file with the name input.txt.

