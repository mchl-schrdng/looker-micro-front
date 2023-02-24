My Looker Micro Admin
This is a Streamlit app that allows you to manage users and datagroups in Looker.

Installation
To run this app, you will need to install the following packages:

Copy code
pip install streamlit
pip install looker-sdk
pip install pandas
You will also need to set the following environment variables using GitHub secrets:

Copy code
LOOKERSDK_BASE_URL
LOOKERSDK_API_VERSION
LOOKERSDK_CLIENT_ID
LOOKERSDK_CLIENT_SECRET
Usage
To run the app, navigate to the directory where the code is saved and run the following command:

Copy code
streamlit run app.py
The app will open in your browser, and you can use the various sections to manage users and datagroups in Looker.

User Management
The "User Management" section allows you to add users to groups and remove users from groups. To use this section, you will need to authenticate with Looker using the Looker SDK.

You can add users to groups by selecting users from a table and groups from a table, and then clicking the "Add Users to Selected Groups" button.

You can remove users from a group by selecting a group from a table, selecting users from a table, and then clicking the "Remove Users from Selected Group" button.

Datagroups
The "Datagroups" section allows you to view information about all datagroups in Looker. To use this section, you will need to authenticate with Looker using the Looker SDK.

License
This app is licensed under the MIT License. See the LICENSE file for more information.