# Person-Detector
An algorithm to count the number of people in a surveillance image of a mall based on a Support Vector Machine person detection technique.

## How to run

1. Upload 'frames' folder on the root of your Google drive storage to match the path = '/content/drive/My Drive/frames/'
2. Open Google Colab from you Google Drive account where you uploaded the frames folder
3. Set to GPU. In the menu, go to Runtime -> Change runtime type -> GPU
4. In the menu, go to Runtime -> Run all
5. The first cell will run then prompt you to restart runtime. Click on Restart Runtime in output or from menu Runtime -> Restart runtime
6. Runtime -> Run all
7. Ensure the first cell output does not prompt you to restart again and shows all 'Requirements already satisfied'
8. The second cell will ask you to authenticate to access the frames folder. 
   Authenticate by clicking on the link that will direct you to a new page with the authentication link. 
   Sign in. Click Allow when it asks you for access permission from Google Colab.
   Copy the authentication link provided and paste it in the input box from the output of the second cell, press Enter.
9. Wait until completion
10. You will find a CSV file in your drive named DeisAnas_submission.csv

Runtime: ~ 15 minutes excluding last two cells, ~ 4 hours otherwise.

Note: If due to inactivity the session prompts you to reconnect and you want to run it back, then you may have to run it 
from the beginning by restarting the runtime first before running (step 4-5) as the local variables might have been lost, 
especially if it tells you that some variables or packages are undefined after re-running a cell, etc.
