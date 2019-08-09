### Detect Selenium And Avoid

Here, I recommend an article [*<Detecting Selenium>*](https://edmundmartin.com/detecting-selenium/)

- If using selenium with chromedriver, we can set *excludeSwitches* as *[enable-automation]* to avoid detecting. Like below

  ``` python
  options.add_experimental_option('excludeSwitches', ['enable-automation'])
  ```

  

####  