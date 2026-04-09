# My-First-Code-in-Automation-Testing-
This is my first code in Automation Testing. I written this code using Java Programming language. Tools Used:- Eclipse as IDE, Maven for project creation, Selenium for Automation.

This is the Package: 
package FirstGo;

Import Command Statements are Here:-
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

This is the Code:- 
public class FirstGo {

public static void main(String[] args) {
		// TODO Auto-generated method stub

		String projectpath = System.getProperty("user.dir");
		System.out.println("projectPath:" + projectpath);
		
		System.setProperty("webdriver.chrome.driver", projectpath+"/Drivers/Chromedriver/chromedriver.exe");
		WebDriver driver = new ChromeDriver();
		driver.get("https://www.amazon.in/");
	}

}
