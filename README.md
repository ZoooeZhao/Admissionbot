# GUAdmissionsBot
Final Project for COSC 483 Dialogue Systems: Georgetown University Undergraduate Office of Admissions "Jack the Bulldog" Chatbott

Rasa 3.1 is required for this system, and we recommend using Python 3.7.9.


# Install Rasa
Install Rasa using the following command:
``
pip3 install rasa
``
# Create a virtual environment and activate it
Create a virtual environment using the following command:
``
python3 -m venv ./venvname
``
Activate it using:
``
source ./venvname/bin/activate
``

# Add the AdmissionsBot data into your virtual environment
Download the files of this repository into your virtual environment.

# Change directory to AdmissionsBot
Change your directory with the following command:
``
cd /path/to/AdmissionsBot
``

# Run Widget 2.0 server*
Run the following in your command line to load the Widget server:
``
rasa run -m models --enable-api --cors "*" --debug
``

# Run Widget 2.0
Double click/open the index.html file that is in the dist folder of the Chatbot Widget folder ( ./venv/AdmissionsBot/Chatbot-Widget-Widget2.0/dist/index.html). 

The widget should load on your browser.

# Running chatbot on terminal
You can also run the chatbot on your terminal. Instead of running models on rasa (as listed above), simply run:
``
rasa shell
``

# That's it!
We hope you enjoy interacting with Jack the Bulldog and get your questions answered about the Georgetown University Undergraduate admissions process!

*We modified the UI of the Rasa Widget 2.0 offered by Jitesh Gaikwad at https://github.com/JiteshGaikwad/Chatbot-Widget/tree/Widget2.0.

Please note that all responses were manually written by the developers Nov/Dec 2022. There are no automatic updates to the information, so please do not rely solely on the chatbot for accurate/updated information!

- jdc286@georgetown.edu , cz335@georgetown.edu
