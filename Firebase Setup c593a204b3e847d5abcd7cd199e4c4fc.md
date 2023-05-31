# Firebase Setup

Created: May 31, 2023 9:14 PM
Video Link: https://www.youtube.com/watch?v=bG30uJ530-A

![FlutterFlow Notion Gallery Images.png](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/FlutterFlow_Notion_Gallery_Images.png)

# **How to Set Up Firebase in FlutterFlow**

Setting up Firebase in your FlutterFlow project is a straightforward process. Follow the steps below to connect Firebase to your project:

## **Step 1: Creating a Firebase Project**

1. Visit the Firebase Console page: **[https://console.firebase.google.com/](https://console.firebase.google.com/)**
2. Create a new project by clicking on the "**Add project**" button.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled.png)
    
3. Provide a name for your project and proceed with the creation process.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%201.png)
    

## **Step 2: Granting Access to Firebase in Your Project**

1. After creating the project, go to the "**Users and permissions**" setting tab.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%202.png)
    
2. Click on the "**Add member**" button and add the email address: **`firebase@flutterflow.io`**.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%203.png)
    
3. Assign the role as "**Editor**" for the added member.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%204.png)
    

Continue until you create a project

## **Step 3: Configuring Advanced Permissions**

1. Access the "**Advanced permission settings**" option in the bottom right corner of the page.
2. Locate the Firebase email (**`firebase@flutterflow.io`**) and click on the pencil icon (edit principle) to edit permissions.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%205.png)
    
3. In the "**Edit permissions**" tab, click on "**Add Another Role**" and add the following two roles:
    - Cloud Functions Admin
    - Service Account User
        
        ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%206.png)
        

## **Step 4: Creating a Firebase Database**

1. Navigate to the "**Firebase Database**" tab under "**Build**" in the navigation bar.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%207.png)
    
2. Click on "**Create Database**" to begin setting up the database.
3. Select "**Start in test mode**" and proceed to the next step.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%208.png)
    
4. Choose the closest location from the dropdown menu.
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%209.png)
    

## **Step 5: Copying the Project ID**

1. In the navigation bar, click on the settings icon and choose "Project Settings."
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%2010.png)
    
2. Copy the Project ID displayed on the page.

## **Step 6: Connecting Firebase to FlutterFlow**

1. Go back to your FlutterFlow project and navigate to the "Settings and Integrations" tab.
2. Select "Firebase" under "Project Setup."
    
    ![Untitled](Firebase%20Setup%20c593a204b3e847d5abcd7cd199e4c4fc/Untitled%2011.png)
    
3. Paste the copied Project ID into the provided field and click "Connect."
4. Congratulations! Your project is now successfully connected to Firebase.

By following these steps, you can easily set up Firebase in your FlutterFlow project and unlock the powerful features and functionalities it offers.