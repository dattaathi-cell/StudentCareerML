Deployment options

1) Streamlit Community Cloud (recommended)

- Sign in at https://share.streamlit.io with GitHub and create a new app using `dattaathi-cell/StudentCareerML`, branch `main`, main file `StudentCareerML/app/app.py`.

2) Render

- Create a new Web Service on Render.
- Connect your GitHub repo `dattaathi-cell/StudentCareerML`.
- Set the build command to: `pip install -r StudentCareerML/requirements.txt`
- Set the start command to: `streamlit run StudentCareerML/app/app.py --server.port $PORT`

3) Docker (generic)

- Create a `Dockerfile` that installs dependencies and runs the `streamlit` command.
