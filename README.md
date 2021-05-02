# Distributed_Arithmetic-DA-
 Distributed Arithmetic is a technique for multiplierless implementation of inner product of two vectors,particularly when one of the vectors is constant. 
Multiplier is the key component in digital designs.But the problem with multiplier is, it takes more area which leads to more power consumption.So we need a technique which performs multiplier operation with less area.So the one of the technique is Distributed Arithmetic in short DA.
DA is a bit serial operation,that implements a series of fixed point MAC operations in a fixed number of steps,regardless of the number of terms to be calculated.
If we take two vectors X[n] and A[n],then their product is available at Kth clock cycle,where K is word size of a element in X[n] and X[n] is called as variable vector and A[n] as fixed vector.Elements in X[n] should be between -1 and 1.
The main advantages of DA is, it takes less area and power and achieves higher throughput.
We can use this Technique in FIR filters,FFT,DCT,image and video processing functions,etc...
