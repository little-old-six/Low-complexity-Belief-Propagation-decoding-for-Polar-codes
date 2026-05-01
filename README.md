# Low-Complexity Belief Propagation Decoding for Polar Codes
These are a set of programs for my research work, called “Low-Complexity Belief Propagation Decoding for Polar Codes”.


# Abstract: 
Due to the high parallelism, belief propagation (BP) decoding is considered as a promising solution for the decoding latency challenges of long polar codes. However, the computational complexity of BP decoding is much higher than that of the successive cancellation (SC) decoding. In this paper, two novel early termination criteria (ETC) are proposed to bridge this complexity discrepancy by avoiding unnecessary BP iterations. The first criterion functions when all the least reliable bits are decoded with stable log-likelihood ratio (LLR) magnitudes.	It requires only the OR and the XOR operations, yielding an inherent advantage in hardware implementation. To better detect the BP decoding convergence, a special type of processing element (PE) of BP decoder, named the frozen-information PE (FIPE), is introduced. By utilizing the FIPE, an ultra-low complexity ETC is proposed to further reduce the decoding complexity. It functions when all frozen bits in the FIPEs are successfully decoded. Our numerical results show that the proposed criteria can significantly reduce the redundant BP iterations without any degradation in error-correction performance. Compared with the state-of-the-art worst information bit (WIB) criterion, the proposed criteria reduces the number of iterations by more than half. Moreover, the proposed criteria yield a lower hardware complexity than the existing G-matrix criterion and the WIB criterion.


# Description: 
These are a set of programs for my research work, called “Low-Complexity Belief Propagation Decoding for Polar Codes”.

- **Method for selecting the optimal parameter:** A method for obtaining the optimal parameter for the proposed ETCs.



## Contact & Feedback:
- These algorithms might be confusing. Please read the paper carefully, and if you still do not understand it, feel free to contact me via email address ZhongjunYang at ieee dot org

- I will also share the whole C++ codes soon, once my paper is accepted. 

- Please report any bugs to ZhongjunYang at ieee dot org.
