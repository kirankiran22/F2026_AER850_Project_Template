# AER850 Project Template - F2026

Please read this description carefully. It includes instructions on how to use this template, set up your development environment, and push your final code.

## Using this Template

Click the green **Use this template** button at the top of the page and choose **Create a new repository**.

Provide your own repository name, and set the repository to **Public**.

![271051255-e9320339-63c7-413c-b50c-144db84a9711](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/d7834484-baaf-4399-ae8c-8dc12f0b8ff4)

## Cloning & Pushing to your Repository

Clicking the green **Code** button will allow you to copy a link to your repository.

![271051552-8e4384f0-8ad9-413e-82c0-6fc9f46a190a](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/f5abc9b7-5e3f-4403-a3b8-4a84b6a8aa2c)

Choose the workflow below that matches your development environment.

### Option A: Local IDE (VS Code, PyCharm, or Spyder)

If you are developing locally using an IDE like VS Code (highly recommended), PyCharm, or Spyder, you can use GitHub Desktop to manage your files visually without needing the command line interface (GIT).

1. Download and install [GitHub Desktop](https://desktop.github.com/).
2. Once you have installed and connected your GitHub account to the application, clone your repository using the **Clone a repository from the Internet...** option. Search for your repository or paste the URL copied from the step above.
3. Select a local path (by default: `C:/Users/%User%/Documents/GitHub/%name of your repo%`) and press **Clone**.

![271053499-c138013c-5157-41ba-97c2-db751b021bd1](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/d088621d-23db-4e45-8add-f301cbc6cd09)

4. Open the cloned folder in your IDE. You will see the project data file (`Project 1 Data.csv`) and this README. Create a new file here for your Python script.
5. As you make changes to your script, GitHub Desktop will track them. Enter a quick description of your work in the bottom-left summary box, then click **Commit to main**.

**Important Data Warning:** Do not duplicate or upload additional large datasets to this folder. GitHub blocks pushes containing files larger than 100MB, which will break your repository synchronization.

![271057822-aee467ae-d78e-4cdd-804f-2098ea111c44](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/4cd1bf5e-9585-460c-a009-ab75ceb99ca4)

6. Push your changes to GitHub by pressing **Push origin**.

![271058164-69ec4a4a-070b-4b15-9da7-637425a318fa](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/667c8a26-5258-42ea-b2f0-8661352634f6)

### Option B: Google Colab (Cloud)

If you are using [Google Colab](https://colab.research.google.com/), you need a slightly different workflow to access the data and save your code.

1. In your GitHub repository, click the green **Code** button and select **Download ZIP**.
2. Extract the ZIP and upload the data file (`Project 1 Data.csv`) to a dedicated folder in your Google Drive.
3. Launch Google Colab, create a new notebook, click the **Files** tab on the left sidebar, and click the **Mount Drive** icon.

![271059328-65999918-df53-4003-b336-12f7adc5d63d](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/a18c5c64-1a98-4c6d-bcde-e4e3b53fb30f)

4. You should now see your Google Drive folders. Read the data into your code using the path: `'drive/MyDrive/%foldername%/Project 1 Data.csv'`

**Saving and Submitting Your Code:**

Once you have made changes to your Colab file, it will save locally to your Google Drive. You push the final version to GitHub. I will not be downloading and running your project or assignment codes, just seeing the final versions on github and your results. 

1. Go to **File** --> **Save a copy in GitHub**.
2. Authorize Google Colab to sign into your GitHub account.
3. Select your newly created project repository from the dropdown.
4. Add a short commit message describing what you did in the file, then press **OK**.

![271061222-0d94718a-7a98-4310-bf7f-85101b9c3501](https://github.com/ShashankVSS/AER850_Project1_Template/assets/32677397/d0145da6-fac2-446b-a98e-4e19d284ae43)

This will upload your final `.ipynb` file directly to your GitHub repository.
