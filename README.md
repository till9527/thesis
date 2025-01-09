This requires several libraries and python installed to work.<br> I recommend using PyCharm because you can install them directly into your virtual environment. <br> You must also have already created an API key for both Gemini and ChatGPT(paid version).<br>Put your api key and file path on the indicated lines:
<br>gpt.py:
<br>line 10: os.environ["OPENAI_API_KEY"] = "your-api-key"
<br>line 94: folder_path = f"C:/path/to/your/folder/{folder_name}"
<br>gemini.py:
<br>line 12: os.environ["GEMINI_API_KEY"] = "your-api-key"
<br>line 99: folder_path = f"C:/path/to/your/folder/{folder_name}"
