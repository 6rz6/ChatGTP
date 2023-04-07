# ChatGTP 
Open AI ChatGTP modules taken to the extream 

Python Terminal which can execute code in chatgtp:
--------------------------------------------------------
can you run the following code in a python terminal simulation?
import requests
from bs4 import BeautifulSoup

def scrape(URL):
response = requests.get(URL)
soup = BeautifulSoup(response.content, 'html.parser')
return soup.text

Call the scrape function with the URL "https://gym1.shop/"

result = scrape("https://gym1.shop/")

Print the result

print(result)
--------------------------------------------------------
