# seleniumWithJava

package packageName;

import io.github.bonigarcia.wdm.WebDriverManager;

public class projectyahoo {

    WebDriver wd;

    @Before
    public void yahooFinanceHomePage(){

        WebDriverManager.chromedriver().setup();
        wd = new.ChromeDriver();
        wd.get();
    }
}
