package openfabrictesting;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;

import io.github.bonigarcia.wdm.WebDriverManager;

public class apps {

	public static void main(String[] args) throws InterruptedException {
		
		WebDriver driver = WebDriverManager.chromedriver().create();
		
		driver.get("https://accounts.google.com/");
		driver.manage().window().maximize();
		Thread.sleep(2000);
		driver.findElement(By.className("whsOnd zHQkBf")).sendKeys("atharvamithbawkar@gmail.com");
		driver.findElement(By.className("VfPpkd-vQzf8d")).click();
		Thread.sleep(2000);
		driver.findElement(By.className("whsOnd zHQkBf")).sendKeys("password");
		driver.findElement(By.className("VfPpkd-RLmnJb")).click();
		Thread.sleep(2000);
		driver.get("https://openfabric.dev/");
		driver.manage().window().maximize();
		driver.findElement(By.className("of-list__item-name")).click();
		driver.findElement(By.className("of__root of-theme--light of-menu--opened material-icons-loaded of-page--app-details")).click();
		Thread.sleep(2000);
		driver.findElement(By.id("mat-input-2")).sendKeys("Create an Image with a beautiful city landscape at night with flying cars");
		driver.findElement(By.className("mat-focus-indicator mat-menu-item ng-tns-c297-79 ng-star-inserted")).click();
		Thread.sleep(2000);
		driver.close();
		
	}

}
