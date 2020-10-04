1. Create a vrtual environment: 

	$ python3 -m venv my_env
	$ source my_env/bin/activate

(The first command might be python or python3 based on your computer and the version of Python)

2. Install the necessary packages: 

	$ pip install -r requirements.txt

3. Run the server:

	$ python manage.py runserver

4. To see the blog visit: http://127.0.0.1:8000/blog/
	To see the admin controls visit: http://127.0.0.1:8000/admin/