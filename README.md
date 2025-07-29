# Lab: Authorizing Requests

## Project Description
Now that we've got the basic login feature working, we need to reward our logged-in users with some bonus content that only users who have logged in will be able to access. We added a new attribute to our articles, `is_member_only`, to reflect whether the article should only be available to authorized users of the site. We also created two new views: `MemberOnlyIndex` and `MemberOnlyArticle`.


## Resource

- [GitHub Repo](https://github.com/webdesigns23/flask-authorizing-requests-lab.git)

## Set Up and Installation Instructions

1. Fork and Clone the Repo to get started

2. Set up your virtual environment of choice (virtualenv prefered)
```bash
virtualenv velab
source velab/bin/activate
```
3. Install PyPi dependencies using requiements.txt
```bash
pip install -r requirements.txt
```
4. Install node.js dependency to run React
```bash
npm install --prefix client

```
5. Execute migration script upgrade and populate initial data 
```bash
cd server
flask db upgrade
python seed.py
```
## Running Application

You can run the Flask server with:

```bash
python app.py
```

And you can run React in another terminal from the root project directory with:

```bash
npm start --prefix client
```

## Testing
You can work on this lab by running the tests with Pytest. It will also be
helpful to see what's happening during the request/response cycle by running the
app in the browser with the above commands.

```bash
pytest
```

## Commit and Push Git History

1. Add your changes to the staging area by executing
2. Create a commit by executing 
3. Push your commits to GitHub by executing 
* If you created a separate feature branch, remember to open a PR on main and merge.
```bash
git add .
git commit -m "Your commit message"
git push origin main
```


