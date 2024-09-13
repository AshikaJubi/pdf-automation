
# Exercise-7 Extract text from a PDF and save it to a text file

### Reg No : 212221040020


## AIM: 
 To read and extract text from a PDF file using UiPath.


## Activites Required:

  1.Read PDF Text
  2.Write File Text
  
## Procedure:
1.Download a sample PDF file   or create one with some text.

2.Open UiPath Studio   and create a new project called PDFAutomation.

3. In the   Activities Panel  , search for Read PDF Text and drag it into the   Designer Panel  .

4. Set the   FileName   property to the path of the PDF file.

5. Create a variable pdfText to store the extracted text by pressing Ctrl + K and typing pdfText.

6. Add a Write Text File activity to the workflow.

7. Set the   FileName   property to where you want to save the text file (e.g., C:\Users\YourName\Documents\output.txt).

8. Set the   Text   property to pdfText.

9.   Save   and   Run   the workflow.

      
## Workflow:
![image](https://github.com/user-attachments/assets/9de7b66a-a1cd-4e5f-b5a8-008ef88b91db)



## Output:
![image](https://github.com/user-attachments/assets/a37b2ab9-192f-4f19-aa08-42e11ec8c61c)

![image](https://github.com/user-attachments/assets/28ebf3f3-afb7-4e00-9cc3-a0ea1440ca06)


## Result:
  Thus, the workflow that read and extract text from a PDF file is implemented successfully.
