This requires several libraries and python installed to work.<br> I recommend using PyCharm because you can install them directly into your virtual environment. <br>Put your api key and file path on the indicated lines:
<br>gpt.py:
<br>line 10: os.environ["OPENAI_API_KEY"] = "your-api-key"
<br>line 97: folder_path = f"C:/path/to/your/folder/{folder_name}"
<br>gemini.py:
<br>line 12: os.environ["GEMINI_API_KEY"] = "your-api-key"
<br>line 105: folder_path = f"C:/path/to/your/folder/{folder_name}"
