# CS540_PRG3
Programming Assignment 3
Program Functionality:
1. PageFrameTable Class:

__init__(self, num_pages): Initializes a page frame table with a specified number of pages (num_pages) and an empty dictionary to store page-frame mappings.
map_page_to_frame(self, page_num, frame_num): Maps a page number to a frame number in the page frame table.
get_frame_number(self, page_num): Retrieves the frame number corresponding to a given page number from the page frame table.
translate_logical_address Function:

2. translate_logical_address(logical_address, page_size):
   Divides a logical address by the page size to obtain the page number and offset.

3. Main Function (main):
   
Initializes a PageFrameTable instance with 256 pages and maps sample page numbers to frame numbers.
Defines a list of sample logical addresses.
Translates each logical address into a page number and offset using the translate_logical_address function.
Prints the original logical addresses along with their corresponding page numbers and offsets.

Instructions for Execution:
Copy the provided code into a Python environment or a Python file (e.g., main.py).
Ensure that the Python environment has access to the necessary dependencies (none required beyond standard Python libraries).
Run the program by executing the Python file (python main.py).
The program will output the translated logical addresses with their corresponding page numbers and offsets.


By following these instructions, you can execute the program and observe its functionality, which includes mapping logical addresses to their respective page numbers and offsets using a page frame table.
