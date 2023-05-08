Download Link: https://assignmentchef.com/product/solved-ucs1411-exercise-9-implementation-of-paging-technique
<br>
To develop a C program to implement the paging technique in memory management.

<u>Procedure:</u>

<ol>

 <li>Get the total size of the physical memory and the page size.</li>

 <li>Divide the physical memory into frames.</li>

 <li>Initialize the physical memory structure using random number generation (Some frames must be free and some random frames are already allotted to other process)</li>

 <li>Construct the free frame list.</li>

 <li>Get the Process memory requirement. Divide the LAS into n pages.</li>

 <li>If n free frames are available, allot the process and update the page table.</li>

 <li><u>Show the conversion of any logical address into the corresponding physical</u> <u></u></li>

 <li>Do de-allocation accordingly.</li>

 <li>Repeat the steps 5-8 for N processes.</li>

</ol>

SAMPLE INPUT/OUTPUT:

Paging Technique

Enter the physical memory size: 32 KB

Enter the page size = 1 KB

<u>Physical memory is divided into 32 frames.</u>

After initialization

<u>Free Frames: 3 6 9 12 1 2 18 30 25</u>

<ol>

 <li>Process request</li>

 <li>Deallocation</li>

 <li>Page Table display for all input process</li>

 <li>Free Frame list display</li>

 <li>Exit</li>

</ol>

<h1>Enter the option:1</h1>

Enter the Process requirement(ID,size): P1, 4 KB

<u>Process is divided into 4 pages</u>

<h1><u>Page Table for P1:</u></h1>

<h1>Page 0 : Frame 3</h1>

<h1>Page 1: Frame 6</h1>

Page 2 : Frame 9

Page 3: Frame 12

<h1>Enter the option: 4</h1>

<u>Free Frames: 1 2 18 30 25</u>

Enter the option: 1

Enter the Process requirement(ID,size): P2, 2 KB

<u>Process is divided into 2 pages</u>

<u>Page Table for P2:</u>

Page 0 : Frame 1

Page 1: Frame 2

Enter the option: 4

<u>Free Frames: 18 30 25</u>

Enter the option: 3 <u>Page Table for P1:</u>

Page 0 : Frame 3

<h1>Page 1: Frame 6 …..</h1>

<u>Page Table for P2:</u>

Page 0 : Frame 1

Page 1: Frame 2

Enter the option: 2

Enter the process ID to be de-allocated:P1

Enter the option:4

<u>Free Frames: 18 30 25 3 6 9 12 ( freed frames appended at end)</u>














