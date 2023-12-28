# discord
import requests

url = "ì¸í°ëì ìëí¬ì¸í¸ URL"
api_key = "ë°ê¸ë°ì API í¤ ëë í í°"

headers = {
    "Authorization": f"Bearer {api_key}",
    "Content-Type": "application/json",  # Content-Typeì APIì ë°ë¼ ë¤ë¥¼ ì ììµëë¤.
}

response = requests.post(url, headers=headers, json={"key": "value"})

print(response.text)
