# Black Box Testing

- ### Login Page Test

```python
from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager
from selenium.webdriver.common.keys import Keys
import time
driver = webdriver.Chrome(ChromeDriverManager().install())
 
driver.get("http://localhost:84/Project%20Showcase%20Management/")
 
 
submit = driver.find_element('xpath','/html/body/section[1]/div/div/div/button')
submit.click()
time.sleep(3)
 
driver.get("http://localhost:84/Project%20Showcase%20Management/login.php")
student = driver.find_element('xpath','/html/body/div/div/div/form[2]/div/button')
 
student.click()
time.sleep(3)
 
driver.get("http://localhost:84/Project%20Showcase%20Management/login_student.php")
time.sleep(3)
id = driver.find_element('xpath','/html/body/div/div/div/div[2]/form/div[2]/input')
password = driver.find_element('xpath','/html/body/div/div/div/div[2]/form/div[3]/input')
login = driver.find_element('xpath','/html/body/div/div/div/div[3]/button')
id.send_keys('011201046')
password.send_keys('12345678')
 
 
login.click()
time.sleep(3)
 
print('success ')
 
while True:
    time.sleep(1)
```

- ### Facult Login Page

```python

from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager
from selenium.webdriver.common.keys import Keys
import time
driver = webdriver.Chrome(ChromeDriverManager().install())
 
driver.get("http://localhost:84/Project%20Showcase%20Management/")
 
 
submit = driver.find_element('xpath','/html/body/section[1]/div/div/div/button')
submit.click()
time.sleep(3)
 
driver.get("http://localhost:84/Project%20Showcase%20Management/login.php")
faculty = driver.find_element('xpath','/html/body/div/div/div/form[1]/div/button')
 
 
 
 
faculty.click()
time.sleep(3)
 
driver.get("http://localhost:84/Project%20Showcase%20Management/login_faculty.php")
time.sleep(3)
id = driver.find_element('xpath','/html/body/div/div/div/div[2]/form/div[2]/input')
password = driver.find_element('xpath','/html/body/div/div/div/div[2]/form/div[3]/input')
login = driver.find_element('xpath','/html/body/div/div/div/div[3]/button')
id.send_keys('1')
password.send_keys('123456789')
 
 
 
login.click()
time.sleep(3)
 
print('success ')
 
while True:
    time.sleep(1)
    
```