# EngineerTestQA
var webdriver = require('selenium-webdriver');
var capabilities = {
    'browserName': 'Chrome'
  };
var browser = webdriver.Builder().withCapabilities(capabilities).build();
await browser.get('medseek-engineering.github.io/qa-engineer-test/');

var promise = driver.getTitle();promise.then(function(title));
console.log("Join the fight against bad bugs :" + title);

 driver.findElement(webdriver.By.id('Join The Fight')).click();

var header = driver.getHeader();promise.then(function(header));
console.log("Thank you for your interest:" + h1);


var name = driver.findElement(By.id('xyz'));
name.clear();
name.sendKeys("name");
    
var email = driver.findElement(By.id('xyz@gmail.com'));
email.clear();
email.sendKeys("email")

jobTitle.sendKeys("jobtitle"); var  = driver.findElement(By.id('xyz'));
jobtitle.clear();
jobtitle.sendKeys("title");

Company.sendKeys("company"); var driver.findelement(By.id('wxyz'));
company.clear();
company.sendKeys("company");

Select dropdown = new Select(driver.findElement(By.id("selectyourindustry")));
dropdown.selectByVisibleText("Computer Software");
    

    
