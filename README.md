# video-sharing-fast-api
Video sharing platform tutorial with Fast API

Tutorial on Youtube: https://www.youtube.com/watch?v=x4zpR2TeO9g

Set up:
1. Created github repo and cloned using git clone
2. Created venv with `python3 -m venv .venv`. Activate with `.venv/bin/activate`
3. Copied over static and templates folder from tutorial repo (available in video description)
4. Installed dependencies with `pip install supabase fastapi uvicorn jinja2 python-dotenv python-multipart httpx`
5. Database was set up on supabase.com (free plan has about 50mb). Then update .env file with environment variables.
6. To run app, `uvicorn main:app --reload`

Stopped vid at 9:00