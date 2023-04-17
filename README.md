# CPSC 481 - Final Project

## Group 13 
Logan Perry-Din - 30070661

Yiannis Hontzias - 30066528

Daniel Chau - 10162889 

Kenny Vo - 30065390

Nicholas McLaughlin- 30052071

## Compiling and Running the system.

The system was built using dotnet 7.0 and Blazor. To run the app on a live development server, `dotnet` must be installed. To verify the latest version of dotnet is installed, in a terminal run `dotnet --version`

To run the code:

1. Download all files from the source code folder. 
2. Navigate to the root directory
3. Build the project with `dotnet build`
4. Run the live development server with `dotnet watch`. A webpage running the app should then open automatically.

## Login
- Once at the login page, you will see two text fields and two buttons. The text field for Username and Password can be entered, and login will redirect you to the homepage.
- The "Create Account" button will redirect you to account creation. In the e-mail text field, type "alice.smith@gmail.com", in the username text field, type "Alice Smith", and the password "123456".
    - This account has pre-made images and collections for testing purposes.
- Once that is done, click "Create Account" to be redirected back to the main login screen.
- In the Username textfield, type "Alice Smith" and in the password text field, type "123456".
- You will then be logged into the home page.

## Homepage

- Navigate your collection of photos by scrolling through each collection window. 
- Click different folders on the left sidebar to navigate to that collection.
- Hover over photos to view quick stats.

## Details
- When hovering over a photo, click "expand details" to go to the details page of that photo
- Click "edit" on the top to edit the name, description and price of the photo, then cancel or save.
- Click "remove" to archive the photo. (This only works for mt fuji in the mountains collection)
- View different graphs by selecting a time frame in the drop down menu.

## Compare
- From the homepage, click "compare" then hover over two images and select the check box to compare their statistics.
- Click "compare selected" to view the stats fo the two photos.

## Uploading a New Photo
- From the homepage, click "upload" on the top bar to open the upload interface.
- Click "Browse" to open a file open dialog and choose a photo. 
- Fill out the fields and hit "continue" to finish.
- Click the x to cancel.

## Uploading a New Collection
- From the homepage, above the folders, click the plus icon.
- From here, select the photos you want to add to the collection and fill out information fields. 
- Click the individual photos to fill out information about the photos.
- Hit continue to finish.