Install goes something like this:
Install instructions:

Min requirement is 3.8

download the zip file of the entire code stack

Unzip the file in the preferred file folder, Use that same folder later

start anaconda navigator


pip install --upgrade openai (worked)


run the bat script .\install.bat (none found in zip, copied previous worked))


start pycharm

cd to project folder C:\Matts\scriptsmk\Tot

run python -m venv .venv  (in that folder directory(worked))

run .\venv\Scripts\activate.bat (worked)



pip install streamlit (worked)

streamlit hello (to check if working(Failed, Not working)
)

PS C:\Matts\scriptsmk\Tot> pip install -r requirements.txt




(to run locally type in  streamlit run main.py )(Failed, Not working)





streamlit run main.py` 

.\streamlit_app.py 

I got the following Error:

C:\ProgramData\anaconda3\python.exe C:\Matts\scriptsmk\Tot\main.py 
Traceback (most recent call last):
  File "C:\Matts\scriptsmk\Tot\main.py", line 105, in <module>
    chain = ChainOfThoughts()
            ^^^^^^^^^^^^^^^^^
  File "C:\Matts\scriptsmk\Tot\main.py", line 19, in __init__
    self.client = openai.OpenAI(
                  ^^^^^^^^^^^^^
AttributeError: module 'openai' has no attribute 'OpenAI'

Process finished with exit code 1



https://chainofthoughts-gpt-py-lmrrhfrftbyzr3q68vhsni.streamlit.app/ 


You do not have access to this app or it does not exist
You're currently signed in as   and with github.com/ Are you sure these accounts have access?
with a different account.
If you believe this is a bug, contact support.


download the code create a new repo on github (make it private)

add the files and push them to the repo

and go to streamit and link your repo with it

in case you don't want to run it locally
