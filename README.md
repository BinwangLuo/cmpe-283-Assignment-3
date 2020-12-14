# CMPE-283-Assignment-3
Binwang Luo 014632566  
## Question 1.I did this assignment by myself  
## uestion 2. I did this assignment as below steps:  
 1. I setup the environment as what I did in assignment-2. Because I did assignment-2 with Ivan and run it in his computer, so I should reset one in mine for this assignment. After that, I checked all the package which I need.  
 2. Then I what I should do is to run the code in my ecvironment. The code files included cpuid.c and vmx.c. I updated the two files. As the requirement of this assignment, we need to creat new cpuid leaf and determine where to place the measurement code. Therefore I updated the cpuid.c to let it can support the new CPUID leaf 0x4FFFFFFE. At the same time the vmx.c file also updated to track the exit counts.
 3. After setting the environment and build set the file as assignmen-2, we can get two VM as what we got in assignment-2. Then we should set the updated kernel code and install the modules in the VM which is outside.  
 4. In the nested VM, installing cupid package and test each leaf. 
 5. Print out the results of test in VM.  
 ## Question 3. Comment on the frequency of exits – does the number of exits increase at a stable rate? Or are there more exits performed during certain VM operations? Approximately how many exits does a full VM boot entail?    
 According to the results, there is not increase at a stable rate. There might be 500 k exits after boot up.  
 ## Question 4. Of the exit types defined in the SDM, which are the most frequent? Least?  
  The most frequent types: I/O instrcution, MOV DR, APIC access  
  The least frequent types: WBINVD, External interrupt
