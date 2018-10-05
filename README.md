# EngineerTestQA
var webdriver = require('selenium-webdriver');
var capabilities = {
    'browserName': 'Chrome'
  };
var browser = webdriver.Builder().withCapabilities(capabilities).build();
await browser.get('medseek-engineering.github.io/qa-engineer-test/');

 driver.findElement(webdriver.By.id('Join The Fight')).click();

var name = driver.findElement(By.id('xyz'));
name.clear();
name.sendKeys("name");
    
var email = driver.findElement(By.id('xyz@gmail.com');
email.clear();
email.sendKeys("email")

jobTitle.sendKeys("title"); var  = driver.findElement(By.id('yyyyzzzz'), 2000);
password.clear();
password.sendKeys("password");

Select dropdown = new Select(driver.findElement(By.id("selectyouindustry")));
dropdown.selectByVisibleText("Computer Software");
    

    
