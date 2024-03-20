import requests
from bs4 import BeautifulSoup
import pyperclip

url = input("Please enter the URL")
response = requests.get(url)
soup = BeautifulSoup(response.text, "html.parser")
link = soup.iframe['src']
pyperclip.copy(link)

#vidmoly = "&s=vm"
#hydrax = "&s=hx"
#kimcartoon version source differences:
#can be accesed with "&s=" and the name of the source
#currently, most links default to vidmoly
