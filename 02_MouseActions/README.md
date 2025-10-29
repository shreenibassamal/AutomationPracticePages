# AutomationPracticePages

Here’s a **comprehensive list of actions** that testers or automation engineers perform on a **web application** — categorized for clarity.

---

### 🧩 **1\. Browser-Level Actions**

Performed using WebDriver/browser API:

* Open browser
    
* Navigate to URL
    
* Refresh/Reload page
    
* Go back / Go forward
    
* Get page title / URL
    
* Maximize / minimize / fullscreen window
    
* Handle multiple tabs or windows
    
* Capture screenshot
    
* Manage cookies (add, delete, get)
    

---

### 🖱️ **2\. Mouse Actions (User Interactions)**

Using `Actions` class or JavaScript:

* Click
    
* Double click
    
* Right click (context click)
    
* Mouse hover
    
* Drag and drop
    
* Click and hold
    
* Move to element
    
* Scroll (vertical/horizontal)
    
* Slider movement
    

---

### ⌨️ **3\. Keyboard Actions**

Using `sendKeys()` or `Actions` class:

* Type text
    
* Clear text
    
* Press keys (Enter, Tab, Escape, Ctrl+A, Ctrl+C, Ctrl+V)
    
* Use keyboard shortcuts
    
* Submit form using Enter
    

---

### 🔤 **4\. Web Element Actions**

Performed on page elements:

* Click on button, link, image
    
* Enter text in textbox / textarea
    
* Select option from dropdown (by visible text, value, index)
    
* Check/uncheck checkbox
    
* Select/deselect radio button
    
* Get text / attribute / CSS value
    
* Verify element is displayed, enabled, selected
    
* Upload file (sendKeys or Robot class)
    

---

### 🔄 **5\. Synchronization & Waiting**

* Implicit wait
    
* Explicit wait (WebDriverWait)
    
* Fluent wait
    
* Thread.sleep() (not recommended)
    

---

### 🧩 **6\. Frame, Alert, and Window Handling**

* Switch to frame (by index, name, or WebElement)
    
* Switch to parent frame or default content
    
* Handle alerts (accept, dismiss, getText, sendKeys)
    
* Handle multiple browser windows/tabs
    

---

### 📋 **7\. Table & Dynamic Elements**

* Get number of rows and columns
    
* Extract cell values
    
* Handle pagination
    
* Click dynamic elements using XPath/CSS
    
* Sort/filter validation
    

---

### 🔍 **8\. Validation & Assertions**

* Validate text or labels
    
* Verify page title / URL / element visibility
    
* Check button enable/disable status
    
* Assert with TestNG or JUnit
    
* Compare expected vs actual result
    

---

### 🌐 **9\. JavaScript Executor Actions**

* Click element using JS
    
* Scroll into view / scroll to bottom
    
* Get inner text / attributes using JS
    
* Change element style dynamically
    
* Handle hidden elements
    
* Refresh using JS
    

---

### 📦 **10\. File Handling**

* Upload files
    
* Download files
    
* Read from Excel, CSV, JSON, or property files
    
* Write logs or results
    

---

### 📶 **11\. API / Network Related**

(For integrated UI + API testing)

* Validate backend response
    
* Verify API trigger after UI action
    
* Mock API responses
    

---

### 🧠 **12\. Other Advanced Actions**

* Shadow DOM element handling
    
* Web component interaction
    
* Captcha handling (manual or API-based)
    
* OTP/email validation
    
* Accessibility testing actions
    
* Performance metrics via DevTools
    

---

### 🧪 **13\. Automation Framework-Level Actions**

* Logging (Log4j, SLF4J)
    
* Reporting (Extent, Allure, TestNG)
    
* Parameterization (DataProvider, Excel, JSON)
    
* Cross-browser testing
    
* Jenkins integration for CI/CD