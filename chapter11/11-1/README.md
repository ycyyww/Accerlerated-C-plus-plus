If the class author does not specify these operations, the compiler synthesizes default versions of the unspecified operations.Now we can understand how the default Student_info operations execute. For example, the copy constructor copies four data elements. To do so, it invokes the string and vector copy constructors to copy the name and homework members respectively. It copies the two double values, midterm and final, directly.
