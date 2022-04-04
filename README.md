# Writing Analyzer

_The key to all your writing problems._



Just input a paragraph into our app, and we guarantee it will segment it into sentences. Unless your paragraph is too large, that is. Then you better clear.



Requirements on your part:

- Ananconda
- NPM



## Usage Instructions

### Flask Server

Save the models (see https://github.com/treeai/writingAnalysis for more details) into a `models_gitignored` directory in `server`.

```sh
cd ./server
pip install -r requirements.txt
python app.py
```



### Vue Client

```
cd ./client
npm i
npm run serve
```

