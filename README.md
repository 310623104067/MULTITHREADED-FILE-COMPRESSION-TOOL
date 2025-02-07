# MULTITHREADED-FILE-COMPRESSION-TOOL

COMPANY:CODTECH IT SOLUTIONS NAME: KARTHIK SRINIVAS SEKAR

INTERN ID:CT08NLW

DOMAIN:C++ PROGRAMMING

DURATION : 4 WEEKS

MENTOR:NEELA SANTHOSH

#A multithreaded file compression tool in C++ would typically use a library like zlib or LZ4 for compression and std::thread (or OpenMP) for multithreading. The basic workflow would be:

Read the file in chunks: Divide the file into multiple segments.

Process each chunk in a separate thread: Compress using zlib, LZ4, or another algorithm.

Write the compressed chunks to an output file: Maintain order if needed.

#OUTPUT

![Image](https://github.com/user-attachments/assets/3502f92e-b425-45ca-a015-0414d347522e)
