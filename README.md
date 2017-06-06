# add_bookmarks_to_pdf
This project aims to add bookmarks to the pdf automatically.


### Steps:
1. put the script named 'addBookmarks.py' and the pdf file together in a directory.
    
2. creata a txt named as the target pdf in the directory
    ![](/readmeFig/1.png)
3. copy the table of content from the pdf and paste it in the txt
    ![](/readmeFig/4.png)
4. find the page number of the first bookmarks from the target pdf
5. open a command prompt window in the directory
    ![](/readmeFig/2.png)
6. type 'python addBookmarks.py pdfName pageNum' into the command prompt and run it.
    ![](/readmeFig/3.png)
    

The new pdf and the table of contents will be created in this directory.For example,in the picture above,the file named 'test_new.pdf' is the new created pdf file with bookmarks and the file named 'test_toc.txt' is the structure of bookmarks.

    
