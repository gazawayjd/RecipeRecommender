# RecipeRecommender
Capstone Project for BS in Computer Science

**Step 1: Prepare Your System**

Before you start, ensure that you have Python and pip installed on your computer.

**Step 2: Extract the Zip File**

Unzip the provided zip file that contains 'user_GUI.ipynb' and the associated CSV database to the directory of your choice.

**Step 3: Open a Terminal or Command Prompt**

Open a terminal or command prompt on your computer.

**Step 4: Navigate to the Directory**

Use the `cd` command to navigate to the directory where you extracted the zip file. For example:

cd path/to/your/directory

**Step 5: Initiate virtual environment**

Create a virtual environment to operate within by using the following prompts:

python -m venv venv
venv\Scripts\activate.bat

Your virtual environment should now be active for downloading necessary python libraries.

**Step 6: Install Voila**

If you don't have Voila installed, you can do so by running the following command in your terminal or command prompt:

pip install voila

**Step 7: Install Required Libraries**

Run the following command to install the required libraries using the requirements.txt file:

pip install -r requirements.txt

**Step 8: Start Voila**

Then, execute the following command to start Voila and convert your Jupyter Notebook into an interactive web application:

voila user_GUI.ipynb

**Step 9: Access the GUI**

Voila should open the GUI in your native browser, but it will provide you with a URL in the terminal where it's running. It should look something like this:

Voila server running at:
http://localhost:8866/

Open your web browser and enter the provided URL (e.g., `http://localhost:8866/`) to access and interact with your GUI if it doesn't open automatically.

**Step 10: Use the GUI**

You should now be able to use the GUI, enter ingredients to see the top 5 recipes that most closely match your pantry. 

For example, if you input "olive onion head cabbage zucchini carrot celery whole tomato garbanzo bean kidney bean spinach chicken broth tomato wine leaf pasta parmesan cheese" you will receive "Minestrone" as the top option, because it has all the ingredient listed.
